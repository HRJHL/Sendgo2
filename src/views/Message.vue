<template>
  <div class="main-content">
    <MessageContent1 />
    <MessageContent2 />
    <AppFooter />
  </div>
</template>

<script>
import AppFooter from './layout/AppFooter.vue';
import MessageContent1 from './message/MessageContent1.vue';
import MessageContent2 from './message/MessageContent2.vue';

export default {
  name: 'MessagePage',
  components: {
    MessageContent1,
    MessageContent2,
    AppFooter
  }
};
</script>

<style scoped>
.body{
  overflow-x: hidden;
}
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
  
}


</style>
