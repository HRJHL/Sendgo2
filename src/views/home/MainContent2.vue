<template class="tem">
  <div class="main-content bg-white text-black flex flex-col justify-center items-center w-full h-screen px-20 relative z-10">
    <div class="content mt-32 mb-10">
      <img src="@/assets/icon1/message.png" class="w-[64px] h-[64px]" />
    </div>
    <div class="content2 text-center mb-5">
      <div class="tex1">
        <span class="text1 text-[56px] font-bold leading-tight">복잡한 인터넷 문자 서비스를<br>간편하게 만나보세요<br></span>
      </div>
      <div class="tex2 mt-3">
        <span class="text2 text-[26px]" style="color:#5C5C5C">모든 종류의 인터넷 SMS를 편리하게</span>
      </div>
    </div>
    <div class="content3 flex justify-around items-center flex-grow z-0 mt-10">
      <div class="box1 w-[444px] h-[339px] flex flex-col justify-center items-center rounded-xl p-4 mx-4 text-center" style="background-color: #F0F0FA">
        <img src="@/assets/icon1/pen.png" class="w-[64px] h-[64px]" />
        <div class="boxtex1 mt-4">
          <span class="boxtext1 text-[26px] font-bold leading-tight">메시지 용량에<br>제한 받지 않고 전송<br></span>
        </div>
        <div class="boxtex2 mt-2">
          <span class="boxtext2 text-[20px]" style="color: #6E7583">메시지 용량 걱정없이 단문 메시지는<br>물론 장문, 사진까지 전송이 가능합니다.</span>
        </div>
      </div>
      <div class="box2 w-[444px] h-[339px] flex flex-col justify-center items-center rounded-xl p-4 mx-4 text-center" style="background-color: #F0F0FA">
        <img src="@/assets/icon1/mail.png" class="w-[64px] h-[64px]" />
        <div class="boxtex1 mt-4">
          <span class="boxtext1 text-[26px] font-bold leading-tight">모든 종류의<br>문자 메시지를 한번에<br></span>
        </div>
        <div class="boxtex2 mt-2">
          <span class="boxtext2 text-[20px]" style="color: #6E7583">메시지 용량 걱정없이 단문 메시지는<br>물론 장문, 사진까지 전송이 가능합니다.</span>
        </div>
      </div>
      <div class="box3 w-[444px] h-[339px] flex flex-col justify-center items-center rounded-xl p-4 mx-4 text-center" style="background-color: #F0F0FA">
        <img src="@/assets/icon1/mega.png" class="w-[64px] h-[64px]" />
        <div class="boxtex1 mt-4">
          <span class="boxtext1 text-[26px] font-bold leading-tight">간편한 광고<br>문자 메시지 설정</span>
        </div>
        <div class="boxtex2 mt-2">
          <span class="boxtext2 text-[20px]" style="color: #6E7583">광고 설정 버튼 클릭 한번으로<br>080 수신 거부 번호가 적용됩니다.</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainContent2'
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
    margin-top: 350px;
    padding:20px;
  }

  .text1 {
    font-size: 30px;
  }
  .text2 {
    font-size: 16px;
  }
  .content3 {
    flex-direction: column;
  }

  .box1, .box2, .box3 {
    width: 320px;
    margin-bottom: 40px;
  }

  .boxtext2{
    font-size: 18px;
  }
}
</style>