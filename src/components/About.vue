<script setup>

</script>

<template>
    <div class="about">
        <div class="presentation container">
            <h2 class="font-500-lg">About DutchWind</h2>
            <div class="presentation__desc">
                <p class=""><strong>Dutchwind</strong> is a company engaged in the energy industry that has been established
                    since 1987 - now.</p>
                <p class=""><strong>Dutchwind</strong> is a company engaged in the energy industry that has been established
                    since 1987 Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                    labore et dolore magna aliqua.</p>
                <a href="#read_more" class="font-700-md">Read more</a>
            </div>
        </div>
        <div class="line container"></div>
        <div class="stats container">
            <div>
                <p class="font-400-xl">200</p>
                <h3 class="font-700-xl">HectareTotal Area</h3>
            </div>
            <div>
                <p class="font-400-xl">200</p>
                <h3 class="font-700-xl">HectareTotal Area</h3>
            </div>
            <div>
                <p class="font-400-xl">200</p>
                <h3 class="font-700-xl">HectareTotal Area</h3>
            </div>
            <div>
                <p class="font-400-xl">200</p>
                <h3 class="font-700-xl">HectareTotal Area</h3>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
@import "src/common/font.scss";
@import "src/common/color.scss";

.about {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0 auto;
    padding-top: 85px;
    padding-bottom: 280px;
    max-width: 1440px;
    height: 1136px;
    border-radius: 75px 75px 0px 0px;
    background-color: $color-second-base;
}

.presentation {}
</style>