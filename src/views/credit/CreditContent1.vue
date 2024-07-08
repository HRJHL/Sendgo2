<template class="tem">
  <div class="main-content bg-white w-[1920px] h-[100px] mt-[70px] flex items-center">
    <div class="text-content flex-1">
      <div class="btn-group flex justify-end mr-[600px] gap-10">
        <button class="btn1 w-[156px] h-[56px] rounded-[13px] text-[20px]"
        style="background-color: #E1E7FD; color:#4F44F0;">크래딧 구매</button>
        <button class="btn2 w-[156px] h-[56px] rounded-[13px] bg-white text-[20px] text-black">크래딧 내역</button>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CreditContent1'
};
</script>

<style scoped>
html,body{
    overflow-x: hidden;
    width: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
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
    height: 80px;
    padding: 0 20px;
  }
  .btn-group {
    flex-direction: row;
    gap: 5px;
    justify-content: center; 
    align-items: flex-end;
    margin-left: 150px;
  }
  .btn1, .btn2{
    width: 90px;
    height: 45px;
    font-size: 15px;
  }
}
</style>
