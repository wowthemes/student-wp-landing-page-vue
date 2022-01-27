<template>

  <section class="section-padding" id="demos">
  
    <section-heading tagline_place="before" :txt="true">
      <template slot="heading">What You Get </template>
      <template slot="styled">for $59</template>
    </section-heading>
      <div class="txt-area">
          <p class="text-dark text-center">Student WordPress theme is generally made for online Learning Management System.</p>
      </div>

    <div class="container mt-5">
        <div class="gx-5 gx-md-0">

            <div class="row">
                <div class="col-lg-4 col-md-6 my-md-4 my-4">
                    <div class="what-you-get-main d-flex align-items-center mb-4">
                        <div class="what-you-get-img">
                            <figure>
                                <img src="../assets/images/plugin-icon-rev-slider.png" alt="img">
                            </figure>
                        </div>
                        <div class="what-you-get-text ps-2">
                            <span class="d-block text-primary">Page Builder</span>
                            <h4>Slider Revolution</h4>
                        </div>
                    </div>
                </div>    

                <div class="col-lg-4 col-md-6 my-md-4 my-4">

                    <div class="what-you-get-main d-flex align-items-center mb-4">
                        <div class="what-you-get-img">
                            <figure>
                                <img src="../assets/images/plugin-icon-elemt-builder.png" alt="img">
                            </figure>
                        </div>
                        <div class="what-you-get-text ps-2">
                            <span class="d-block text-primary">Page Builder</span>
                            <h4>Elementer Builder</h4>
                        </div>
                    </div>
                </div>    

                <div class="col-lg-4 col-md-6 my-md-4 my-4">

                    <div class="what-you-get-main d-flex align-items-center mb-4">
                        <div class="what-you-get-img">
                            <figure>
                                <img src="../assets/images/plugin-icon-wp-form.png" alt="img">
                            </figure>
                        </div>
                        <div class="what-you-get-text ps-2">
                            <span class="d-block text-primary">Manage Forms</span>
                            <h4>WP Forms</h4>
                        </div>
                    </div>
                </div>    
                    

                    
            
                <div class="col-lg-4 col-md-6 my-md-4 my-4">

                    <div class="what-you-get-main d-flex align-items-center mb-4">
                        <div class="what-you-get-img">
                            <figure>
                                <img src="../assets/images/plugin-icon-woo.png" alt="img">
                            </figure>
                        </div>
                        <div class="what-you-get-text ps-2">
                            <span class="d-block text-primary">Manage Shop</span>
                            <h4>WooCommerce</h4>
                        </div>
                    </div>
                </div>    
                <div class="col-lg-4 col-md-6 my-md-4 my-4">
                    
                    <div class="what-you-get-main d-flex align-items-center mb-4">
                        <div class="what-you-get-img">
                            <figure>
                                <img src="../assets/images/plugin-icon-lp.png" alt="img">
                            </figure>
                        </div>
                        <div class="what-you-get-text ps-2">
                            <span class="d-block text-primary">Page Builder</span>
                            <h4>LearnPress</h4>
                        </div>
                    </div>
                </div>    
                <div class="col-lg-4 col-md-6 my-md-4 my-4">

                    <div class="what-you-get-main d-flex align-items-center mb-4">
                        <div class="what-you-get-img">
                            <figure>
                                <img src="../assets/images/plugin-icon-wpml.png" alt="img">
                            </figure>
                        </div>
                        <div class="what-you-get-text ps-2">
                            <span class="d-block text-primary">Multilingual Plugin</span>
                            <h4>WPML</h4>
                        </div>
                    </div>
                </div>    

            </div>
            
        </div>
                
    </div>

  </section>

</template>


<script>
import SectionHeading from './SectionHeading.vue'
export default {
  components: { SectionHeading },
  name: 'when-you-get',
    
}
</script>

<style lang="scss" scoped>
    figure {
        margin: 0;
    } 
    .what-you-get-main {
        padding: 25px;
        box-shadow: 0 0 35px rgb(0 0 0 / 20%);
        border-radius: 25px;
        height: 100%;
    }

    .section-padding {
        padding-top:50px;
        padding-bottom:50px !important ;
    }



    @media (min-width:768px) {
        .section-padding {
            padding-top:100px !important ;
    }
}

</style>