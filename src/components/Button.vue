<script setup>
defineProps(["content"])

</script>

<template>

    <button class="button">{{ content }}</button>

</template>

<style scoped lang="scss">


.button {
  display: block;
  background-color: #F4E041;
  width: 100px;
  height: 34px;
  border-radius: 20px;
  font-size: 16px;
  font-weight: 400;
  line-height: 26px;
  color: rgba(0, 0, 0, 0.87);
  margin: 0 auto;
  &:hover {
    background-color: #FFE302;
  }
}



</style>