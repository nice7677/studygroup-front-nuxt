<template>
  <div>
    <div class="col-xl-12 d-none d-sm-block no-margin" style="padding: 0px;">
      <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="4000"
        controls
        indicators
        background="#ababab"
        img-width="1024"
        img-height="250"
        style="text-shadow: 1px 1px 2px #333;"
        @sliding-start="onSlideStart"
        @sliding-end="onSlideEnd"
      >
        <!-- Text slides with image -->
        <b-carousel-slide
          caption="Studygram"
          img-src="https://picsum.photos/1024/250/?image=192"
          text="스터디 그램은 무료 입니다."
        >
        </b-carousel-slide>

        <!-- Slides with custom text -->
        <b-carousel-slide
          caption="Study Manager"
          text="누구나 스터디 매니저가 될 수 있습니다."
          img-src="https://picsum.photos/1024/250/?image=134"
        ></b-carousel-slide>

        <b-carousel-slide
          caption="Study Search"
          text="누구나 스터디에 참여 할 수 있습니다."
          img-src="https://picsum.photos/1024/250/?image=137"
        ></b-carousel-slide>
      </b-carousel>
    </div>
    <div class="col-12 d-block d-sm-none" style="padding: 0px;">
        <b-carousel
          id="carousel-2"
          v-model="slide"
          :interval="4000"
          controls
          indicators
          background="#ababab"
          img-width="500"
          img-height="350"
          style="text-shadow: 1px 1px 2px #333;"
          @sliding-start="onSlideStart"
          @sliding-end="onSlideEnd"
        >
          <!-- Text slides with image -->
          <b-carousel-slide
            caption="Studygram"
            img-src="https://picsum.photos/500/350/?image=192"
            text="스터디 그램은 무료 입니다."
          >
          </b-carousel-slide>

          <b-carousel-slide
            caption="Study Manager"
            text="누구나 스터디 매니저가 될 수 있습니다."
            img-src="https://picsum.photos/500/350/?image=161"
          ></b-carousel-slide>

          <b-carousel-slide
            caption="Study Search"
            text="누구나 스터디에 참여 할 수 있습니다."
            img-src="https://picsum.photos/500/350/?image=137"
          ></b-carousel-slide>
        </b-carousel>
    </div>

  </div>
</template>

<script>
  import Vue from 'vue'
  import BootstrapVue from 'bootstrap-vue'

  import 'bootstrap/dist/css/bootstrap.css'
  import 'bootstrap-vue/dist/bootstrap-vue.css'


  Vue.use(BootstrapVue)
  import pic from 'assets/pic/test.png'
  export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    comments : {
      pic,
    },
    name: "Top",
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }
</script>

<style scoped>

</style>
