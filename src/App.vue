<template>
  <Header />
  <div class="mx-auto w-75">
    <FeatureSection />
    <hr class="mx-auto hr-rule">
    <SearchSection />
    <hr class="mx-auto hr-rule">
    <VenueSection />
    <hr class="mx-auto hr-rule">
  </div>
  <Footer />  
</template>

<script setup>
import Header from './components/Header.vue';
import FeatureSection from './components/FeatureSection.vue';
import SearchSection from './components/SearchSection.vue';
import VenueSection from './components/VenueSection.vue';
import Footer from './components/Footer.vue';
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
body {
  font-family: Poppins;
}
.hr-rule{
  background: rgba(0, 0, 0, 1);
  width: 90%;
  border: 0;
  height: 1px;
  
}
</style>


