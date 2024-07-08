<template class="tem">
  <div class="main-content flex flex-col justify-center items-center bg-white text-black w-full h-full p-20 box-border">
    <div class="content mt-20 mb-25">
      <img src="@/assets/icon1/know.png" class="know w-[79px] h-[80px] mb-10" />
    </div>
    <div class="content2 text-center mb-20">
      <div class="tex1 mb-5">
        <span class="text1 text-[56px] font-bold">샌드고의 다양한<br>기능들을 살펴보세요<br></span>
      </div>
      <div class="tex2">
        <span class="text2 text-[26px] font-normal" style="color: #5C5C5C">고객님들 입장에서 고민하였습니다.</span>
      </div>
    </div>
    <div class="content3 flex justify-around items-center flex-grow mt-30">
      <div class="box1 w-[626px] h-[597px] flex flex-col justify-start items-star rounded-xl p-10 ml-10"
      style="background-color:#F8F9FA">
        <div class="boxtex11 mt-10 ml-5 text-[34px] font-bold text-black">
          <span>자주 전송하는 내용이 있나요?</span>
        </div>
        <div class="boxtex12 mt-3 ml-5 mb-[70px] leading-10 text-[34px] font-bold"
        style="color:#727B88">
          <span>템플릿으로 메시지 내용을<br>저장하여 간편하게 전송하세요.</span>
        </div>
        <img src="@/assets/main/3p1.png" class="a w-[572px] h-[320pxs] ml-10" />
      </div>
      <div class="box2 w-[750px] h-[597px] flex flex-col justify-start items-start rounded-xl p-10 ml-10"
      style="background-color:#E9EBFD">
        <div class="boxtex21 mt-10 ml-5 text-[34px] font-bold"
        style="color:#6264F6">
          <span>크레딧 구매 시, 보너스 크레딧 증정</span>
        </div>
        <div class="boxtex22 mt-3 ml-5 mb-[53px] leading-10 text-[34px] font-bold text-blue-600"
        style="color:#7079CB">
          <span>크레딧 상품을 구매하면 상품 별<br>보너스 크레딧을 증정합니다</span>
        </div>
        <img src="@/assets/main/3p2.png" class="b w-[644px] h-[321px]" />
      </div>
    </div>
    <div class="content4 flex justify-around items-center flex-grow mt-10">
      <div class="box3 w-[855px] h-[720px] flex flex-col justify-start items-start rounded-xl p-10 ml-10"
      style="background-color:#DBE5FF">
        <div class="boxtex31 mt-10 ml-5 text-[34px] font-bold"
        style="color:#375984">
          <span>전송 후 바로 발송확인 기능</span>
        </div>
        <div class="boxtex32 mt-3 ml-5 mb-10 leading-10 text-[34px] font-bold"
        style="color: #698AB1">
          <span>메시지 전송 후 바로 발송현황 창에서<br>현재 메시지 전송 현황을 알려드립니다</span>
        </div>
        <img src="@/assets/main/3p3.png" class="c w-[798px] h-[427px] mt-[50px] ml-[60px]" />
      </div>
      <div class="box4 w-[520px] h-[720px] flex flex-col justify-start items-start rounded-xl p-10 ml-10"
      style="background-color:#FAFAEE">
        <div class="boxtex41 mt-10 ml-5 text-[34px] font-bold"
        style="color:#6C3111">
          <span>누르면 바로 전송완료</span>
        </div>
        <div class="boxtex42 mt-3 ml-5 mb-20 leading-10 text-[34px] font-bold"
        style="color:#6F6F6F">
          <span>누르자마자 수신인에게<br>바로 전달됩니다.</span>
        </div>
        <img src="@/assets/main/3p4.png" class="d mt-10 w-[416px] h-[432px] mt-[-5px]" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainContent3'
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
    margin-top: 400px;
    padding: 20px;
  }

  .text1{
    font-size: 36px;
  }

  .text2{
    font-size: 18px;
  }

  .box1, .box2, .box3, .box4 {
    width: 320px;
    height: 400px;
    margin-bottom: 50px;
    padding: 20px;

  }
  .content3{
    flex-direction: column;
    display: flex;
    align-items: start;
    justify-content: start;
    margin-right: 40px;
  }

  .content4{
    flex-direction: column;
    align-items: start;
    justify-content: start;
    margin-right: 40px;
  }

  .boxtex11 {
    font-size: 20px;
  }

  .boxtex21 {
    font-size: 18px;
  }

  .boxtex31 {
    font-size: 20px;
  }

  .boxtex41 {
    font-size: 20px;
  }

  .boxtex12, .boxtex22, .boxtex42 {
    font-size: 20px;
  }
  .boxtex32 {
    font-size: 17px;
  }
  .a {
    width: 300px;
    height: 300px;
    margin-left: 20px;
    margin-top: -9px;
  }

  .b {
    width:400px;
    height: 200px;
    margin-top: 28px;
  }

  .c {
    width:400px;
    height: 300px;
    margin-top: 30px;
    margin-left: 30px;
  }

  .d {
    width:200px;
    height: 200px;
    margin-top: -60px;
    margin-left: 30px;
  }

}
</style>