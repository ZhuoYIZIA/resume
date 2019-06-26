<template>
  <div class="layOut">
    <nav class="sidebar">
      <img class="sidebar__img" src="@/assets/avatar.jpg" alt="avatar">
      <h2 class="sidebar__tittle">卓奕嘉</h2>
      <ul>
        <li class="sidebar--li">HOME</li>
        <li class="sidebar--li">ABOUT ME</li>
        <li class="sidebar--li">SKILL</li>
        <li class="sidebar--li">RESUME</li>
        <li class="sidebar--li">PORTFOILO</li>
        <li class="sidebar--li">CONTACT</li>
        <li>
          <i class="far fa-copyright"></i> 2019 Rondo_lin All Rights Reserved
        </li>
      </ul>
    </nav>
    <div class="body">
      <layoutHome />
      <about />
      <skill />
      <resume />
      <portfoilo />
      <contact />
    </div>

  </div>

</template>

<script>
  import layoutHome from '@/components/layoutHome.vue';
  import about from '@/components/about.vue';
  import skill from '@/components/skill.vue';
  import resume from '@/components/resume.vue';
  import portfoilo from '@/components/portfoilo.vue';
  import contact from '@/components/contact.vue';

  export default {
    data() {
      return {}
    },
    methods: {},
    components: {
      layoutHome,
      about,
      skill,
      resume,
      portfoilo,
      contact,
    },
  }

</script>

<style lang="scss" scoped>
  @import '../scss/page/layOut';

</style>
