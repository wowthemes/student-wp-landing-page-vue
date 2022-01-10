<template>
  <div class="container">
    <div class="row">
      <div class="col-sm-4 text-center d-flex align-items-center">
        <div class="w-100">
          <h2 class="text-white fw-bold lh-lg">The best Premium <br>Education</h2>
          <h2 class="text-white font-pristina mb-3">WordPress theme of 2022</h2>

          <a class="btn btn-primary mt-5 rounded-pill btn--space_extra text-uppercase fw-bold text-white">View Live demo</a><br>
          <a class="btn btn-warning mt-4 rounded-pill btn--space_extra text-uppercase fw-bold">Buy this theme</a>
        </div>
      </div>
      <div class="col-sm-8 position-relative">
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