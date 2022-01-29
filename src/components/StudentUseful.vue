<template>
  <div class="student-useful-background-image" id="features">
    <section class="section-padding" id="demos">
      <section-heading tagline_place="before" :txt="true">
        <template slot="heading">STUDENT USEFUL </template>
        <template slot="styled">Features</template>
      </section-heading>
      <div class="txt-area text-center">
        <p class="text-dark">
          Student WordPress theme is generally made for online Learning
          Management System.
        </p>
      </div>
      <div class="container mt-4">
        <div class="gx-5 gx-md-0">
          <div class="row justify-content-center">
            <div class="col-lg-4 col-md-6 my-md-4 my-4" v-for="feature in features" :key="feature.title">
              <div :class="['student-useful-col-main text-center mb-4 reveal', feature.active && 'student-bg-styled']" :data-animate="feature.animation">
                <div class="student-useful-icon">
                  <i class="icon-icon-1" :style="{backgroundImage: `url(${getIcon(feature.icon)})`}"></i>
                </div>
                <div :class="['student-useful-heading', feature.active && 'text-white']">
                  <h3 v-html="feature.title"></h3>
                </div>
                <div class="student-useful paragraph">
                  <p :class="[feature.active && 'text-white']" v-html="feature.text"></p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>


<script>
import SectionHeading from "./SectionHeading.vue";
export default {
  components: { SectionHeading },
  name: "student-useful",
  data() {
    return {
      features: [
        {
          title: 'Create Courses<br> and Lessons',
          icon: 'icon-1.png',
          text: 'You can create unlimited courses, lesson and recurring courses.',
          animation: 'animate__slideInDown',
        },
        {
          title: 'Sell courses<br> Online',
          icon: 'icon-2.png',
          text: 'Using LearnPress WordPress plugin you can sell courses online using number of Payment Gateways',
          animation: 'animate__slideInUp',
        },
        {
          title: 'Events<br> Management',
          icon: 'icon-3.png',
          text: 'Student WP theme comes with The Event Calendar plugin compatibility to schedule events online.',
          animation: 'animate__slideInDown',
        },
        {
          title: 'One Click Demo<br> Install',
          icon: 'icon-4.png',
          text: 'Student WP theme comes with One click demo installation so start a wizard and content is ready within few minutes.',
          animation: 'animate__slideInUp',
        },
        {
          title: 'Customizablity<br> and Flexibility',
          icon: 'icon-5.png',
          text: 'Student WP theme comes with bundles of theme options and Elementor plugin that enables to customize anything.',
          animation: 'animate__slideInDown',
        },
        {
          title: 'Optimized Code<br> and CSS',
          icon: 'icon-6.png',
          text: 'Student WP theme code is optimized and well written so any PHP/WordPress developer can easily understand and modify.',
          animation: 'animate__slideInUp',
        },
        {
          title: 'Cross Browser<br> support',
          icon: 'icon-7.png',
          text: 'Student WP theme is compatible with all major browsers. It is fully responsive and fluid on all the devices',
          animation: 'animate__slideInDown',
        },
        {
          title: 'Child Theme<br> include',
          icon: 'icon-8.png',
          text: 'Student WP theme comes with Child theme support and its templates could be override from child theme with less code.',
          animation: 'animate__slideInUp',
        },
        {
          title: 'Well<br> Documented',
          icon: 'icon-9-white.png',
          text: 'Documentation is included in the full package and avialable online as well. Video tutorials are also available on youtube',
          animation: 'animate__slideInDown',
          active: true,
        },
      ]
    }
  },
  methods: {
    getIcon(icon) {
      return require(`../assets/images/icon/${icon}`);
    }
  }
};
</script>

<style lang="scss" scoped>
figure {
  margin: 0;
}

[class^="icon-"] {
  display: inline-block;
  line-height: 1;
  background-repeat: no-repeat;
  background-position: center;
  background-size: contain;
  vertical-align: middle;
  height: 50px;
  width: 50px;
}

.student-useful-background-image {
  background-image: url("../assets/images/bg-pattern.png");
  background-color: #f8f7ff;
}

.student-useful-col-main {
  padding: 55px;
  box-shadow: 0 0 35px rgb(0 0 0 / 20%);
  border-radius: 25px;
  background-color: #fff;
  height: 100%;
}

.student-useful-icon {
  padding: 20px;
}

.student-bg-styled {
  background-color: #4764fd;
  background-image: url("../assets/images/bg-wave.png");
  background-repeat: no-repeat;
  background-position: bottom;
}

.student-useful-heading h3 {
  font-weight: 600;
}
</style>