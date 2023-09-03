<script setup>
import Button from '../components/Button.vue'
</script>

<template>

  <header class="header">
    <div class="header__container">
      <picture class="header_logo">
        <img src="/src/assets/Logo-small.png" alt="logo">
      </picture>

      <div class="header_buttons">
      <Button content="Users"></Button>
      <Button content="Sign Up"></Button>
    </div>

    </div>
  </header>

</template>

<style scoped>

.header {
  background-color: #fff;
}

.header__container {
  display: flex;
  padding-bottom: 5px;
  padding-top: 5px;
  min-height: 60px;
  align-items: center;
  justify-content: space-between;

}

.header_buttons {
  display: flex;
  gap: 10px;
}


@media (max-width: 360px) {

}

</style>