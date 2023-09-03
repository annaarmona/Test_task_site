<script>

</script>

<template>

  <div class="register-inputs-container">
    <div class="input-box">
      <input class="input" type="text" required>
      <span class="pseudo-label">Your name</span>
    </div>

    <div class="input-box">
      <input class="input" type="text" required>
      <span class="pseudo-label">Email</span>
    </div>

    <div class="input-box">
      <input class="input" type="text" required>
      <span class="pseudo-label">Phone</span>
    </div>


      <span class="number-phone">+38 (XXX) XXX - XX - XX</span>


    </div>

</template>


<style scoped lang="scss">

.register-inputs-container {
  margin-bottom: 30px;
  margin-top: 50px;
}

.input-box {
  position: relative;
  height: 54px;
  line-height: 26px;
  width: 380px;
  margin-bottom: 50px;

}

.input-box:last-of-type {
  margin-bottom: 0;
}


.input {
  position: absolute;
  padding: 0 22px;
  line-height: 30px;
  background: transparent;
  transition: 0.1s ease;
  z-index: 1111;
  font-size: 16px;
  border: 1px solid #D0CFCF;
  border-radius: 6px;
  max-width: 380px;
  width: 100%;
  height: 54px;

}

.number-phone {
  color: #7E7E7E;
  font-size: 12px;
  line-height: 14px;
  font-weight: 400;
  padding-left: 22px;
}

.pseudo-label {
  position: absolute;
  color: #7E7E7E;
  margin: 14px 20px;
  transition: 0.2s ease;
}

.input:focus,
.input:valid {
  color: #000000DE;
  border: 1px solid #D0CFCF;
  border-radius: 6px;
  outline: none;
}

.input:focus + .pseudo-label,
.input:valid + .pseudo-label{
  color: #7E7E7E;
  height: 30px;
  line-height: 26px;
  transform: translate(-2px, -26px) scale(0.88);
  z-index: 1111;
  background-color: #F8F8F8;
  border-radius: 6px;

}


</style>