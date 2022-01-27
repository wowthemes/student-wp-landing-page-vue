<template>
  <section class="section-padding" id="demos">
    <section-heading tagline_place="after" :txt="false">
      <template slot="heading">3+ Pre-Made Home </template>
      <template slot="styled">demos</template>
    </section-heading>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-sm-6 col-lg-4 text-center" v-for="home in homes" :key="home.title">
          <a class="text-decoration-none hvr-grow" :href="home.url" target="_blank" title="home.title">
            <img :src="require(`../assets/${home.img}`)" :alt="home.title" />
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
          img: 'images/home-1.jpg',
          title: 'Home Page 1'
        },
        {
          url: process.env.VUE_APP_HOME_TWO,
          img: 'images/home-2.jpg',
          title: 'Home Page 2'
        },
        {
          url: process.env.VUE_APP_HOME_THREE,
          img: 'images/home-3.jpg',
          title: 'Home Page 3'
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
</style>