<script setup>

import img1 from '@/assets/image/swiper/welcome1.png';
import img2 from '@/assets/image/swiper/welcome2.png';
import img3 from '@/assets/image/swiper/welcome3.png';
import img4 from '@/assets/image/swiper/welcome4.png';
import img5 from '@/assets/image/swiper/welcome5.png';


const card = [
    {
        id: 1,
        img: img1,
        icon: icon,
        title: " Naxly as the Winners in Global Agency Awards",
        body: "Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups."
    },
    {
        id: 2,
        img: img2,
        title: "Expert Prespective Agency Awards",
        body: "Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups."
    },
    {
        id: 3,
        img: img3,
        title: "Business Prespective Global Agency Awards",
        body: "Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups."
    },
    {
        id: 4,
        img: img4,
        title: "Value for Results in Global Agency Awards",
        body: "Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups."
    },
    {
        id: 5,
        img: img5,
        title: "Global Experience in Agency Awards",
        body: "Lorem ipsum is placeholder text commonly used in print, and publishing industries for previewing layouts and visual mockups."
    },

]

</script>

<template>
    <div class="swiper">
        <div class="swiper__cards">
            <div class="swiper__card" v-for="item in card" :key="item.id" :info="item">
                <img :src="item?.img" alt="" class="swiper__card-image">
                <h3 class="swiper__card-title">{{ item?.title }}</h3>
                <p class="swiper__card-txt">{{ item?.body }}</p>
            </div>
        </div>
    </div>
</template>
