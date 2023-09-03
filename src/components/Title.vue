<script setup>
defineProps(["content"])

</script>

<template>


  <section><h1 class="main-title">{{content}}</h1></section>

</template>

<style scoped>
.main-title {
  font-size: 40px;
  line-height: 40px;
  text-align: center;
}

</style>