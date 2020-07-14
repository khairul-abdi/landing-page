<template>
  <div class="container">
    <div class="row">
      <div class="col-md-8 offset-md-2">
        <p class="testimonial">Testimonial</p>
        <section>
           <vue-horizontal-list :items="items"
                           :options="{responsive: [{end: 576, size: 1}, {start: 576, end: 768, size: 2},{size: 3}]}">
              <template v-slot:default="{item}">
              <div class="item">
                <p class="title-testi">{{item.by}}</p>
                <p class="content-testi">{{item.testimony}}</p>
              </div>
            </template>
          </vue-horizontal-list>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
import Vue from 'vue'
import VueHorizontalList from './vue-horizontal-list.vue'
import axios from 'axios'

export default Vue.extend({
  name: 'Testimonial',
  components: {
    VueHorizontalList
  },
  data () {
    return {
      // items: [
      //   { title: 'Arron', content: 'couldn\'t have asked for more than this. I wish I would have thought of it first. This is simply unbelievable!' },
      //   { title: 'Kelsey', content: 'Wow what great service, I love it! Without WEEKEND, we would have gone by now. You guys rock' },
      //   { title: 'SoYoung', content: 'Unless you have a truly unique product, it will be very hard to differentiate and gain brand traction' },
      //   { title: 'Steven', content: 'I wish I would have thought of it first.' },
      //   { title: 'Charley', content: 'Content item with description' },
      //   { title: 'Vanessa', content: 'This is unbelievable. After using WEEKEND my business skyrocketed!' },
      //   { title: 'Vanessa', content: 'This is unbelievable. After using WEEKEND my business skyrocketed!' }
      // ]
      items: []
    }
  },
  mounted () {
    axios.get('https://wknd-take-home-challenge-api.herokuapp.com/testimonial')
      .then(response => {
        this.items = response.data
      })
      .catch(error => {
        console.log(error)
      })
  }
})
</script>

<style lang="scss" scoped>

  .testimonial {
    margin-top: -160px;
    margin-bottom: 30px;
    text-shadow: 0 20px 30px rgba(249, 131, 171, 0.7);
    font-family: 'Work Sans';
    font-size: 32px;
    color:black;
    text-align: center;
    font-weight: 900;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: normal;
    color: #ffffff;
  }

  .item {
    padding: 20px 20px;
    border-radius: 4px;
    background: #F5F5F5;
    height: 140px;
  }

  section {
    margin-top: 24px;
  }

  .title-testi {
    font-family: 'Work Sans';
    width: 151px;
    height: 38px;
    font-size: 32px;
    font-weight: 900;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: normal;
    color: var(--black);
    padding-bottom: 20px;
  }

  .content-testi {
    font-family: 'Work Sans';
    font-size: 12px;
    font-weight: normal;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: -0.43px;
    color: var(--black);
  }

@media screen and (max-width: 575px) {
  .testimonial {
    margin-top: -100px;
  }
}
</style>
