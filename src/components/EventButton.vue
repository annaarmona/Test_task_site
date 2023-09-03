<script setup>

import Button from "./Button.vue";


</script>

<template>


  <div  class="home-page-bottom-gap">
    <Button class="button" content="Sign Up"></Button>
  </div>




</template>

<style scoped lang="scss">


.home-page-bottom-gap {
  padding-bottom: 100px;
}

.button {
  display: block;
  background-color: #B4B4B4;
  width: 100px;
  height: 34px;
  border-radius: 20px;
  font-size: 16px;
  font-weight: 400;
  line-height: 26px;
  color: rgba(255, 255, 255, 0.87);
  margin: 0 auto;
  &:hover {
    background-color: #B4B4B4;
  }
}




</style>