<template>
  <div class="container">
    <div class="row reverse">
      <div class="col-sm-12 col-lg-4 text-center d-flex align-items-center">
        <div class="w-100">
          <h2 class="text-white fw-bold lh-lg">The best Premium <br>Education</h2>
          <h2 class="text-white font-pristina mb-3">WordPress theme of 2022</h2>

          <a :href="demourl" target="_blank" class="btn btn-primary mt-5 rounded-pill btn--space_extra text-uppercase fw-bold text-white hvr-grow">View Live demo</a><br>
          <a :href="buyurl" target="_blank" class="btn btn-warning mt-4 rounded-pill btn--space_extra text-uppercase fw-bold hvr-grow">Buy this theme</a>
        </div>
      </div>
      <div class="col-lg-8 col-sm-12 position-relative">
        <img src="../assets/images/hero-img-1.png" alt="" />
        <img src="../assets/images/hero-img-2.png" class="hero--img_2 animate__animated animate__slideInUp d-none d-lg-block" alt="" />
        <img src="../assets/images/hero-img-3.png" class="hero--img_3 animate__animated animate__slideInRight d-none d-lg-block" alt="" />
        <img src="../assets/images/elementor.png" class="hero--elementor d-none d-lg-block" alt="" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      buyurl: process.env.VUE_APP_BUYURL,
      demourl: process.env.VUE_APP_HOME_ONE,
    }
  },
  mounted() {

  }
}
</script>
<style lang="scss" scoped>
.site--hero_content {
  .hero--img_2 {
    position: absolute;
    left: 5%;
    bottom: -10%;
  }
  .hero--img_3 {
    position: absolute;
    right: 0;
    top: 10%;
  }
  .hero--elementor {
    position: absolute;
    bottom: -7%;
    right: 25%;
  }
}

.reverse {
    flex-direction: column-reverse;

  }
@media (min-width:992px) {
  .reverse {
    flex-direction: row;
  }
}
</style>