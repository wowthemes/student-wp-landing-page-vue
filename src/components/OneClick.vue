<template>
    <div class="container">
        <div class="one-click-box">
            <div class="row">
                <div class="col-md-8 mb-4 mb-md-0">
                    <div class="one-click-image">
                        <figure>
                            <img src="../assets/images/one-click-demo2.png" alt="">
                        </figure>
                    </div>
                </div>  
                <div class="col-md-4 mb-4 mb-md-0 mt-md-5">
                    <div class="one-click-col">
                       <div class="section-heading d-flex align-items-center">
                            <i class="icon-cap"></i>
                            <div class="heading-text fw-bold">
                              <span class="stu-clr">STUDENT</span>  <span class="wp-clr">WORDPRESS THEME </span> 
                            </div>
                        </div>

                        <div class="heading-txt">
                            <h2 class="fw-bold">One Click Demo <span class="pl-2 colr-blue font-pristina fs-1 fw-bold">Import</span>
                            </h2>
                        </div>
                        <div class="text-area mb-5">
                            <p class="text-dark">The best feature of this plugin is, that theme authors can define import files in their themes and so all you (the user of the theme) have to do is click on the "Import Demo Data" button.</p>
                        </div>
                        <div class="d-flex ocd-btn">
                            <a href="#" class="btn btn-warning rounded-pill text-black">BUY THIS THEME</a>
                        </div>
                    </div>
                </div>          
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'one-click',
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
      height: 30px;
      width: 40px;
    }

.heading-text {
      font-size: 12px;
      font-family: sans-serif;
    }

.wp-clr {
    color: #6588fc;
}

.stu-clr {
    color: #0e1951;
}

.colr-dark-blue {
    color: #fff !important;
}
.one-click-box {
    padding-top: 60px;
}

.heading-txt  h2{
    color: #0e1951;
    width: 100%;
    text-align: center;
}

.ocd-btn {
    justify-content: center;
}

.section-heading  {
    justify-content: center;
}

@media(min-width:768px){


    .section-heading  {
        justify-content: start;
    }
    .ocd-btn {
        justify-content: start;
    }

    .mt-md-5 {
       margin-top: 5rem !important; 
    }

    .heading-txt  h2{
        color: #0e1951;
        width: 60%;
        text-align: start;
    }
}
</style>