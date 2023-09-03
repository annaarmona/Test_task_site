<script setup>

import Button from '../components/Button.vue'
import Title from '../components/Title.vue'

</script>

<template>

  <div class="section__container">

    <section class="hero_section">

      <div class="hero_section-text-block">

        <div>
        <Title class="title-hero-section" content="Test assignment for front-end developer"></Title>
      </div>

        <div class="hero-text">
          <p>What defines a good front-end developer is one that has skilled knowledge of HTML, CSS, JS
            with a vast understanding of User design thinking as they'll be building web interfaces
            with accessibility in mind. They should also be excited to learn, as the world of
            Front-End Development keeps evolving.</p>
        </div>
      </div>


      <Button content="Sign Up"></Button>


    </section>
    </div>

</template>

<style scoped lang="scss">

.title-hero-section {
  color: #f8f8f8;
  padding-bottom: 21px;
}

.hero_section {
  padding-top: 164px;
  padding-bottom: 163px;
  height: 650px;
  background-image: url("/src/assets/Rectangle 29.png");
  margin-bottom: 140px;
  @media (max-width: 360px) {
    padding-top: 40px;
    background-image: url("/src/assets/image 2.png");
    height: 500px;
  }

  @media (max-width: 1024px) {
    background-image: url("/src/assets/1 copy 3.png");
  }

  @media (max-width: 768px) {
    background-image: url("/src/assets/image 1.png");
    height: 500px;
  }
}

.hero_section-text-block {
  text-align: center;
  width: 380px;
  margin: 0 auto;
  @media (max-width: 360px) {
    width: 298px;
  }
}


.hero-text {
  color: #fff;
  margin-bottom: 32px;
  line-height: 26px;
  font-weight: 400;
}



</style>