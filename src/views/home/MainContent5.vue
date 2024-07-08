<template class="tem">
  <div class="main-content bg-black text-white flex justify-center items-center h-[1080px] mt-[100px] px-20">
    <div class="text-content text-center">
      <div class="texbox">
        <div class="text1 text-[56px] font-bold mb-[60px]"
        style="background-image: linear-gradient(to left, #B6B7F7, #7FB2FE);
        background-clip: text;
        -webkit-background-clip: text;
        color: transparent;">
          <span>
            비지니스 광고의 시작,<br>이제 샌드고와 함께 하세요
          </span>
        </div>
        <div class="button-content">
          <span class="text2 inline-block rounded-full text-white px-6 py-3 text-center text-[21px] 
          font-bold cursor-pointer transition duration-300 ease-in-out hover:bg-blue-600"
          style="background-color: #6250FF">
          메시지 바로가기
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainContent5'
};
</script>

<style scoped>

@media (max-width: 480px) {
  body{
    overflow-x: hidden;
    width: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
  }
  .main-content {
    width: 100%;
    margin-top: 50px;
    padding:20px;
    margin-bottom: -250px;
  }

  .text1 {
    margin-top: -200px;
    font-size: 32px;
  }
}
</style>
