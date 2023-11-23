<script setup>
import Button from '@/components/UI/Button.vue';

</script>

<template>

    <section class="about">
        <div class="container">
            <div class="about__image">
                <img src="@/assets/image/about/about.png" alt="" class="about__png">
            </div>
            <div class="about__desc">
                <h3 class="about__title">Apply AI, Deep Learning and Data Sciece to solve</h3>
                <p class="about__txt">Lorem ipsum is placeholder text commonly used in the graphic, print, and publishing industries for previewing layouts and visual mockups.</p>
                <!-- <a href="#!" class="about__btn btn">Learn More</a> -->
                <Button text="Learn More"/>
            </div>
        </div>
    </section>

</template>
