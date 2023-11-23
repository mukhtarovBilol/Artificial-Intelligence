<script setup>
import { ref } from 'vue';


const items = ['New Collection', 'About Store', 'Contact Us', 'Latest News', 'Our Sitemap', 'Orders History'];

const menu = ['Instagram profile', 'New Collection', 'Contact Us', 'Latest News', 'Terms & Conditions', 'Purchase Theme'];

const more = ref(false)

</script>

<template>
    <footer class="footer">
        <div class="container">
            <div class="footer__desc">
                <a href="#!" class="footer__logo">
                    <img src="@/assets/image/nav/navLogo.svg" alt="" class="footer__img">
                    Artificial Intelligence
                </a>
                <p class="footer__txt">Lorem ipsum is placeholder text commonly used in the graphic, print, and layouts and
                    visual mockups.</p>
                <a href="mailto:Company@gmail.com.com" class="footer__contact">
                    <img src="../../assets/image/footer/email.svg" alt="" class="footer__contact-img">
                    Company@gmail.com.com
                </a>
                <a href="tel:0643321233" class="footer__contact">
                    <img src="../../assets/image/footer/phone.svg" alt="" class="footer__contact-img">
                    Phone: (064) 332-1233
                </a>
                <a href="" class="footer__contact">
                    <img src="../../assets/image/footer/geo.svg" alt="" class="footer__contact-img">
                    450 Wall Street, USA, New York
                </a>
            </div>
            <div class="footer__list">
                <h3 class="footer__title">INFORMATION</h3>
                <ul class="footer__menu">
                    <li class="footer__item" v-for="item in items" :key="item">
                        <a href="#!" class="footer__link">{{ item }}</a>
                    </li>
                </ul>
            </div>
            <div class="footer__list">
                <h3 class="footer__title">FOOTER MENU</h3>
                <ul class="footer__menu">
                    <li class="footer__item" v-for="item in menu" :key="item">
                        <a href="#!" class="footer__link">{{ item }}</a>
                    </li>
                </ul>
            </div>
            <div class="footer__list">
                <h3 class="footer__title">USEFUL LINKS</h3>
                <ul class="footer__menu">
                    <li class="footer__item" v-for="item in menu" :key="item">
                        <a href="#!" class="footer__link">{{ item }}</a>
                    </li>
                </ul>
            </div>
            <div class="footer__about">
                <h3 class="footer__title">ABOUT THE STORE</h3>
                <p class="footer__about-txt">Lorem ipsum is placeholder text commonly used in the graphic, print, and
                    layouts and visual mockups.</p>
                <div class="footer__company">
                    <a href="#!" class="footer__about-link">www.company.com</a>
                    <img src="../../assets/image/footer/socials.png" alt="" class="footer__socials">
                </div>
                <div class="footer__language" @click="more = more = !more">
                    <img src="@/assets/image/footer/lang.svg" alt="" class="footer__language-img">
                    <p class="footer__language-txt">English</p>
                    <img src="@/assets/image/footer/vector.svg" alt="" class="footer__language-vector">
                    <span :class="{'active' : more}">
                        <p class="footer__more">Русский</p>
                        <p class="footer__more">O'zbekcha</p>
                    </span>
                </div>
            </div>
        </div>
    </footer>
</template>

