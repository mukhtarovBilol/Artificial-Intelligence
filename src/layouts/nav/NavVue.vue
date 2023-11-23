<script setup>
import { ref } from 'vue';


const nav = ['Home', 'About', 'Services', 'Blog', 'Contact'];
const color = ref(false)

</script>

<template>
    <nav class="nav">
        <div class="container">
            <div class="nav__desc">
                <a href="#!" class="nav__logo">
                    <img src="@/assets/image/nav/navLogo.svg" alt="" class="nav__logo-image">
                    Artificial Intelligence
                </a>
                <ul :class="{'active' : color}">
                    <li class="nav__item" v-for="item in nav" :key="item">
                        <a href="#!" class="nav__link">{{ item }}</a>
                    </li>
                </ul>
                <a href="#!" class="nav__login">Sign In</a>
                <span class="nav__burger" @click="color = color = !color"></span>
            </div>
        </div>
    </nav>
</template>

