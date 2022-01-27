<template>
  <div class="bg-pattren">
    <div class="container">
      <section class="section-padding">
        <div class="video-block text-center">
          <div class="video-block-image">
            <figure class="video-sec mb-md-5m">
              <img class="bradius" src="../assets/images/video-cover.png" />
            </figure>

            <a
              href="https://www.youtube.com/watch?v=668nUCeBHyY"
              target="blank"
            >
              <i class="icon-play-btn"></i>
            </a>
          </div>
        </div>

        <section-heading tagline_place="before" :txt="false">
          <template slot="heading">REVIEW FOR </template>
          <template slot="styled">Students</template>
        </section-heading>

        <div class="text-area">
          <p class="text-dark text-center">
            Student Wordpress theme is generllay made for Online Learnin
            Management System.
          </p>
        </div>

        <div class="container mt-5">
          <div class="row justify-content-center">
            <div class="col-lg-4 col-md-6 my-4" v-for="review in reviews" :key="review.name">
              <div class="user-img-post">
                <div
                  class="
                    testimonal-area
                    text-center
                    bg-white
                    bradius
                    p-3 p-lg-4
                    pt-0 pt-lg-0
                    pb-lg-5
                  "
                >
                  <div class="testi-user-img">
                    <figure class="testi-img shadow-sm">
                      <img class="rounded-circle" :src="require(`../assets/images/${review.thumb}`)" />
                    </figure>
                  </div>
                  <div class="txt-block">
                    <p class="text-dark" v-html="review.review"></p>
                    <div
                      class="
                        user-info
                        d-flex
                        justify-content-center
                        align-items-center
                      "
                    >
                      <div class="icon">
                        <i class="icon-quotes"></i>
                      </div>
                      <div class="user-name-rank ms-3">
                        <div class="name">
                          <h4 class="user-name">{{ review.name }}</h4>
                        </div>
                        <div class="ranking d-flex">
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
          <div></div>
        </div>
      </section>
    </div>
  </div>
</template>


<script>
import SectionHeading from "./SectionHeading.vue";
export default {
  components: { SectionHeading },
  name: "testi-monals",
  data() {
    return {
      reviews: [
        {
          name: 'asimd2',
          review: 'Very helpful and accessible. The theme is very useful and up-to-date.You can use it with peace of mind',
          thumb: 'male-placeholder.jpeg'
        },
        {
          name: 'danish_tariq',
          review: 'Your software is good but i am very happy for your instant support, you were always ready to solve your customer problems and which is very appreciated. i strongly recommend your product and i ll love to work with you in future,thanks alot for your support',
          thumb: 'male-placeholder.jpeg'
        },
        {
          name: 'Tlazya',
          review: 'All is good, design, coding, and support <br>I like it and used it for one of my customers and might use it for another two.',
          thumb: 'male-placeholder.jpeg'
        },
      ],
    };
  },
};
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
  border-radius: 10px;
}

.bradius {
  border-radius: 40px;
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
  margin-bottom: 2em;
}

.icon-play-btn {
  margin: 0;
  margin-top: -75%;
}

.icon-play-btn {
  background-image: url("../assets/images/icon/icon-play.png");
  width: 40px;
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

.testi-user-img::before,
.testi-user-img::after {
  content: "";
  width: 0;
  height: 0;
  border-left: 17px solid transparent;
  border-right: 17px solid transparent;
  border-top: 19px solid rgba(0, 0, 0, 0.03);
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
  background-image: url("../assets/images/icon/icon-quote.png");
  width: 40px;
  height: 45px;
}

h4.user-name {
  margin: 0;
}

.txt-block {
  line-height: 1.5;
}

@media (min-width: 992px) {
  figure.video-sec {
    margin-top: -370px;
  }

  .section-padding {
    padding-bottom: 350px !important;
  }

  .mb-md-5m {
    margin-bottom: 5em !important;
  }

  .icon-play-btn {
    width: 60px;
    height: 60px;
  }
}

@media (min-width: 1200px) {
  .icon-play-btn {
    margin-top: -65%;
  }
}
</style>