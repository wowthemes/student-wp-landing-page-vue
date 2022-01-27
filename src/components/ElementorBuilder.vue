<template>
  <section class="section-padding" id="demos">

    <div class="container">
      <div class="row">

        <div class="col-lg-6 col-md-12">
            <div class="ele-ico d-flex mt-5r">
              <div class="img-box">
                <a class="text-decoration-none">
                  <img  src="../assets/images/plugin-icon-elemt-builder.png">
                </a>
              </div>

              <div class="txt-area">
               <p class="text-dark mb-0 pb-1"> Elementor Drang-n-Drop</p>
               <h3 class="pl-2 colr-blue font-pristina fs-1 fw-bold">Visual Buiders</h3>
              </div>

            </div>

            <p class="text-dark pt-3 ">Get full course over the page using the bulided powerful builder. It Darg Editor allows you to creat without any line of code. </p>

            <div class="row pt-4 pb-4">
              <div class="col-lg-6">
                <h5>Elementor <br>Builder Webiste</h5>
                <p class="text-dark">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore, totam corporis quis quisquam ipsa</p>
              </div>

              <div class="col-lg-6 mt-sm-4 mt-lg-0">
                <h5>Live Responsive <br> Editing</h5>
                <p class="text-dark">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore, totam voluptas asperiores corporis quis quisquam ipsa</p>
              </div>  
            </div>
        
        </div>

        <div class="col-lg-6 col-md-12">
          <figure class="bulider-section">
                <img class="builder-img" src="../assets/images/image-builder-1.png">
          </figure>

        </div>

        </div>    
      </div>
  </section>
</template>


<script>

export default {
  name: 'elementor-builder'
}
</script>

<style lang="scss" scoped>
.font-neue-bold {
  font-size: 20px;
}
h5 {
  font-weight : 600;
}

.mtr {    
  transform: translate(55px, -65px);
}

.fnt-30 {
  font-size: 30px;

}

.bradius {
  border-radius : 10px;
}

.section-padding {
  padding-top: 50px !important;
  padding-bottom: 50px !important;
}


.builder-img {
  width:100%;
}

.bulider-section {
    margin: 0;
}

 .row {
    flex-direction: column-reverse;
  } 

@media (min-width:992px) {

  .row {
    flex-direction: row;
  
  }
  .mt-5r {
    margin-top: 5rem;
  }
}


</style>