<script setup>
import Button from '@/components/UI/Button.vue';


</script>

<template>
    <header class="header">
        <div class="container">
            <div class="header__banner">
                <div class="header__desc">
                    <p class="header__txt">Next genaretion platform</p>
                    <h1 class="header__title">Artificial intelligence & Syber security</h1>
                    <p class="header__subtitle">Lorem ipsum is placeholder text commonly used in the graphic, print, and
                        publishing industries for previewing layouts and visual mockups.</p>
                    <div class="header__links">
                        <!-- <a href="#!" class="header__link btn">Get Started</a> -->
                        <Button text="Get Started"/>
                        <div class="header__video">
                            <img src="@/assets/image/header/icon.svg" alt="" class="header__video-image">
                            <!-- <Button text="Watch Video"/> -->
                            <a href="#!" class="header__link2">Watch Video</a>
                        </div>
                    </div>
                </div>
                <div class="header__image">
                    <img src="@/assets/image/header/header.png" alt="" class="header__png">
                </div>
            </div>
            <div class="header__company">
                <a href="#!" class="header__company-image">
                    <img src="@/assets/image/header/Group1.svg" alt="" class="header__company-png">
                </a>
                <a href="#!" class="header__company-image">
                    <img src="@/assets/image/header/Group2.svg" alt="" class="header__company-png">
                </a>
                <a href="#!" class="header__company-image">
                    <img src="@/assets/image/header/Group3.svg" alt="" class="header__company-png">
                </a>
                <a href="#!" class="header__company-image">
                    <img src="@/assets/image/header/Group4.svg" alt="" class="header__company-png">
                </a>
            </div>
        </div>
    </header>
</template>

