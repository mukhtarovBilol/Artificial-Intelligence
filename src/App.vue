<script setup>

import Nav from '@/layouts/nav/NavVue.vue';
import HeaderVue from '@/layouts/header/headervue.vue'; 
import AboutVue from '@/views/about/AboutVue.vue';
import Swiper from '@/views/swiper/SwiperVue.vue';
import OurClients from '@/views/ourClients/ourclients.vue';
import Footer from '@/layouts/footer/Footer.vue'


</script>

<template>
  <Nav/>
  <HeaderVue/>
  <main>
    <AboutVue/>
    <Swiper/>
    <OurClients/>
  </main>
  <Footer/>
</template>

