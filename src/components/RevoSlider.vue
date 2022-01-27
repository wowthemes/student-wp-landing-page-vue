<template>
  <section class="section-padding">

    <div class="container">
      <div class="row">

      

        <div class="col-lg-6 col-md-12">

            <figure class="bulider-section">
                <img class="builder-img" src="../assets/images/image-builder-2.png">
            </figure>
        </div>

          <div class="col-lg-6 col-md-12">

              <div class="txt-area mt-5r">
               <p class="text-dark mb-0 pb-1"> Elementor Drang-n-Drop</p>
               <h3 class="pl-2 colr-blue font-pristina fs-1 fw-bold">Revolution Slider</h3>
              </div>

            <p class="text-dark">Get full course over the page using the bulided powerful builder. It Darg Editor allows you to creat without any line of code. </p>

            <div class="row pt-4 pb-4">
              <div class="col-lg-6">
                <h5>Retina ready  <br>mobile optimize</h5>
                <p class="text-dark">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore, totam corporis quis quisquam ipsa</p>
              </div>

              <div class="col-lg-6 mt-sm-4 mt-lg-0">
                <h5>Optimize wordpress<br> speed</h5>
                <p class="text-dark">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore, totam voluptas asperiores corporis quis quisquam ipsa</p>
              </div>  
            </div>
        
        </div>

        </div>    
      </div>
  </section>
</template>


<script>
export default {
  name: 'revo-slider'
}
</script>

<style lang="scss" scoped>
.font-neue-bold {
  font-size: 20px;
}

h5 {
  font-weight : 600;
}

.mtl {    
  transform: translate(220px, -65px);
}

.fnt-30 {
  font-size: 30px;

}

.bradius {
  border-radius : 10px;
}

.bulider-section {
    margin: 0;
}

.builder-img {
  width:100%;
}

.section-padding {
  padding-top:0px !important;
  padding-bottom:0px !important;
}


@media (min-width:768px) {
  
  .mt-5r {
    margin-top: 5rem;
  }

  .section-padding {
    padding-top:50px !important;
    padding-bottom:50px !important;
}
}

</style>