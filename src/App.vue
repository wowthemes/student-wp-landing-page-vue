<template>
  <div id="app">
    <div class="site--hero_area">
      <main-header />
      <hero class="position-relative site--hero_content" />
    </div>
  </div>
</template>

<script>
require('bootstrap');
import MainHeader from './components/MainHeader.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    Hero
  }
}
</script>
<style lang="scss">
@import "assets/css/style.scss";

.site--hero_area {
  
  background: url(assets/images/bg-1.jpg) no-repeat scroll;
  background-size: cover;
  padding: 80px 0;
  color: #fff;
  position: relative;
  &::before {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #0f1c49;
    opacity: 0.9;
    top: 0;
    z-index: 0;
  }
  .site--hero_content {
    padding: 120px 0;
  }
  .btn--space_extra {
    padding: 20px 50px;
  }
}
</style>