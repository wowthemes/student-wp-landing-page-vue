<template>
    <div class="bg-pattren">

        <div class="container">

            <section class="section-padding">
                <div class="video-block text-center">
                    <div class="video-block-image">
                        <figure class="video-sec mb-md-5m">
                            <img class="bradius" src="../assets/images/video-cover.png">
                        </figure>
                    
                        <a href="https://www.youtube.com/watch?v=668nUCeBHyY" target="blank">
                            <i class="icon-play-btn"></i>

                        </a>
                    </div>
                    
                </div>
                
                <section-heading tagline_place="before" :txt="false">
                    <template slot="heading">REVIEW FOR </template>
                    <template slot="styled">Students</template>
                </section-heading>    

                <div class="text-area">
                    <p class="text-dark text-center">Student Wordpress theme is generllay made for Online Learnin Management System. </p>
                </div>

                <div class="container mt-5">
                    <div class="row">
                    <div class="col-md-4 my-md-0 my-4">
                        <div class="user-img-post">

                            <div class="testimonal-area text-center bg-white bradius p-3 p-lg-4 pt-0 pt-lg-0 pb-lg-5">
                                <div class="testi-user-img">
                                    <figure class="testi-img shadow-sm">
                                        <img class="" src="../assets/images/snap-1.png">
                                    </figure>
                                </div>
                                <div class="txt-block">
                                    <p class="text-dark">very useful and up to date You can use very useful and up to date You can use </p>

                                    <div class="user-info d-flex justify-content-center align-items-center">
                                        <div class="icon">
                                            <i class="icon-quotes"></i>
                                        </div>
                                        <div class="user-name-rank ms-3">
                                            <div class="name">
                                                <h4 class="user-name">asimd2</h4>
                                            </div>
                                            <div class="ranking d-flex" >
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                            </div>
    
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>                    
                    </div>
                    
                    <div class="col-md-4 my-md-0 my-4">
                        <div class="user-img-post">

                            <div class="testimonal-area text-center bg-white bradius p-3 p-lg-4 pt-0 pt-lg-0 pb-lg-5">
                                <div class="testi-user-img">

                                    <figure class="testi-img shadow-sm">
                                        <img class="" src="../assets/images/snap-1.png">
                                    </figure>
                                </div>    

                                <div class="txt-block">
                                            <p class="text-dark">very useful  use very useful and  use very useful andand up to date You can use very useful and up to date You can use  use very use very useful and useful and very useful  use very useful and  use very useful andand up to date You can use very useful and up to date  </p>

                                    <div class="user-info d-flex justify-content-center align-items-center">
                                        <div class="icon">
                                            <i class="icon-quotes"></i>
                                        </div>
                                        <div class="user-name-rank ms-3">
                                            <div class="name">
                                                <h4 class="user-name">danish_tariq</h4>
                                            </div>
                                            <div class="ranking d-flex" >
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                            </div>
    
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>                    
                    </div>

                   <div class="col-md-4 my-md-0 my-4">
                        <div class="user-img-post">

                            <div class="testimonal-area text-center bg-white bradius p-3 p-lg-4 pt-0 pt-lg-0 pb-lg-5">
                                <div class="testi-user-img">

                                    <figure class="testi-img shadow-sm">
                                        <img class="" src="../assets/images/snap-1.png">
                                    </figure>
                                </div>    

                                <div class="txt-block">
                                            <p class="text-dark">very useful  use very useful and  use very useful andand up to date You can use very useful and up to date You</p>

                                    <div class="user-info d-flex justify-content-center align-items-center">
                                        <div class="icon">
                                            <i class="icon-quotes"></i>
                                        </div>
                                        <div class="user-name-rank ms-3">
                                            <div class="name">
                                                <h4 class="user-name">asimd2</h4>
                                            </div>
                                            <div class="ranking d-flex" >
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                                <i class="icon-star"></i>
                                            </div>
    
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>                    
                    </div>


                    </div>   
                  <div>  
                </div>
                </div>
            </section>
        </div>

    </div>    

</template>


<script>
import SectionHeading from './SectionHeading.vue'
export default {
  components: { SectionHeading },
  name: 'testi-monals'
}
</script>

<style lang="scss" scoped>
.font-neue-bold {
  font-size: 20px;
}

.bg-pattren {
    background-image: url("../assets/images/bg-pattern.png");
    background-color: #f8f7ff;
}

.bradius {
  border-radius : 10px;
}


.bradius {
  border-radius : 40px;
}

.user-img-post .testimonal-area {
    height: 100%;
}

.user-img-post {
    height: 100%;
}

figure.video-sec {
    margin-top: 0;
}

.mb-md-5m {
    margin-bottom:2em;
}

.icon-play-btn{
    margin:0;
    margin-top: -75%;
}

.icon-play-btn {
    background-image: url("../assets/images/icon/icon-play.png");
    width: 58px;
    height: 40px;
}

.testi-user-img {
    margin: 0;
    display: inline-block;
    margin-top: -44px;
    border-radius: 50%;
    padding: 10px;
    width: 100px;
    height: 100px;
    background-color: #fff;
    position: relative;
}

.testi-user-img::before, .testi-user-img::after {
    content: '';
    width: 0;
    height: 0;
    border-left: 17px solid transparent;
    border-right: 17px solid transparent;
    border-top: 19px solid rgba(0,0,0,0.03);
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateY(100%) translateX(-50%);
    margin-bottom: 39px;
}

.testi-user-img::after {
    border-top: 17px solid #fff;
    border-left-width: 15px;
    border-right-width: 15px;
    bottom: 3px;
}

.testi-img {
    margin: 0;
    display: inline-block;
    margin-top: -44px;
    border-radius: 50%;
    border: 10px solid #fff;
    max-width: 80px;
}

[class^="icon-"] {
    display: inline-block;
    line-height: 1;
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    vertical-align: middle;
}

.icon-star {
    background-image: url("../assets/images/icon/icon-star.png");
    width: 15px;
    height: 15px;
}

.icon-quotes {
    width: 58px;
    height: 40px;
    background-image: url("../assets/images/icon/icon-quote.png");
}


h4.user-name {
    margin: 0;
}

.txt-block {
    line-height: 1.5;
}


@media (min-width:768px){

    figure.video-sec {
        margin-top: -370px;
    }
    
    .section-padding {
        padding-bottom:350px !important;
    }

    .mb-md-5m {
        margin-bottom:5em !important;
    }

}

</style>