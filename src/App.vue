<script setup>
import { RouterView } from 'vue-router'
import Navigation from "@/components/Navigation.vue";

</script>

<template>
  <Navigation />

  <RouterView />

</template>

<style lang="scss">
*, *::before, *::after {
  padding: 0;
  margin: 0;
  border: 0;
  box-sizing: border-box;
}

a {
  text-decoration: none;
}

ul, ol, li {
  list-style: none;
}

img {
  vertical-align: top;
}

h1, h2, h3, h4, h5, h6 {
  font-weight: inherit;
  font-size: inherit;
}

html,body {
  height: 100%;
}

body {
  line-height: 1;
  font-family: Nunito,serif;
  background-color: #f8f8f8;
}


[class*=__container] {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0px 15px;

}

</style>
