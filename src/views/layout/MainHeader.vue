<template>
  <header class="header main-header">
    <div id="app">
    <header class="header">
    <nav class="nav">
        <router-link to="/" class="logo">
          <img src="@/assets/logo2.svg" alt="Logo" />
        </router-link>
        <div class="nav-links">
          <router-link to="/message" class ="mess">메시지</router-link>
          <router-link to="/credit" class ="credit">크레딧</router-link>
        </div>
      </nav>
  </header>
    <router-view />
  </div>
  </header>
</template>

<script>
export default {
  name: 'MainHeader'
};
</script>

<style scoped>
.body {
  margin: 0;
  font-family: Arial, sans-serif;
}

.header {
  padding: 10px 20px;
  background-color: black;
  height: 70px;
  display: flex;
  align-items: center;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  z-index: 100000;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.nav {
  display: flex;
  align-items: center;
  width: 100%;
}

.logo {
  margin-left: 10%;
  margin-right: 10%;
  height: 30px;
}

.logo img {
  height: 30px;
}


.nav-links {
  display: flex;
  gap: 100px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-size: 16px;
}

.nav-links a:hover {
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
  .header {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: 10000;
    background-color: black;
    widows: 480px;
    height: 70px;
    display: flex;
    align-items: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    border-bottom: 1px solid #84848495;
  }

.nav-links {
  display: flex;
  gap: 70px;
}

.logo {
  margin-left: 5%;
  margin-right: 10%;
  height: 30px;
}
}
</style>

