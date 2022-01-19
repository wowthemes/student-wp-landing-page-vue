<template>
  <section class="section-padding" id="demos">
    <section-heading class="mb-5" tagline_place="after" :txt="false">
      <template slot="heading">3+ Pre-Made Home </template>
      <template slot="styled">demos</template>
    </section-heading>
    <div class="container">
      <div class="row">
        <div class="col-sm-4 text-center" v-for="home in homes" :key="home.title">
            <figure class="image">
              <a class="text-decoration-none hvr-grow" :href="home.url" target="_blank" title="home.title">
                <img :src="require(`../assets/${home.img}`)" :alt="home.title" />
              </a>
            </figure>
            <h4 class="title text-uppercase text-secondary">{{ home.title }}</h4>
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
          url: 'https://studentwp.wptech.co/',
          img: 'images/home-thumb-1.png',
          title: 'Home Page 1'
        },
        {
          url: 'https://studentwp.wptech.co/',
          img: 'images/home-thumb-2.png',
          title: 'Home Page 2'
        },
        {
          url: 'https://studentwp.wptech.co/',
          img: 'images/home-thumb-3.png',
          title: 'Home Page 3'
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  .image {
    margin-bottom: 1rem;
    padding: 1rem;

    img {
      border-radius: 1rem;
      box-shadow: 0 0 35px rgba(0, 0, 0, 0.2);
    }
  }    
  .title {
    font-size: 1.2rem;
    position: relative;
    z-index: 1;
  }
</style>