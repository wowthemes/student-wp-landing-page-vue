<template>
  <section class="section-padding section--what_else">
    <section-heading class="mb-5 pb-3">
      <template slot="heading">What else? You </template>
      <template slot="styled">deserve</template>
      Student WordPress theme is generally made for online Learning Management System.
    </section-heading>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-4 col-md-6 mb-5 pb-3" v-for="box in boxes" :key="box.title">
          <div :class="['card shadow h-100 text-center reveal']" :data-animate="box.animation">
            <div class="card-body">
              <div class="card-icon rounded-circle">
                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="46" height="52" viewBox="0 0 46 52">
                  <image id="updated" width="46" height="52" :xlink:href="box.img"/>
                </svg>
              </div>
              <h3 class="text-secondary fw-bold" v-html="box.title"></h3>
              <p class="fw-light" v-html="box.txt"></p>
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
  name: 'what-else',
  data() {
    return {
      boxes: [
        {
          img: 'data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAC4AAAA0CAYAAAD19ArKAAAE00lEQVRogc2aa4hWRRjHf25blpGiJiZk6qbdRbst6hd1JcXItpuo1ZeyUiEoiAqErbClsg+yUZClGUVfBKHUqCiEjdJtSbuHW7iCl7LVxJLES+o/xuZs0+y858x597y7+4cHdmeey/99zsx7nnnmRVKlpFZSm6Q7K+G/isrhBHA5sA54FehfZKRKEneJLgbagNlFOe9n0l4AJgCTgMnAWGCwlREB1yuAx4HTvUX8RuBe4GZLNg922mV0stzg1WXYzAEeAWaUGfMQ8FJ3M56H+KXAyynr9CDQCnwL7AYuAp72dN4FHgJ+L+FjJNBhN3Y6Ir9+lkg6oa74RVKTpGmSzvdshjnaRyUtzojRIOm0pF2S6rI4xZB+I0B4hyXSP8VuutVtljQ6Io6Ph7tD/OOAw6ckVUUQGS6pPsdLpSEQq7Ec4s2ekw5JUyv4pjWyKED+yTzE13rGrZKGVph0IpMlHfPi3xFD/LEA6Z4g7MoEu1FdjEgjPs5T3p+xASspsz0u29KIb/eUr+4l0oks8/gsDBFf4Ckt6WXSiXzvcPpLUrVPfI+j0NZHSBu5LpTQZHKmNzmzDxE38pnDrd0lvt6Z+LkHCY2XNCpCb4aX2BuwNcbfzuCjPUD4EkmbbTzztfdshM0+h+NyM3CT92liMtAdMW/fP9UV0zN8vu5YtJqj2yynfPwJ2JWj1M2LB4BmYGDAri7D1ybn7/GGeK0z8GEFSTcBq1LmP8qw/9Q5fKjKFvwJ2nIQqQEGROiZGOvtqakUGoDNGX5+A/bZv08Zp4OcyYMRREYBLUC7PTvOS9EdA3wH3JqiMxdojIhrcKDzL0mHnUU/O2LTtQQ2Vm1A7xZJRwK6CfZKmphzk2+xtodNxvs5nyjryF9l2xA+PgDOccYWARtTllKLbWl8E5npBJ1cDZHjzsR5GYZmc3wRGB8KvGn9LQdWpvgwelMil6WP//hJ2uk8vvsjHtfYlMffnjJn8EQ33wG/ukvFbRWMjvjUO4D5JeZqUuzqgRfLyHKCi53OWLUh/oMzOS3SyVpgdaTuHmAisCE/1/9hqvPPmfTP9x7nwByPri1jaXwiaVBBpcJbjt/PsW0EF/NyOBuZQrqp4BrnkON7WTK41RnclNOhadyf8kgXXWHO8fxfk0z4/YwxOR3XSFpq5cqCSRv52uH2o5yDxLleb/C9CgQvV2Z5SV0g78z5gqdwbR8hvtfhtD8ZdxUGeCehXX2A9GovmbeFiBu521Nc34uk/X33vjsfMtjoGTzXC6T9LtYRv6MWMjrbqQkSPNODpOeqK6b4eqWMawId03cknVVh0o0B0veEdNOcmA7Scc+J+Q69MJKEqSKvj9QdF+jHG9xXyibL4VWSdnvOHowgktQ/WzL0TCtkRaClbN7Et6fZxmTDFEkbrENTL1yWojvYK4ZWBXSG2CsWs/ROBrL8pU1YKq88F7ST7AH5QIn5ett+GOaMmZbCK/Ya0NT6V9jb5wtK+FgKPB/FpoANZeqalYHMxcJkfY1d59Fxy7lZ9lFnD8d58ZW9sH3bXujmQlE/QrgLeA0Y4o2bu/o/7G2xIWfae9ts82d7tyIWsFQSGe5s4gTrbOVZZJwzUuTvVTpsx2ohcNSOmaV4rMAYnajED23W8O+3x1avZ1McgH8AuxxvKS4We9EAAAAASUVORK5CYII=',
          title: 'Free lifetime <br>updates',
          txt: 'We release the theme updates<br> regularly once you buy and <br>get updates lifetime.',
          animation: 'animate__slideInDown',
        },
        {
          img: 'data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAA0CAYAAADMk7uRAAAEdklEQVRoge2aXYhVVRTHf3P7wsY+yTErygihohEpSclqoogmiogCxaQggklxXgYKfBKTIghBpSYqSIgeKsOHHoReoi9nQMmHEiopKHUsHE1zJsWPqRUr1pXdcp97zrmz77kT9IcN9+y9z1r/dfbaa6+99+0QERJgBrAI6AbmAbOBLuASE30UGAV+Ar4BdgHbgIOTVT0ZAy4GFgNLjPy0ku8fB4aBD4H3gPGmWKgBJctMEXlFRH6TdDhkMmeW5VOWfL+IjCUk7jEuIivLcCrqQtcB7wA9Dfr8YC6xE9hrPn/E2i6zOXEtcBtwBzCngaxPgaeBPSlc6AH7MjEcFZGNIrKoCVe8U0Q2mIys0eidrAs902C4XxSRK5og7ovKeLmBnqeaNWBZhsBhEZmbgLgvKnMoQ+eysgb0ZAha1wLivqzP0N1T1IAuETkZEfBsBeTrZUVEv3K6tIgBX0VeHqiQfL0MRHhsyzNgeeSlV9tAvl5ei/BZHvYJ14ELLWc5N4iyO4AFRRaKFuJrYG4gfsJyLE1FqAUNzzvyisfaTF7xsHtWjs+debKh6IgsVhva6Dq+bHTclGstnAM+5p8Skc4pZECncQqxVNvqLrTSDZPmPcda7hzFccw4hXgS2w9oonUomA9iG5K9U8gALKHUDVGHPZ8ErtQJca+bzIq3zOohYBPwexsIY9GmD1hoUTLEBcB96l9rIrE2xGiT2eZki+o8kMNtTc32sY2g+90vgasr/PKzTGdXTr/uWs7Gog71u9fT8cvFpsDXG2FOLWKl7qoeAQZdvdZdVAF5HeleVzdo+ne6+hlE9rg3BL6737XdWpHvhxgJ2m50bWM++mC5Rh2HXZtPNapAGAGPO30dNYv7IcJwdb5r+7MCwn+55/OC352uTWIj8J/C/wZUjLMOsWoF4+2URcyA08FvP2mrMNbrCDlM+L61SGgMQ6dvOycBwTx4tw45HPHv1iKVqyx06Vbuete2rwID/Noz27gop9Wu7ZSubm9EsrxfInXfV5SF6lZxX1FO+sKs7Gz1X3iowlS6tyCnzepCvwL35wzrC8DWxK7SCB+bzjxsD63uFpEtInLYrDthJ2FL2riZX2wHvuMZR/y3xC44pgPX2GQarfCr52HILkbq0NR6fqpbylZjod1qhmH8UeCjVhqgx4E32/L/nV2vNgO9lvrRZaU/nwnxLfDbB+0SxGPYrqvKyLpJRA5GZC2o90lNvr9A6OsvKOuJyGmc4qWwX0ry8wrG7n+iRwM5uqXcmvHeB75/yjnwiR2ShfjCft/t6rcDK+z3NNvIzwfuAW7PkP8+sPSs2kRf//LI1+oL2vtKjE4Ma7N0pzLgLqc0ljftboL4jrxTwVSnDP4kO3Z+NL2EvM+Bt4F38zqmMmCXGVE/NbgK2AwM2PN6qwvxrW1e9KjkALDfVtfPgN2FNSeMQoMRF5iw4vFmKr0po5D+f2ikwPHjuI3GHymUpjyVGLOcZaRBnz3WJwl5RStyIZ0H6vuP23ZQFSjxLcA64EQyTcDfTYMveKmQvT8AAAAASUVORK5CYII=',
          title: 'First-Class <br>support',
          txt: 'Through our dedicated support forum, ticket system and live <br>chat we are available 24/7',
          animation: 'animate__slideInUp',
        },
        {
          img: 'data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAADQAAAAkCAYAAADGrhlwAAAEhklEQVRYhe1YXYhVVRT+ZlLL0VGJjDA1c7TQ0JEUjcQeRtSyB0lRegjJIqTJl0oKsyGoRNAifDAYVHzRKBEsJDL7IUczZaZCR5sxSzQDJ0wzrRlTmi/29B1abO4+95xz77lPLdjcfff61l5r7b3W3mufKpLImaoB7AUwDMAsAD15qquEQ7UALqtfB+BUnsqq85xcVGX6vXkrq4RDDPRzoUo4VFH636EMZHOoqmyzBiipQyMBvA6gIYMOmzdZFnAagDUAxibTRiZpT/Bf+jwh3rZqkodJniRZk0G+WbqfTYJPeg8NAbAYwCEAlwD0B3A6w2qnodsADATwN4C5AHYBuFBMPsvF2qtcuB/AVzk5cxeAbwHUpM27tDF9g8oYRwcV30loC4CdCbF3AmiTM0cADEplYYaYdu19xfV1klOLYOv5H80rgh1P8rzQ+0hWpbUtq0Ou7TSG3huD+8zgjsfgJmmBImcy2VWKQ67tJtlLcnqAf48MvEqyW/3ZAewc8Q+XYlOpDrk2OIb3oYx8kuRD6n9TJDyrS7Enz+fDJABH1Y9Oqm4dxe5ddCAPpXmWPhv022zGXiswVl4qQ8gVajPNQTDc8AeQvKbxhXnoLiXkhukCvAPAaADjFGZjANwuzHYAj3lyriZcrX4XgJ8AHAPQCeBnVSA/ADifyaoMqzCCZDvJK4ynFm93onYjyU/MEV2Iekh2kqyrxA7VaQUj2gOgA8AZ/Z4FcE41XxzVaidHAJignR0PYIGRmQygvVw7NEQ3dyHedJMLm8uYA28kqCrGBHa+r8VNflITjwrw681l+WkZnHnPONMQwNTqIv8trUPzzeTbYoyYqHh3tL8EZ3YZfbNicGsMbnkah9q9RB1axKlLwrUo6dM4s1uybuXvK4LtMTZ1FXPoJtVeKyXwnVH2AckZJG8OKBpL8rSwh0j2S+hMVOC6CntaADNUvK3CumL3a/XXKvQHWYfeInnUlO0RzRfI0p8kT5D8iORoT/FUg+uf0KGzwi/wxm/RE6WD5GXPhhrvSeLoIslj7rnuG3xKCd5s3iIrtCpfetiZnhGzNZ7mgNgumWXe+N2erjZ9z2gymDdlV6cFOsYUkn/o/8cxyp83cs/FJOzGFA41SWZTAd5So29dzBw7DK7BrsgFs8L+15mXjNBTgYnfFb+xAO8Fkq+QHOiNPyyZA4E5H9Fh4Wi9x3PPjHfE644ixgImGKNv9YSj/FoVs1LR1tvkXkLyezNvl95GEX+kxq/G5N0yL6Jsi2iuPRSiNlzMDv1/nORq9V8Wb0nMSUSFLnQxthqFrTrSaXQs8g6GUN0W5eYW/X9ReQ1Fk6PJhRx6VMzj3gHwI8k96m8NKJ0i/q8k9xrZcySf8fLihOF/Yf4/GJj7VfH36SSLqM0c342FHLJ1FBUqLd7YmYDSpz3cX8qbAQF8o5y35OdI1Ny9ZukgySPemMvfPrx9sbr+FVXLq/TWeQDAQgCt4v0eqHEHi/8LgPX6Fr4OwLUA/m0AowA06Q3kZEMfFK+L76rupfrAWQ9ghap+x+vXhwTwD6efo4h0tKIRAAAAAElFTkSuQmCC',
          title: 'Rock-Solid <br>5-Star Rating',
          txt: 'Through our dedicated support forum, ticket system and live <br>chat we are available 24/7',
          animation: 'animate__slideInDown',
        },
      ]
    }
  }
}
</script>
<style lang="scss" scopeed>
.section--what_else {
  padding-bottom: 36px !important;
  background: url('../assets/images/bg-2.jpg') no-repeat scroll;
  background-size: cover;
  .card {
    border-radius: 20px;
    border: none;
    transition: all 0.8s;
    cursor: pointer;
    .card-body {
      padding: 60px 60px 40px;
      h3 {
        font-size: 20px;
        margin: 10px 0 20px;
      }
      p {
        font-family: Roboto;
        font-size: 1rem;
        color: #4c5895;
      }
      .card-icon {
        width: 90px;
        display: inline-flex;
        height: 90px;
        justify-content: center;
        align-items: center;
        position: absolute;
        top: -15%;
        left: calc(100%/2 - 45px);
        background-color: #6588fc;
        transition: all 0.5s;
      }
    }
    &:hover {
      box-shadow: 0 0.1rem 2rem rgb(0 0 0 / 15%) !important;
      .card-icon {
        background-color: #0e1951;
        transform: rotate(360deg);
      }
    }
  }

  .h-100 {
    height:100% !important;
  }
}
</style>