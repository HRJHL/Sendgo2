<template>
  <div class="main-content">
    <MainHeader />
    <MainContent1 />
    <MainContent2 />
    <MainContent3 />
    <MainContent4 />
    <MainContent5 />
    <AppFooter />
  </div>
</template>

<script>
import MainHeader from './layout/MainHeader.vue';
import MainContent1 from './home/MainContent1.vue';
import MainContent2 from './home/MainContent2.vue';
import MainContent3 from './home/MainContent3.vue';
import MainContent4 from './home/MainContent4.vue';
import MainContent5 from './home/MainContent5.vue';
import AppFooter from './layout/AppFooter.vue';

export default {
  name: 'HomePage',
  components: {
    MainHeader,
    MainContent1,
    MainContent2,
    MainContent3,
    MainContent4,
    MainContent5,
    AppFooter
  }
};
</script>

<style scoped>
.content {
 margin-top: 10%;
}
@media (max-width: 480px) {
  html,body{
    overflow-x: hidden;
    width: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
  }
  .main-content {
    width: 100%;
  }
}

</style>
