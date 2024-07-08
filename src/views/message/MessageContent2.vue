<template class="tem">
  <div class="main-content bg-gray-200 text-black">
    <div class="text-content h-[2481px] flex flex-col items-center" style="background-color: #F2F4F8">
      <div class="head rounded-[24px] flex flex-col items-center w-[1223px] h-[2213px] bg-white mt-[68px]">
      <div class="border-b border-gray-400 mb-[30px] flex flex-col items-center">
        <div class="name text-[38px] font-bold mt-[53px] mb-4">메시지 전송</div>
        <div class="btnGroup mt-[20px] flex gap-[16px] mb-[20px]">
          <button class="btn1 w-[333px] h-[66px] rounded-[8px] text-[22px]"
          style="background-color: #4F44F0; color:white;">문자메시지</button>
          <button class="btn2 text-gray-600 w-[333px] h-[66px] rounded-[8px] text-[22px]"
          style="background-color: #F5F6FA; color:#555555;">알림톡(카카오)</button>
          <button class="btn3 text-gray-600 w-[333px] h-[66px] rounded-[8px] text-[22px]"
          style="background-color: #F5F6FA; color:#555555;">친구톡(카카오)</button>
        </div>
        <div class="scGroup flex flex-col items-start mr-[570px] mb-[30px]">
          <span class="sc1 text-sm">간편하게 한 화면에서 단문, 장문 포토메시지를 발송할 수 있습니다.</span>
          <span class="sc2 text-sm">90byte 초과 시 장문문자로 자동 전환되며, 최대 2,000byte까지 작성이 가능합니다.</span>
        </div>
      </div>
      <div class="content1 flex ml-[-10px] border-b border-gray-400 mb-[30px]">
        <div class="memo flex-1 mb-[20px]">
          <div class="con1 border-b border-gray-400 mb-[20px]">
            <div class="text1 text-[24px] font-semibold">수신번호</div>
            <div class="phone flex items-center mt-2">
              <input type="tel" name="pnumber" placeholder="휴대폰번호(숫자만 입력)" class="pnum1 rounded-[8px] w-[439px] h-[61px] text-[18px] px-[20px]"
              style="background-color:#F4F5F6; color:#7B7B7B">
              <button class="pbtn text-[20px] text-white w-[114px] h-[61px] ml-4 rounded-[8px]"
              style="background-color:#4F44F0">+ 추가</button>
            </div>
            <textarea placeholder="번호를 입력하거나 후 엔터 혹은 추가하기를 클릭해 주세요.
최대1만자건까지 붙여넣기 가능합니다."
            class="textarea1 w-[562px] h-[238px] mt-4 p-4 rounded-[8px]"
            style="border: 1px solid #CECECE; resize: none;"></textarea>
            <span class="areatext1 absolute bg-white text-[18px] px-2 py-1 mt-[200px] ml-[-540px]">총 <span class="atr text-blue-500">0</span>명</span>
            <span class="areatext2 absolute bg-white text-[18px] px-2 py-1 mt-[200px] ml-[-100px]">모두 삭제</span>
            <div class="groupbtn flex flex-grow mt-4 mb-[30px]">
              <button class="abtn bg-white w-[182px] h-[61px] rounded-[8px] text-[16px] flex flex-grow items-center"
              style="border: 1px solid #CECECE; color:#7B7B7B">
              <img src="@/assets/icon2/person.png" class="icon-person w-[32px] h-[32px] ml-[20px] items-center"/>
              주소록 불러오기</button>
              <button class="bbtn bg-white ml-[5px] w-[182px] h-[61px] rounded-[8px] text-[16px] flex flex-grow items-center"
              style="border: 1px solid #CECECE; color:#7B7B7B">
               <img src="@/assets/icon2/file.png" class="icon-file w-[32px] h-[32px] ml-[20px] items-center"/>
              파일 불러오기</button>
              <button class="cbtn bg-white ml-[5px] w-[182px] h-[61px] rounded-[8px] text-[16px] flex flex-grow items-center"
              style="border: 1px solid #CECECE; color:#7B7B7B">
               <img src="@/assets/icon2/recent.png" class="icon-recent w-[32px] h-[32px] ml-[20px] items-center"/>
              최근 전송 내역</button>
            </div>
          </div>
          <div class="con2 border-b border-gray-400 mb-[30px]">
            <div class="text2 text-[22px] font-semibold mb-[10px]">발신번호</div>
            <div class="phone2">
            <input type="text" name="resphone" class="pnum2 mb-[30px] px-[20px] rounded-[8px] w-[565px] h-[61px] text-[18px]" placeholder="전송할 발신번호 선택" readonly
            style="background-color:#F4F5F6; color:#7B7B7B;">
             <img src="@/assets/icon2/bottom_arrow.png" class="icon-arrow absolute w-[32px] h-[32px] mt-[-75px] ml-[515px] items-center"/>
          </div>
          </div>
          <div class="con3">
            <div class="text3 text-[22px] font-semibold">메시지 입력</div>
            <div class="box mt-4 w-[561px] h-[783px] mb-[30px] rounded-[8px]"
            style="background-color: #F6F6F6; border: 1px solid #E1E3E5;">
              <div class="boxcon1 mt-[20px] ml-[20px] mr-[20px] border-b border-gray-400 mb-[30px]">
                <input type="text" name="title" placeholder="제목을 입력해주세요 (단문 SMS는 제외, 최대 30byte)" 
                class="pnum3 rounded-[8px] text-[18px] px-[20px] w-[513px] h-[61px]"
                style="background-color:#FFFFFF; border: 1px solid #CECECE; color:#7B7B7B;">
                <div class="boxbtn flex items-center mt-[20px]">
                  <button class="btnbox text-white px-4 py-1 w-[101px] h-[35px] rounded-[35px] text-[16px]"
                  style="background-color:#5E2BFF;">단문 SMS</button>
                  <div class="byte ml-[-30px]">
                  <span class="bytetext ml-[320px] text-[16px]" style="color:#5E2BFF">0</span><span class="bytetext ml-1 text-[16px]">/90byte</span>
                  </div>
                  <img src="@/assets/icon2/reroll.png" class="w-[35px] h-[35px] ml-[15px]"/>
                </div>
                <div class="textbox">
                <textarea placeholder="내용을 입력해주세요. 90byte 초과 시 문자로, 
이미지 추가 시 포토문자로 자동 전환됩니다." 
                class="textarea2 mt-4 w-[513px] h-[295px] p-4 rounded-[8px] mb-[20px]"
                style="border: 1px solid #CECECE; resize:none;"></textarea>
                <button class="tbox1 absolute mt-[255px] ml-[-370px] px-4 py-2 w-[107px] h-[43px] rounded-[22px] text-[16px]"
                  style="background-color:#F5F5F5; color:#646464">치환코드</button>
                  <button class="tbox2 absolute mt-[255px] ml-[-250px] px-4 py-2 w-[107px] h-[43px] rounded-[22px] text-[16px]"
                  style="background-color:#F5F5F5; color:#646464">템플릿</button>
                  <button class="tbox3 absolute mt-[255px] ml-[-130px] px-4 py-2 w-[107px] h-[43px] rounded-[22px] text-[16px]"
                  style="background-color:#F5F5F5; color:#646464">문자도구</button>
                  </div>
              </div>
              <div class="boxcon2 flex flex-grow items-center contents-center ml-[20px] mr-[20px]">
                <div class="con2text text-[18px] font-semibold mb-[20px]">광고성 문자(080 수신거부번호 포함)</div>
                <img src="@/assets/icon2/togle.png" class="icon-togle w-[59px] h-[32px] mb-[20px] ml-[180px]"/>
              </div>
              <div class="boxcon3 mt-[10px] ml-[20px] mr-[20px] py-[10px] border-t border-gray-400">
                <div class="mb-[10px]">
                  <span class="text-[18px] font-semibold">이미지 추가</span>
                </div>
                <img src="@/assets/icon2/white_plus.png" class="w-[100px] h-[100px] mb-[10px]"/>
                <div>
                <span class="scripttext text-[16px]" style="color:#797979">이미지는 최대 3장까지 첨부 가능합니다.</span><br>
                <span class="scripttext text-[16px]" style="color:#797979">이미지 파일 형식은 JPG, PNG, GIF만 가능합니다.</span>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="area flex-1 ml-[40px]">
          <div ref="deviceElement" class="device sticky top-20 w-[401px] h-[775px] rounded-[22px] mb-[40px]"
          style="background-color:#EAF8FF; border: 5px solid #4D4D4D;">
          <img src="@/assets/icon2/bottom_arrow.png" @click="handleClick2" class="btnEvent w-[46px] h-[46px] rotate-90 mt-[27px] ml-[18px]"/>
          </div>
          <div @click="handleClick" ref ="checkElement" class="checkbtn btnEvent sticky top-40 w-[0px] h-[0px]">
            <img src="@/assets/icon2/bottom_arrow.png" class="checkdevice w-[0px] h-[0px] rotate-90 mt-[27px] ml-[18px]"/>
          </div>
        </div>
      </div>
      <div class="content2 w-[1031px] mb-[0px]">
        <div class="content2text mb-[20px]">
          <span class="c2t1 text-[22px] font-semibold">발송 설정</span>
        </div>
        <div class="flex flex-grow">
          <div class="sendbox flex-1 flex flex-grow">
        <button class="sendbtn1 w-[274px] h-[66px] rounded-[8px] text-[22px] gap-[5px] ml-4 flex flex-grow items-center justify-center"
        style="background-color:white; color:#4F44F0; border: 2px solid #4F44F0;">
        <img src="@/assets/icon2/blue_check.png" class="w-[32px] h-[32px] ml-[-32px]"/>
        즉시발송</button>
        <button class="sendbtn2 w-[274px] h-[66px] rounded-[8px] text-[22px] gap-[5px] ml-4 flex flex-grow items-center justify-center mb-[40px]"
        style="background-color:#F2F5F9; color:#747B84; ">
        <img src="@/assets/icon2/grey_check.png" class="w-[32px] h-[32px] ml-[-32px]"/>
        예약발송</button>
        </div>
        <div class="flex-1"></div>
        </div>
      </div>
      <div class="content3  border-t border-gray-400 py-[30px]">
        <button class="sendbtn3 text-white w-[1031px] h-[66px] text-[22px] rounded-[8px]"
        style="background-color: #4F44F0">발송하기</button>
      </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: 'MessageContent2',
  methods: {
    handleClick() {
      const deviceElement = this.$refs.deviceElement;
      const checkElement = this.$refs.checkElement;
      deviceElement.style.display = 'block';
      checkElement.style.display='none';
    },
    handleClick2() {
      const deviceElement = this.$refs.deviceElement;
      const checkElement = this.$refs.checkElement;
      deviceElement.style.display = 'none';
      checkElement.style.display='block';
    }
  }
};

</script>

<style scoped>
.body{
  overflow-x: hidden;
}

@media (max-width: 480px) {
  
  .main-content {
    padding: 0 px;
  }
  .head {
    width: 90%;
    
  }
  .content1 {
    margin-left: 0;
  }

  .btnGroup{
    display: felx;
    flex-direction: row;
  }
  .btn1, .btn2, .btn3 {
    width: 100px;
    height: 50px;
    font-size: 15px;
  }

  .scGroup {
    margin-right: 0;
  }
  .sc1 {
    font-size: 10px;
  }
  .sc2 {
    font-size: 10px;
  }

  .con1, .con2, .content2, .content3 {
    display: flex;
    flex-direction: column;
    align-items: center;
    width:100%;
  }

  .content3{
    width:300px;
  }

  .memo{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 320px;
  }

  .con3 {
    display: flex;
    flex-direction: column;
    align-items: center;
    width:500px;
  }
  
  .text1{
    margin-bottom: 10px;
  }

  .phone {
    width:90%;
  }
  .pnum1{
    width: 200px;
    height: 50px;
    font-size: 15px;
  }

  .pbtn{
    width: 120px;
    height: 50px;
    margin-left: 10px;
    font-size: 15px;
  }

  .textarea1{
    width: 300px;
    font-size: 16px;
  }

  .areatext1 {
    margin-top: 320px;
    margin-left: -220px;
    font-size: 15px;
  }

  .areatext2 {
    margin-top: 320px;
    margin-left: 200px;
    font-size: 15px;
  }

  .groupbtn  {
    width: 300px;
  }

  .abtn, .bbtn, .cbtn {
    font-size: 10px;
    height: 40px;
    display: flex;
    align-items: center;
  }

  .icon-person, .icon-file, .icon-recent {
    width: 16px;
    height: 16px;
    margin-left: 10px;
  }

  .pnum2{
    width:300px;
  }

  .icon-arrow {
    margin-left: 250px;
  }

  .box {
    width: 60%;
  }

  .pnum3{
    width: 100%;
    height: 40px;
    font-size: 10px;
  }

  .btnbox{
    width: 100px;
    height: 30px;
    font-size: 14px;
  }

  .byte {
    margin-left: -250px;
  }
  .bytetext{
    font-size: 13px;
    margin-right: -5px;
  }

  .textbox{
    width:100%;
  }

  .textarea2{
    width:100%;
    font-size: 12px;
  }

  .tbox1, .tbox2, .tbox3{
    width: 70px;
    height: 40px;
    font-size: 10px;
  }

  .tbox1{
    margin-left: -240px;
  }
  .tbox2{
    margin-left: -160px;
  }
  .tbox3{
    margin-left: -80px;
  }

  .boxcon2{
    width: 100%;
  }

  .con2text {
    font-size: 13px;
    width:200px;
  }

  .icon-togle {
    margin-left: 10px;
    width: 40px;
    height: 25px;
  }
  
  .sendbox{
    display: flex;
    width:40%;
    margin-left: 240px;
  }
  .sendbtn1, .sendbtn2 {
    padding-left: 20px;
    font-size: 18px;
    height: 50px;
  }

  .sendbtn3 {
    width:100%;
    font-size: 20px;
    height: 50px;
  }

  .area {
    position: absolute;
    height: 2000px;
  }

  .scripttext{
    font-size: 12px;
  }

  .device {
    width:300px;
    height: 500px;
    margin-left:-30px;
    display: none;
    position: sticky;
  }

  .checkbtn{
    width: 46px;
    height: 46px;
    margin-left: 230px;
  }
  .checkdevice {
    width: 46px;
    height: 46px;
    background-color: #EAF8FF;
    border-bottom-right-radius: 22px;
    border-bottom-left-radius: 22px;
    transform: rotate(90deg);
  }

}

</style>
