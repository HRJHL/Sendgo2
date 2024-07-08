<template class="tem">
  <div class="main-content bg-white text-black flex flex-col justify-center items-center p-20">
    <div class="content mt-20 mb-5">
      <img src="@/assets/icon1/depend.png" class="depend w-[80px] h-[80px]" />
    </div>
    <div class="content2 text-center mb-10">
      <div class="tex1 mb-2">
        <span class="text1 text-[56px] font-bold">정확도와 다양함은 물론<br>신뢰할 수 있는 보안까지</span>
      </div>
      <div class="tex2 text-[26px]" style="color: #5C5C5C">
        <span class="text2">고객님들 입장에서 고민하였습니다.</span>
      </div>
    </div>
    <div class="content3 flex justify-around items-center mt-5">
      <div class="box1 w-[688px] h-[597px] rounded-lg p-4"
      style="background-color: #DCEFF4">
        <div class="boxtex11 mb-3 text-[34px] font-bold text-black mt-[50px] ml-[20px]">
          <span class="boxtext11">일반 SMS는 기본, 카카오톡까지</span>
        </div>
        <div class="boxtex12 mb-8 text-[34px] font-bold ml-[20px]"
        style="color: #516B71">
          <span class="boxtext12">종류와 상관없이 모두 전송해 드립니다</span>
        </div>
        <img src="@/assets/main/4p1.png" class="a w-[382px] h-[310px] pl-24 ml-[80px]" />
      </div>
      <div class="box2 w-[688px] h-[597px] rounded-lg p-4 ml-[20px]"
      style="background-color: #FBFBEF">
        <div class="boxtex21 mb-3 text-[34px] font-bold mt-[50px] ml-[20px]"
        style="color: #431B06">
          <span class="boxtext21">강력한 보안을 제공합니다.</span>
        </div>
        <div class="boxtex22 mb-16 text-[34px] font-bold ml-[20px]"
        style="color: #696156">
          <span class="boxtext22">신뢰할 수 있는 최신의 보안 시스템을<br>적용하여 개인정보를 보호합니다.</span>
        </div>
        <img src="@/assets/main/lock.png" class="b w-[385px] h-[288px] pl-40 ml-[120px]" />
      </div>
    </div>
    <div class="content4 mt-5">
  <div class="box3 w-[1420px] h-[495px] rounded-lg p-4 flex flex-col justify-center items-center"
  style="background-color: #F8F9FA">
    <div class="boxtex31 mb-3 text-[34px] font-bold text-black mt-[30px]">
      <span class="boxtext31">놀라운 수신율을 경험해 보세요</span>
    </div>
    <div class="boxtex32 mb-2 text-[34px] font-bold"
    style="color:#727B88">
      <span class="boxtext32">샌드고의 정확한 수신율은 99.8%에 달합니다</span>
    </div>
    <img src="@/assets/main/4p3.png" class="c w-3/5 h-4/5 pl-8 mt-[15px]" />
  </div>
</div>

  </div>
</template>

<script>
export default {
  name: 'MainContent4'
};
</script>

<style scoped>

@media (max-width: 480px) {
  hmtl,body{
    overflow-x: hidden;
    width: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
  }

  .main-content {
    width: 100%;
    margin-top: -100px;
    padding: 20px;
  }

  .text1{
    font-size: 32px;
  }

  .text2{
    font-size: 18px;
  }

  .content3 {
    flex-direction: column;
  }

  .box1, .box2, .box3 {
    width: 320px;
    height: 400px;
    margin-bottom: 30px;
  }

  .box2 {
    margin-left: -10px;
  }
  
  .box3 {
    height: 250px;
  }
  .boxtex11, .boxtex21, .boxtex31 {
    margin-top: 30px;
    font-size: 20px;
  }

  .boxtex12, .boxtex22, .boxtex32 {
    font-size: 16px;
  }

  .boxtex32{
    margin-bottom: 20px;
  }

  .a {
    width: 500px;
    height: 200px;
    margin-left: -40px;
    margin-top: 40px;
  }
  
  .b {
    margin-top: -30px;
    margin-left: -60px;
    width: 400px;
    height: 200px;
  }

  .c {
    width: 300px;
    height: 150px;
    margin-left: -30px;
    margin-top: 30px;
  }
}
</style>