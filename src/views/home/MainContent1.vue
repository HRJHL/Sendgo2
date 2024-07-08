<template class="tem">
  <div class="main-content flex bg-black text-white w-full h-780 px-20">
    <div class="text-content flex-1 flex flex-col justify-center items-center">
      <div class="texbox text-start">
        <span class="text1 text-white text-[24px] font-bold mb-4">인터넷 문자 메시지 전송의 모든것<br><br></span>
        <span class="text2 text-[56px] font-bold"
        style="background-image: linear-gradient(to right, #9FBAFD, #4E81FF);
        background-clip: text;
        -webkit-background-clip: text;
        color: transparent;">
        가장 빠르고 안정적인<br>문자 서비스 SENDGO</span>
        <div class="button-content flex mt-[50px]">
          <span class="text3 rounded-[44px] w-[206px] h-[65px] text-white px-6 py-4 text-center 
          text-[21px] font-normal"
          style="background-color : #6250FF">회원가입</span>
          <span class="text4 ml-4 rounded-[44px] w-[206px] h-[65px] text-white px-6 py-4
          text-center text-[21px] font-normal"
          style="background-color:#242424">로그인</span>
        </div>
      </div>
    </div>
    <div class="flex flex-1 flex-col">
    <div class="icontent flex-1 flex flex-row gap-[20px]">
      <img src="@/assets/main/1p1.png" class="Image1 w-[204px] h-[393px] mt-[150px] rounded-[22px]" style="background-color: rgb(106, 106, 230);" />
      <img src="@/assets/main/1p2.png" class="Image2 w-[204px] h-[404px] mt-[70px] rounded-t rounded-[22px]" style="background-color: rgb(72, 55, 55);" />
      <img src="@/assets/main/1p3.png" class="Image3 w-[204px] h-[476px] mt-[-200px] rounded-[22px]" style="background-color: rgb(106, 106, 230);" />
    </div>
    <div class="icontent flex-1 flex flex-row gap-[20px] mt-[40px]">
      <img src="@/assets/main/1p4.png" class="Image4 relative w-[204px] h-[388px] rounded-b rounded-[22px]" style="background-color: rgb(72, 55, 55); z-index: 5;" />
      <img src="@/assets/main/1p5.png" class="Image5 relative w-[204px] h-[464px] mt-[-75px] rounded-b rounded-[22px]" style="background-color: rgb(106, 106, 230); z-index: 5;" />
      <div class="Image6 w-[204px] h-[559px] mt-[-300px] mt-[-270px] rounded-[22px]" style="background-color: rgb(72, 55, 55);">
        <img src="@/assets/main/1p6.png" class="Image7 absolute w-[290px] h-[609px]" style="margin-top: -100px;" />
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'MainContent1'
};
</script>

<style scoped>

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
    height: 1080px;
    flex-direction: column;
  }

  .texbox {
    margin-top: 100px;
  }

  .text1{
    font-size: 16px;
  }
  .text2{
    font-size: 25px;
  }

  .text3{
    width:100px;
    height: 50px;
    font-size: 14px;
  }

  .text4{
    width:100px;
    height: 50px;
    font-size: 14px;
  }

  .icontent {
    margin-top: 200px;
    display: flex;
    flex-direction: row;
    margin-right: -50px;
    margin-left: -50px;
  }

  .Image1{
    width:100px;
    height: 200px;
    position: relative;
    top:-200px;
    border-radius: 22px;
  }
  .Image2{
    width:100px;
    height: 200px;
    position: relative;
    top:-180px;
    border-radius: 22px;
  }
  .Image3{
    width:100px;
    height: 200px;
    position: relative;
    top: 150px;
    border-radius: 22px;
  }
  .Image4{
    width:100px;
    height: 200px;
    position: relative;
    top:-380px;
    border-radius: 22px;
  }
  .Image5{
    width:100px;
    height: 200px;
    position: relative;
    top:-230px;
    border-radius: 22px;
  }
  .Image6{
    width:100px;
    height: 200px;
    position: relative;
    top:-80px;
    border-radius: 22px;
  }
  .Image7{
    width:100px;
    height: 250px;
    position: relative;
    top: 70px;
  }
}
</style>
