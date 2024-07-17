<template>
  <section class="venue-section py-5">
    <div class="d-flex justify-content-between align-items-center">
      <h3 class="venue-heading">Our Popular Venues</h3>
      <p class="venue-para">See All</p>
    </div>
    <div class="container ">
      <swiper
        :slides-per-view="3"
        :space-between="34.13"
        pagination
        :breakpoints="breakpoints"
        class="mySwiper"
      >
        <swiper-slide class="" v-for="venue in venues" :key="venue.name">
          <div class="card h-100  image-container">
            <div class="">
              <img :src="venue.image" class="card-img-top image-container" :alt="venue.name">
            </div>
            <div class="card-body">
              <h5 class="card-title">{{ venue.name }}</h5>
              <p class="card-text">{{ venue.location }}</p>
              <div class="d-flex justify-content-between">
                <span>{{ venue.rating }} <i class="fa fa-star text-warning"></i></span>
                <span>{{ venue.reviews }} Reviews</span>
              </div>
            </div>
          </div>
        </swiper-slide>
        <div class="swiper-pagination"></div>
      </swiper>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue';
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/swiper-bundle.css';
import 'swiper/css';
import 'swiper/css/pagination';

const venues = ref([
  { name: 'Victory Sports Arena', image: '/src/assets/images/pic1.png', location: 'North College Road, Chittagong', rating: 4.5, reviews: 124 },
  { name: 'Oxygen Sports Turf', image: '/src/assets/images/pic2.png', location: 'South College Road, Chittagong', rating: 4.8, reviews: 98 },
  { name: 'Oxygen Sports Turf', image: '/src/assets/images/pic1.png', location: 'South College Road, Chittagong', rating: 4.8, reviews: 98 },
  { name: 'Oxygen Sports Turf', image: '/src/assets/images/pic2.png', location: 'South College Road, Chittagong', rating: 4.8, reviews: 98 },
  { name: 'Oxygen Sports Turf', image: '/src/assets/images/pic1.png', location: 'South College Road, Chittagong', rating: 4.8, reviews: 98 },
  { name: 'Oxygen Sports Turf', image: '/src/assets/images/pic2.png', location: 'South College Road, Chittagong', rating: 4.8, reviews: 98 },
]);

const breakpoints = {
  1024: {
    slidesPerView: 3,
    spaceBetween: 34.13
  },
  600: {
    slidesPerView: 2,
    spaceBetween: 20
  },
  480: {
    slidesPerView: 1,
    spaceBetween: 10
  }
};
</script>
<style scoped>
.venue-heading {
  font-size: 26px;
  font-weight: bold;
  font-family: "Poppins";
  margin-top: 64px;
  margin-bottom: 76px;
}
.venue-para {
  font-family: "Poppins";
  font-size: 16px;
  font-weight: 700;
  color: rgba(196, 48, 28, 1);
}
.card {
  border: none;
}
.image-container {
  width: 332.31px;
  height: 247.53px;
}
.card-img-top {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.swiper-pagination {
  position: absolute;
  text-align: center;
  transition: 300ms opacity;
  transform: translate3d(0, 0, 0);
  z-index: 10;
}
.swiper-pagination-bullet {
  background: #000;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  opacity: 0.5;
}
.swiper-pagination-bullet-active {
  background: #000;
  opacity: 1;
}
</style>
