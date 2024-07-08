<template>
  <footer class="footer main-footer">
    <div id="app">
    <footer class="footer">
      <nav class="nav2">
        <router-link to="/" class="logo">
          <img src="@/assets/logo2.svg" alt="Logo" />
        </router-link>
        <div class="nav2-links">
          <router-link to="/message" class ="mess">메시지</router-link>
          <router-link to="/credit" class ="credit">크레딧</router-link>
        </div>
      </nav>
      <div class="textbox">
        <span class="text1">문의 사항이 있으신가요? 텔레그램을 통해 고객센터로 문의해 보세요.</span>
        <span class="text2">Telegram: @shdevelope</span>
      </div>
  </footer>
    <router-view />
  </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter'
};
</script>

<style scoped>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-items: center;
  overflow-x:hidden;
}


.footer {
  background-color: rgba(0, 0, 0, 0.535);
}

.nav2 {
  display: flex;
  align-items: center;
  width: 100%;
  height: 100px;
  box-sizing: border-box;
  border-top: 1px solid #84848495;
  border-bottom: 1px solid #84848495;

}

.textbox {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 150px;
  margin-left: 10%;
  margin-right: 10%;
}

.mess{
  font-size: 16px;
}
.credit{
  font-size: 16px;
}

.text1 {
  margin-top: 30px;
  color :rgba(255, 255, 255, 0.756);
  font-size: 16px;
}

.text2 {
  margin-top: 10px;
  color :white;
  font-size: 16px;
}

.logo {
  margin-left: 10%;
  margin-right: 25%;
  margin-top: 10px;
  width: 142px;
  height: 44px;
}


.nav2-links {
  display: flex;
  gap: 50px;
}

.nav2-links a {
  color: white;
  text-decoration: none;
  font-size: 12px;
}

.nav2-links a:hover {
  color: white;
}




@media (max-width: 480px) {
  body{
    overflow: hidden;
    width: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
  }
  .main-content {
    width: 100%;
  }
  .nav2 {
    height: 50px;
    flex-direction: row;
    justify-content: start;
    align-items: center;
  }
  .nav2-links {
    flex-direction: row;
    margin-left: -80px;
  }

  .text1, .text2 {
    font-size: 12px;
  }
}
</style>

