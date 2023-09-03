<script setup>

</script>

<template>
  <div class="input-select-block">
  <div class="register-selects">
    <p class="register-selects-title">Select your position</p>
</div>
    <div class="label-select-title">
    <label ><input type="radio" name="select" value="Frontend developer" checked>     Frontend developer</label>
    <label ><input type="radio" name="select" value="Backend developer">     Backend developer</label>
    <label ><input type="radio" name="select" value="Designer">     Designer</label>
    <label ><input type="radio" name="select" value="QA">     QA</label>
  </div>
  </div>
</template>

<style scoped lang="scss">
.input-select-block {
  font-size: 16px;
  line-height: 34px;
}


.label-select-title {
  display: flex;
  flex-direction: column;
}

</style>