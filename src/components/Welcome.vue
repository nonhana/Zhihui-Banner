<script setup lang="ts">
import banner4 from "../assets/banner4.png";
</script>

<template>
  <div class="welcome-wrapper">
    <div class="title">
      <span>跟我们一起探索更多</span>
    </div>
    <div class="image">
      <img :src="banner4" alt="banner4" />
    </div>
  </div>
</template>

<style scoped lang="scss">
.welcome-wrapper {
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  .title {
    font-size: 40px;
    font-weight: bold;
    margin-bottom: 20px;
  }
  .image {
    img {
      width: 600px;
    }
  }
}
</style>
