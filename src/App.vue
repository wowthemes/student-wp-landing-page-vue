<template>
  <div id="app">
    <div class="site--hero_area">
      <main-header />
      <hero class="position-relative site--hero_content" />
    </div>
    <what-else />
    <pre-made-homes />
    <!-- <buy-themes /> -->
    <create-sell />
    <one-click />
    <what-you-get />
    <student-useful />
    <payment-gateway />
    <elementor-builder />
    <revo-slider />
    <student-useful-inner-pages />
    <testi-monals />
    <footer-section />




  </div>
</template>

<script>
require('bootstrap');
import MainHeader from './components/MainHeader.vue'
import Hero from './components/Hero.vue'
import WhatElse from './components/WhatElse.vue';
import PreMadeHomes from './components/PreMadeHomes.vue';
import ElementorBuilder from './components/ElementorBuilder.vue';
import RevoSlider from './components/RevoSlider.vue';
import TestiMonals from './components/TestiMonals.vue';
import FooterSection from './components/FooterSection.vue';
import CreateSell from './components/CreateSell.vue';
import WhatYouGet from './components/WhatYouGet.vue';
import StudentUsefulInnerPages from './components/StudentUsefulInnerPages.vue';
import StudentUseful from './components/StudentUseful.vue';
import PaymentGateway from './components/PaymentGateway.vue';
import OneClick from './components/OneClick.vue';
// import BuyThemes from './components/BuyThemes.vue';












export default {
  name: 'App',
  components: {
    MainHeader,
    Hero,
    WhatElse,
    PreMadeHomes,
    ElementorBuilder,
    RevoSlider,
    TestiMonals,
    FooterSection,
    CreateSell,
    WhatYouGet,
    StudentUsefulInnerPages,
    StudentUseful,
    PaymentGateway,
    OneClick,
    // BuyThemes
  }
}
</script>
<style lang="scss">
@import "assets/css/style.scss";
#app {
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
      padding: 20px 65px;
    }
  }
}
</style>