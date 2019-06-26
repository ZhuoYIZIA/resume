<template>
  <!-- 
        2017 7-9 馬來西亞 濱城 sunshine 實習
        2017 10 - 2018 12 產學合作 後端開發 php laravel mysql
        2019 1 - 6 實習 全端開發 Vue.js Laravel
        2019 6/15 亞東技術學院畢業 
     -->
  <div class="resume">
    <h1>
      <i class="far fa-address-card"></i>
      RESUME
    </h1>

    <div class="resume__content">
      <!-- asdf -->
      <div class="resume__content--item">
        <div>
          <span>2019 June</span>
          <h3>亞東技術學院 畢業</h3>
          <span>資訊管理係</span>
        </div>
        <p>
          涉略 Python , R , Java , C# , Linux , Photoshop , 系統分析 , 專案管理。
        </p>
      </div>
      <div class="resume__content--item">
        <div>
          <span>2019 Jan - June</span>
          <h3>馬跡庫比有限公司</h3>
          <span>實習生</span>
        </div>
        <p>
          擔任全端，內容為開發媒合平台網站，網站顧客群主要為旅遊業。
          開發工具使用Vue與Laravel，資料庫使用MySQL。
        </p>
      </div>
      <div class="resume__content--item">
        <div>
          <span>2017 Oct - 2018 Dec</span>
          <h3>校內專題</h3>
          <span>產學合作</span>
        </div>
        <p>
          與馬跡庫比有限公司合作開發網站，專題名稱為旅遊媒婆，擔任後端，使用語言為PHP，
          框架使用Laravel，資料庫使用MySQL。得到校內第一。
        </p>
      </div>
      <div class="resume__content--item">
        <div>
          <span>2017 Jul - Sep</span>
          <h3>馬來西亞 檳城 Sunshine公司</h3>
          <span>實習生</span>
        </div>
        <p>
            因技術不成熟，主要目的為語言學習以及文化體驗。
        </p>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {

      }
    }
  }

</script>

<style lang="scss" scoped>
  @import '../scss/page/resume';

</style>
