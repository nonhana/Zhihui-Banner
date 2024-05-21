<script setup lang="ts">
import logo from "../assets/logo.svg";
</script>

<template>
  <div class="header-wrapper">
    <div class="container">
      <div class="buttons">
        <img :src="logo" alt="logo" />
        <div class="button">
          <span>主页</span>
        </div>
        <div class="button">
          <span>特色</span>
        </div>
        <div class="button">
          <span>帮助中心</span>
        </div>
        <div class="button">
          <span>关于我们</span>
        </div>
      </div>
      <el-button
        style="width: 180px; height: 60px; color: #fff"
        type="primary"
        color="#F5DD7D"
        ><span>下载</span></el-button
      >
    </div>
  </div>
</template>

<style scoped lang="scss">
.header-wrapper {
  position: relative;
  width: 100%;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(
    255,
    255,
    255,
    0.8
  ); /* 使用 rgba() 函数设置白色透明背景 */
  backdrop-filter: blur(10px); /* 添加模糊效果 */
  span {
    font-size: 18px;
  }
  .container {
    width: 1100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    .buttons {
      display: flex;
      align-items: center;
      gap: 40px;
      & > * {
        cursor: pointer;
      }
      img {
        width: 140px;
      }
      .button {
        color: #333;
        &:hover {
          color: #bdaffa;
        }
      }
    }
  }
}
</style>
