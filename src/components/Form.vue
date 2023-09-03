<script setup>
import RegisterInputs from "@/components/RegisterInputs.vue"
import InputsSelect from "@/components/InputsSelect.vue";
import UploadInputs from "@/components/UploadInputs.vue";

</script>

<template>

  <section class="form_content">


    <RegisterInputs></RegisterInputs>
    <InputsSelect></InputsSelect>
    <UploadInputs></UploadInputs>



  </section>

</template>

<style lang="scss">

.form_content {
  max-width: 380px;
  width: 100%;
  margin: 0 auto;
  @media (max-width: 360px) {
    max-width: 328px
  }
}


</style>