<script setup>

</script>

<template>
    <div class="hero">
        <div class=" container header">
            <a class="header__logo font-700-lg  " href="#home_page">
                <img src="public/Hero/Group 12.png" alt="#logo-dutwind">
                Dutchwind
            </a>
            <nav class="header__nav">
                <a class="font-400-sm" href="#about">About Us</a>
                <a class="font-400-sm" href="#service">Service</a>
                <a class="font-400-sm" href="#project">Project</a>
                <a class="font-400-sm" href="#article">Article</a>
            </nav>
            <div class="header__btn ">
                <a class="font-400-sm " href="#contact">Contact Us</a>
                <img src="public/Hero/Frame-1.png" alt="#arrow_icon">
            </div>
        </div>


        <div class="container hero-title ">
            <h1 class="font-500-xl">Smart Concept For Better Energy</h1>
            <div class="hero-title__btn">
                <a href="#contact" class="font-400-lg ">Contact us now</a>
                <img src="public/Hero/Frame.png" alt="#arrow_icon">
            </div>
        </div>

        <div class="container hero-footer">
            <h4 class="font-700-lg">Dutchwind</h4>
            <p class="font-400-sm ">Best Windpower Energy in This World</p>
        </div>
    </div>
</template>


<style lang="scss">
@import "src/common/font.scss";
@import "src/common/color.scss";

.hero {
    margin: 0 auto;
    max-width: 1440px;
    height: 1152px;
    background-image: url('public/Hero/Group 19.png');
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 24px;

    &__logo {
        display: flex;
        align-items: center;
        gap: 20px;
    }

    &__nav {
        display: flex;
        justify-content: space-around;
        width: 353px;
    }

    &__btn {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 1px;
        height: 45px;
        width: 158px;
        border: 1px solid $color-primary;
        border-radius: 35px;

        a {
            color: $color-primary;
        }
    }
}

.hero-title {
    display: flex;
    flex-direction: column;
    gap: 36px;
    padding-top: 179px;

    h1 {
        max-width: 1051px;
    }

    &__btn {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 18px;
        height: 72px;
        width: 330px;
        background-color: $color-primary;
        border-radius: 35px;

        a {
            color: $color-second-base;
        }
    }
}

.hero-footer {
    display: flex;
    flex-direction: column;
    gap: 5px;
    padding-top: 264px;
}
</style>