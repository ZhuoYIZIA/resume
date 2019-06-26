<template>
  <div class="skill">
      <h1>
        <i class="fas fa-code"></i>
        SKILL
      </h1>

      <h4>front end</h4>
      <div class="skill__frontEnd">
        <img src="@/assets/logo/HTML_Logo.png" alt="html logo">
        <img src="@/assets/logo/scss-logo.svg" alt="scss logo">
        <img src="@/assets/logo/js-logo.svg" alt="javascript logo">
        <img src="@/assets/logo/vuejs-logo.png" alt="VueJs logo">
      </div>

      <h4>back end</h4>
      <div class="skill__backEnd">
        <img src="@/assets/logo/php7-logo.png" alt="php logo">
        <img src="@/assets/logo/laravel-logo.png" alt="laravel logo">
        <img src="@/assets/logo/mysql-logo.png" alt="mysql logo">
      </div>

      <h4>web</h4>
      <div class="skill__else">
        <img src="@/assets/logo/github-logo.svg" alt="github logo">
        <img src="@/assets/logo/stackoverflow-logo.png" alt="github logo">
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
  @import '../scss/page/skill';

</style>
