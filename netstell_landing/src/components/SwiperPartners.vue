<template>
  <swiper class="swiper pt-5 pr-5 pl-5" :options="swiperOption">
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <swiper-slide class="container">
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
        <div class="row">
            <div class="square"></div>
            <p>Название</p>
        </div>
    </swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
  </swiper>
</template>

<script>
  import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
  import 'swiper/swiper-bundle.css'

  export default {
    name: 'SwiperPartners',
    components: {
      Swiper,
      SwiperSlide
    },
    data() {
      return {
        swiperOption: {
          slidesPerView: 4,
          spaceBetween: 30,
          pagination: {
            el: '.swiper-pagination',
            clickable: true
          }
        }
      }
    }
  }
</script>

<style scoped>
.square {
  height: 200px;
  width: 100%;
  background-color: #555;
}
</style>