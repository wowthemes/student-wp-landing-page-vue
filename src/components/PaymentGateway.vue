<template>
  <div class="container-fluid px-0">
    <div class="payment-gateway-box">
      <div class="row mx-0">
        <div class="col-md-6 px-0">
          <div class="payment-gateway-col d-flex">
            <div class="payment-text">
              <div
                class="
                  section-heading
                  d-flex
                  justify-content-center
                  align-items-center
                "
              >
                <i class="icon-cap"></i>
                <div class="heading-text fw-bold">
                  <span class="text-light">STUDENT WORDPRESS THEME </span>
                </div>
              </div>
              <div class="headings text-center">
                <h5 class="head text-light fw-bold">20+ LEARNPRESS</h5>
                <h3 class="text-light fw-bold">PAYMENT GATEWAYS</h3>
              </div>
            </div>
            <div class="payment-gateway-image">
              <figure>
                <img src="../assets/images/icon/icon-payment-gateways.png" />
              </figure>
            </div>
          </div>
        </div>
        <div class="col-md-6 px-0">
          <div class="payment-gateway-col sec d-flex">
            <div class="payment-text">
              <div
                class="
                  section-heading
                  d-flex
                  justify-content-center
                  align-items-center
                "
              >
                <i class="icon-cap"></i>
                <div class="heading-text fw-bold">
                  <span class="text-light">STUDENT WORDPRESS THEME </span>
                </div>
              </div>

              <div class="text-light heading-text text-center">
                <h3 class="fw-bold">
                  ENHANCED THEME
                  <span class="pl-2 font-pristina fs-1 fw-bold">options</span>
                </h3>
              </div>
              <div class="text-area text-center">
                <p class="text-light fz-13">
                  Student WordPress theme is generally made for online
                  Learning<br />
                  Managment System.
                </p>
              </div>
            </div>
            <div class="payment-gateway-image lg">
              <figure>
                <img src="../assets/images/image-enhance-theme.png" />
              </figure>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "payment-gateway",
};
</script>

<style lang="scss" scoped>
.headings {
  font-family: sans-serif;
}
.fz-13 {
  font-size: 13px;
}
[class^="icon-"] {
  display: inline-block;
  line-height: 1;
  background-repeat: no-repeat;
  background-position: center;
  background-size: contain;
  vertical-align: middle;
}

.icon-cap {
  background-image: url("../assets/images/icon/icon-cap-white.png");
  height: 30px;
  width: 40px;
}

.heading-text {
  font-size: 9px;
  font-family: sans-serif;
}
.payment-gateway-col {
  background-color: #2a166f;
  flex-direction: column;
  align-items: center;
  height: 100%;
  padding-bottom: 160px;
  background-image: url("../assets/images/bg-clouds.png");
  background-position: bottom;
  background-repeat-x: repeat;
  background-repeat-y: no-repeat;
}
.sec {
  background-color: #4764fd;
  background-image: url(../assets/images/bg-pattern.png);
  background-repeat: repeat;
}
.payment-text {
  padding: 65px 20px 20px 20px;
}
.payment-gateway-image img {
  width: 200px;
}
.payment-gateway-img img {
  width: 680px;
}
.lg img {
  width: 400px !important;
}
figure {
  margin: 0;
}
@media (min-width: 768px) {
  .payment-gateway-col {
    padding-bottom: 90px;
  }
}
</style>