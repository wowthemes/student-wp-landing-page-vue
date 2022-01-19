<template>
    <div class="overlay">
        <div class="footer-bg">

            <section class="section-padding">
                <div class="container">
                

                    <div class="row">
                        <div class="col-md-6 bg-light p-5  bradius shadow mt-fd">
                            <div class="section-heading d-flex align-items-center mb-2">
                                <i class="icon-cap"></i>
                                <div class="heading-text fw-bold">
                                    <span class="stu-clr">STUDENT</span><span class="wp-clr">WORDPRESS THEME </span>
                                </div>
                            </div> 

                            <div class="create-head">
                                <h3>Request A <span class="pl-2 colr-blue font-pristina fs-1 fw-bold">Demo</span>
                                </h3>
                            </div>

                            <div class="text-area">
                                <p class="text-dark">Student Wordpress theme is generllay made for Online Learnin Management System. </p>
                            </div>

                            <div class="testi-user-img">
                                <figure class="testi-img text-center">
                                    <img class="rounded-circle" src="../assets/images/image-contact.png">
                                </figure>
                            </div>

                        </div>
                    
                        <div class="col-md-6 bg-blue p-5 bradius ml-120 shadow mt-fd">
                            <div class="form-floating mb-3">
                                <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                                <label for="floatingInput">Full Name</label>
                            </div>
                            <div class="form-floating mb-3">
                                <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                                <label for="floatingInput">E-mail Address</label>
                            </div>
                            <div class="form-floating mb-3">
                                <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                                <label for="floatingInput">Phone Number</label>
                            </div>
                            <div class="form-floating">
                                <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
                                <label for="floatingTextarea2">Message</label>
                            </div>
                            <div class="submit-form-btn form-btn pt-4">
                            <button class="btn btn-warning form-btn rounded-pill" type="submit">CONTACT US NOW</button>
                            </div>
                        
                        </div>
                    </div> 

                    <div class="footer-block text-center pt-100">
                        <div class="footer-logo"> 
                            <figure class="ftr-logo">
                                <img  class="" src="../assets/images/logo-footer.png" alt="footer-logo">
                            </figure>
                        </div>
                        <div class="footer-txt">
                            <h3 class="">Discover the whole world of new<br> Possibilities with
                            <span class="pl-2 colr-blue font-pristina fs-1 fw-bold">Student</span></h3>
                        </div>
                        <div class="submit-form-btn pt-4">
                        <button class="btn bg-blue text-light form-btn rounded-pill fnt-14" type="submit">BUY THIS THEME IN $59 </button>
                        </div>

                    </div>

                </div>
            </section>

        </div>

    </div>    

</template>


<script>
export default {
  name: 'footer-section'
}
</script>

<style lang="scss" scoped>

    .icon-cap {
      background-image: url("../assets/images/icon/icon-cap.png");
      height: 20px;
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

.font-neue-bold {
  font-size: 20px;
}

.footer-bg {
    background-image: url("../assets/images/image-footer-bg.png");
    background-size:cover;
    position: relative;
    z-index: 1;

}

.footer-bg::before {
    content: "";
    color: #fff;
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #0f1c49;
    opacity: 0.9;
    top: 0;
    z-index: -1;
}
.bradius {
  border-radius : 40px;
}

.mb-md-5m {
    margin-bottom:2em;
}

.mt-fd {
        margin-top: 0;
    }

.pr-50 {
    padding-right : 50px !important;
}

.bg-blue {
    background-color:#6588fc;
}

.form-btn  {
    padding:15px 40px;
    font-weight:600;
}

.form-floating {
    color:#fff;
}

.form-control {
    background-color : transparent;
    border:none;
    border-radius: 0;
    border-bottom: 1px solid #fff;
}


.pt-100{
    padding-top:100px;
}

.ml-120 {
    margin-left: 0;
    position: relative;
    z-index: 1;  
}

.ml-120::before {
    content: '';
    position: absolute;
    top: -30px;
    bottom: -30px;
    left: 0;
    right: 0;
    background-color: #6588fc;
    border-radius: 40px;
    z-index: -1;
}

textarea:focus , input:focus {
    background:transparent;
}

.footer-txt h3 {
    color: #fff;
    font-size: 37px;
    font-weight: 600;
}

.fnt-14 {
        font-size:14px;
        font-weight:500;
    }
    
.play-btn-cls {
    margin: 0;
    margin-top: -100%;
}


.create-head h3 {
    font-family: sans-serif;
    color: #0e1951;
    font-size: 37px;
    font-weight: 800;
}

.form-btn {
    text-align: center;
}


@media (min-width:768px){

    .mt-fd {
        margin-top: -315px;
    }
    
    .ml-120 {
        margin-left: -43px;
    }


    .mb-md-5m {
        margin-bottom:5em !important;
    }

    
    .form-btn {
        text-align: start;
    }
}

</style>    