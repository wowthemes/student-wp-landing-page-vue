<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-5 text-center">
        <h2 class="text-white">The premium education</h2>
        <h2 class="text-white">WordPress theme of 2022</h2>

        <a class="btn btn-primary mt-4 rounded-pill btn--space_extra">View Live demo</a><br>
        <a class="btn btn-secondary mt-4 rounded-pill btn--space_extra">Buy this theme</a>
      </div>
      <div class="col-sm-7 position-relative">
        <img src="../assets/images/hero-img-1.png" alt="" />
        <img src="../assets/images/hero-img-2.png" class="hero--img_2 animate__animated animate__slideInUp" alt="" />
        <img src="../assets/images/hero-img-3.png" class="hero--img_3 animate__animated animate__slideInRight" alt="" />
        <img src="../assets/images/elementor.png" class="hero--elementor" alt="" />
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.site--hero_content {
  overflow: hidden;
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
</style>