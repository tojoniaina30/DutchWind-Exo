<script setup>
import { onMounted, ref } from 'vue';
import Hero from './components/Hero.vue';
import About from './components/About.vue';

const data = ref([])
/* const name = ref("")

data.value = [{}]

onMounted(() => {
}),

const test = ()=>{
}

export default {
  data() {
    return {
      data:[], 
      name:''
    }
  },
  mounted() {
    
  },
  methods: {
    test(){}

  },
} */
</script>

<template>
  <Hero />
  <About />
  <div>
    <!-- <input type="text" v-model="name" @click="test"> -->
  </div>
</template>

<style lang="scss">
@import "src/common/font.scss";
@import "./common/color.scss";

a {
  text-decoration: none;
  color: $color-first-base;
}

body {
  font-family: 'Lexend Deca', sans-serif;
  font-style: normal;
  background-color: #ABC3D6;
}

.container {
  margin: 0 auto;
  max-width: 1280px;
}
</style>
