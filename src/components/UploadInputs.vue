<script></script>
<template>
  <div class="upload-input">

    <label for="image_uploads" class="label-field-upload-file">Upload
      <input class="image_uploads" type="file" id="image_uploads" accept=".jpg, .jpeg, .png"
             name="Upload" multiple >
    </label>

    <label>
      <input class="input-field-upload" type="text" name="Upload your photo" placeholder="Upload your photo" required readonly>
    </label>
  </div>
</template>

<style scoped lang="scss">

.upload-input {
  margin-top: 50px;
  margin-bottom: 50px;
  justify-content: center;
  display: flex;
  @media (max-width: 360px) {
    max-width: 328px
  }
}

.input-field-upload {
  padding-left: 20px;
  font-size: 16px;
  color: #7E7E7E;
  background-color: #f8f8f8;
  border: 1px solid #D0CFCF;
  border-radius: 0 6px 6px 0;
  width: 297px;
  height: 54px;
  @media (max-width: 360px) {
    width: 244px
  }
}


.label-field-upload-file {
  padding-left: 15px;
  padding-top: 18px;
  font-size: 16px;
  color: #000000;
  background-color: #f8f8f8;
  border: 1px solid #000000;
  border-radius: 6px 0 0 6px;
  width: 83px;
  height: 54px;
  &:hover{
    cursor: pointer;
  }
}


.image_uploads {
  opacity: 0;
}


</style>
