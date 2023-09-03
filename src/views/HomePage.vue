<script setup>
import HeroSection from '../components/HeroSection.vue'
import GridSection from '../components/GridSection.vue'
import Cards from '../components/Cards.vue'
import Title from '../components/Title.vue'
import Form from '../components/Form.vue'
import Button from '../components/Button.vue'
import EventButton from "../components/EventButton.vue";


</script>

<template>

  <div>

  <HeroSection></HeroSection>
  <GridSection></GridSection>
  <Cards></Cards>

    <div class="card-button-shell">
    <Button class="button-show-more" content="Show more"></Button>
  </div>

    <div >
  <Title content="Working with POST request"></Title>
  </div>
  <Form></Form>
  </div>
  <EventButton></EventButton>

</template>

<style scoped lang="scss">

.card-button-shell {
  margin-bottom: 140px;
}

.button-show-more {
  display: block;
  background-color: #F4E041;
  width: 120px;
  height: 34px;
  border-radius: 20px;
  font-size: 16px;
  font-weight: 400;
  line-height: 26px;
  color: rgba(0, 0, 0, 0.87);
  margin: 0 auto;
  &:hover{
    background-color: #FFE302;
  }
}




</style>