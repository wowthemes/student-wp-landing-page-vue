<template>
  <section class="section-padding" id="demos">
    <section-heading tagline_place="after" :txt="false" class="mb-4">
      <template slot="heading">3+ Pre-Made Home </template>
      <template slot="styled">demos</template>
    </section-heading>
    <div class="container">
      <div class="row justify-content-center mt-5">
        <div class="col-sm-6 col-lg-4 text-center" v-for="home in homes" :key="home.title">
          <a class="text-decoration-none hvr-grow reveal" :data-animate="home.animation" :href="home.url" target="_blank" :title="home.title">
            <img :src="require(`../assets/${home.img}`)" class="img mb-4" :alt="home.title" />
            <h4 class="font-neue-bold text-secondary">{{ home.title }}</h4>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>


<script>
import SectionHeading from './SectionHeading.vue'
export default {
  components: { SectionHeading },
  name: 'pre-made-homes',
  data() {
    return {
      homes: [
        {
          url: process.env.VUE_APP_HOME_ONE,
          img: 'images/home-1.png',
          title: 'Home Page 1',
          animation: 'animate__slideInDown',
        },
        {
          url: process.env.VUE_APP_HOME_TWO,
          img: 'images/home-2.png',
          title: 'Home Page 2',
          animation: 'animate__slideInUp',
        },
        {
          url: process.env.VUE_APP_HOME_THREE,
          img: 'images/home-3.png',
          title: 'Home Page 3',
          animation: 'animate__slideInDown',
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
.font-neue-bold {
  font-size: 20px;
}
.img {
  border-radius: 28px;
  box-shadow: 0 0 20px rgba(0,0,0,0.1);
}
</style>