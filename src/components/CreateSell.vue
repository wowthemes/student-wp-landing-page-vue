<template>

    <div class="create-sell-background-image">
      
    <section class="section-padding" id="demos">

      <div class="container">
        <div class="theme-box mb-100">
            <div class="row">
                <div class="col-lg-9 col-md-12">
                    <div class="theme-content d-flex justify-content-center">
                        <div class="theme-logo align-self-center">
                            <i class="icon-cap"></i>
                        </div>
                        <div class="theme-heading">
                            <div class="buy-text text-light text-center">
                                <h3 class="fw-bold">Ultimate Theme for online <span class="pl-2 text-light font-pristina fs-4 fw-normal">Courses <span class="fw-bolder"> & </span>  Education</span>
                                </h3>
                            </div>
                            <div class="para-box text-center">
                                <p class="text-light">Your site can be built in less than you can expect!!.</p>
                            </div>
                        </div>
                    </div>
                </div>  
                <div class="col-lg-3 col-md-12 align-self-center">
                    <div class="d-flex buy-theme-btn">
                        <a :href="buy" target="_blank" class="btn btn-warning fw-bold rounded-pill buy-theme text-black">BUY THIS THEME</a>
                    </div>
                </div>          
            </div>
        </div>
      </div>

        <div class="section-heading d-flex justify-content-center align-items-center mb-2">
          <i class="icon-cap"></i>
          <div class="heading-text fw-bold">
            <span class="text-light">STUDENT WORDPRESS THEME </span>
          </div>
        </div>
      
        <div class="create-head text-center">
          <h3>CREATE & SELL ONLINE <span class="pl-2 colr-blue font-pristina fs-1 fw-bold">Courses</span>
          </h3>
        </div>
        <div class="txt-area text-center">
          <p class="text-white">Student WordPress theme is generally made for online Learning Management System.</p>
        </div>

        <div class="container mt-5">
          <div class="create-sell-image">
                <figure>
                    <img src="../assets/images/sell-online.png" alt="img">
                </figure>
            </div>
        </div>
    </section>

    </div>

</template>


<script>
export default {
  name: 'create-sell',
  data() {
    return {
      buy: process.env.VUE_APP_BUYURL_2,
    }
  }
}
</script>

<style lang="scss" scoped>


    [class^=icon-] {
      display: inline-block;
      line-height: 1;
      background-repeat: no-repeat;
      background-position: center;
      background-size: contain;
      vertical-align: middle;
    }

    .icon-cap {
      background-image: url("../assets/images/icon/icon-cap.png");
      width: 42px;
      height: 21px;
      margin-right: 5px;
    }

    .heading-text {
      font-size: 12px;
      font-family: sans-serif;
    }

    figure {
    margin: 0;
    }

    .create-sell-background-image {
    background-image: url("../assets/images/bg-image-1.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    }

    .create-sell-image img {
      width: 100%;
    }

  .section-padding {
    padding-top: 100px !important;
    padding-bottom: 100px !important;
  }

  .create-head h3 {
    font-family: sans-serif;
    color: #fff;
    font-size: 37px;
    font-weight: 600;
}

.theme-box {
    background: linear-gradient(to right, #4764fd, #83acfc);
    padding: 35px 10px;
    border-radius: 20px;
}

.buy-text h3, p {
    margin: 0;
}

.mb-100{
      margin-bottom: 50px;
    }


    .buy-theme-btn {
      justify-content:center;
      margin-top: 20px;
    }



@media (min-width:992px){

    .theme-box {
      margin-top: -170px;
    }

    .mb-100{
      margin-bottom: 100px;
    }


    .buy-theme-btn {
      justify-content:start;
      margin-top: 0;
    }

}


</style>