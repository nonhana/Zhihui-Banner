<script setup lang="ts">
import info from "../assets/info.png";
</script>

<template>
  <div class="info-wrapper">
    <div class="image">
      <img :src="info" alt="info" />
    </div>
  </div>
</template>

<style scoped lang="scss">
.info-wrapper {
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  .image {
    img {
      height: 508px;
    }
  }
}
</style>
