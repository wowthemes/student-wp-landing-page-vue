<template>

    <div class="student-useful-background-image">
    
    <section class="section-padding" id="demos">
        <section-heading tagline_place="before" :txt="true">
        <template slot="heading">STUDENT USEFUL </template>
        <template slot="styled">Inner Pages</template>
        </section-heading>

            <p class="text-center text-dark">Student WordPress theme is generally made for online Learning Management System.</p>
            <div class="background-images mt-4">
                <figure>
                    <img src="../assets/images/pages-carousel.png" alt="backgroung-image">
                </figure>
            </div>
    </section>

    </div>

</template>


<script>
import SectionHeading from './SectionHeading.vue'
export default {
  components: { SectionHeading },
  name: 'student-useful-inner-pages',
    
}
</script>

<style lang="scss" scoped>

figure {
    margin: 0;
}

.background-images img {
    width: 100%;
}

.section-padding {
    padding-top:50px !important;
} 

@media (min-width:768px){
   .section-padding {
        padding-bottom:350px !important;
    } 
}

</style>