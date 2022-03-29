<template>
  <div id="resume">
    <div class="basic">
      <div class="left">
        <p class="name">邱柏翰</p>
        <p class="content">
          <img
            class="img"
            src="https://www.svgrepo.com/show/349475/phone.svg"
          />0963808310
        </p>
        <p class="content">
          <img
            class="img"
            src="https://www.svgrepo.com/show/341847/github.svg"
          /><a href="https://github.com/bohan1109">bohan1109</a>
        </p>
        <p class="content">
          <img
            class="img"
            src="https://www.svgrepo.com/show/243092/gmail.svg"
          />qazwsx147866@gmail.com
        </p>
      </div>
      
        <img
          src="../assets/4A790162-2.jpg"
          alt=""
          class="mt-5"
          style="width:120px;height:150px;border:1px solid rgb(215, 215, 216)"
        />
      
    </div>
    <hr class="hr" />
    <div class="summary">
      <p class="title">簡歷 Summary</p>
      <p class="content">
        就讀於南台科技大學資訊管理系，目前在創科資訊股份有限公司培訓，培訓時常接觸到共同開發，以及技術分享，因此在培訓中我非常享受團隊互相合作、
        共同前進的感覺，並且可以在分享會中學到每個人分享的內容，培訓內容也非常廣，因此工作並不只侷限在單一的領域中，可以吸收更多不一樣的經驗，
        更是在培訓中找到對工作的熱情。
      </p>
    </div>
    <hr class="hr" />
    <div class="work_experience overflow-hidden">
      <p class="title">工作經驗 Professional Experience</p>
      <div class="flex justify-between items-center">
        <div class="">
          <p class="content_work">創科資訊股份有限公司培訓</p>
        </div>
        <div class="">
          <p class="content_time">2022/02-now</p>
        </div>
      </div>
      <p class="content">
        在大四下時，到創科資訊股份有限公司培訓進行培訓，在這邊學習許多技能，從設計、前端、後端、測試、部屬都有學到，對專案的流程及執行有了更進一步的了解，
        並且在實習時有許多實作機會，可以讓我們進行團隊專案的製作，在團隊專案製作中，除了學到許多沒用過的技術，像是react.js、git、laravel、虛擬環境等等，還學到了與團隊成員溝通的技巧，
        因為與不同的人分組合作，有同樣為資管系的台中科技大學的幾位、逢甲大學資工系的、雲科大資管系還有嘉義大學設計系的同學，養成了與不同的人合作時的溝通能力。
      </p>
    </div>

    <hr class="hr" />
    <div class="skill">
      <p class="title">專業技能 Skills & Certificates</p>
      <div class="skillgird">
        <div class="skilldiv">
          <img
            class="img"
            src="https://www.svgrepo.com/show/349402/html5.svg"
          />
          <p class="skilltitle">Html5</p>
          <hr />
          <li>Html</li>
          <li>Css</li>
        </div>
        <div class="skilldiv">
          <img
            class="img"
            src="https://www.svgrepo.com/show/349419/javascript.svg"
          />
          <p class="skilltitle">Javascript</p>
          <hr />
          <li>Javascript</li>
          <li>Vue.js</li>
          <li>Jquery</li>
          <li>Ajax</li>
        </div>
        <div class="skilldiv">
          <img
            class="img"
            src="https://www.svgrepo.com/show/374016/python.svg"
          />
          <p class="skilltitle">Python</p>
          <hr />
          <li>Python</li>
          <li>Flask</li>
        </div>
        <div class="skilldiv">
          <img class="img" src="https://www.svgrepo.com/show/354180/php.svg" />
          <p class="skilltitle">Php</p>
          <hr />
          <li>Php</li>
          <li>Laravel</li>
        </div>
        <div class="skilldiv">
          <img
            class="img"
            src="https://www.svgrepo.com/show/42243/database.svg"
          />
          <p class="skilltitle">Database</p>
          <hr />
          <li>Mysql</li>
          <li>Postgresql</li>
        </div>
        <div class="skilldiv">
          <img class="img" src="https://www.svgrepo.com/show/373623/git.svg" />
          <p class="skilltitle">Git</p>
          <hr />
          <li>Git</li>
          <li>Github</li>
        </div>
      </div>
    </div>
    <hr class="hr" />
    <div class="project">
      <p class="title">專案與作品集 Portfolio</p>
      <div class="projectdiv">
        <div class="basic">
          <div class="left">
            
            <p class="projectname">Monospace鎖櫃系統</p>
            <p class="projectcontent">
              公司新進鎖櫃，為了決定鎖櫃使用者，鎖櫃使用者需要輸入志願並抽籤，因此我們製作了個鎖櫃系統，此系統前端是使用了react.js後端使用了laravel，
              我負責的部分是後端api製作、前後端串接、heroku架設的部分。
            </p>
          </div>
          <div class="picture">
            <img
              src="../assets/monolock.png"
              alt=""
              class="pricture"
              
            />
          </div>
        </div>
        <div class="basic">
          <div class="left">
            <p class="projectname">即時溫溼度感測</p>
            <p class="projectcontent">
              這個專案是做溫溼度感測，並將資料即時存進資料庫，並將資料庫內容抓出來，將資料顯示在網頁上，讓觀測人員可以使用透過網頁的圖表，
              隨時知道現在的溫溼度如何，我負責的部分是mqtt broker的架設、python flask的api製作，包含資料庫連線、表格製作、新增、搜尋等功能。
            </p>
          </div>
          
            <img
              src="../assets/1028905.jpg"
              alt=""
              class="picture"
            />
          
        </div>
      </div>
    </div>
    <hr class="hr" />
    <div class="education">
      <p class="title">學歷 Education</p>
      <div class="flex justify-between items-center">
        <div class="">
          <p class="content_work">南台科技大學</p>
        </div>
        <div class="">
          <p class="content_time">2018/09-2022/06</p>
        </div>
      </div>
      <p class="content">資訊管理系</p>
    </div>
    <hr class="hr" />
    <div class="language">
      <p class="title">語言能力 Language</p>
      <p class="content">中文(母語)<br>英文(初學)</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="postcss" scoped>
div #resume {
  margin: 0 auto;
  width: 60vw;
  height: auto;
  margin-top: 20px;
  border: solid 1px rgb(215, 215, 216);
  @apply p-16 shadow-md;
}
.skilldiv hr {
  @apply my-2;
}
.projectdiv{
  @apply pl-5;
}

.img {
  width: 30px;
  height: 30px;
  float: left;
  @apply mr-3;
}
.hr {
  @apply leading-[1em] relative outline-0 border-0 text-center h-[1.5em] opacity-50;
}
.hr::before {
  @apply absolute w-full h-[3px] left-0 top-1/2 content-[''] bg-gradient-to-r from-transparent via-blue-400 to-transparent;
}
.title {
  @apply text-3xl mt-5 ml-3;
}
.content {
  @apply mx-8 mt-3;
}
.name {
  @apply text-3xl mt-5 ml-4;
}
.projectname {
  @apply text-2xl mt-4 ml-5 ;
}
.projectcontent {
  @apply mt-4 ml-7;
}
.content_work {
  @apply mx-7 mt-3 float-left font-extrabold;
}
.content_time {
  @apply mx-7 mt-3 float-right;
}
.skillgird {
  @apply grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-4 p-5 w-full;
}
.skilldiv {
  @apply w-full m-8;
}
.skilltitle {
  @apply text-lg font-bold;
}
.basic {
  @apply flex w-full justify-between;
}
.left{
  @apply w-8/12 relative flex-col break-all;
}
.picture{
  @apply w-40 h-40 pt-9 items-center;
}
.projectname::before{
  content:"";
  height: 1.5rem;
  width: 1.5rem;
  @apply rounded-full absolute -left-4 mt-1 z-10 border-0 bg-cyan-100;

}
.projectcontent::before{
  content:"";
  left: -6.5px;
  @apply rounded absolute mt-1 w-1 sm:h-4/5 md:h-4/5 xl:h-3/5 2xl:h-3/5 lg:h-3/5 z-10 border-0 bg-cyan-100;
}
</style>
