<script setup lang="ts">
import banner1 from "../assets/banner1.png";
import video from "../assets/video.svg";
</script>

<template>
  <div class="banner-wrapper">
    <div class="detail">
      <div class="title">
        <span>智绘</span>
        <span>让孩子的画笔生花</span>
      </div>
      <div class="note">
        <span>为孩子筑起一隅想象的天空</span>
      </div>
      <div class="buttons">
        <el-button
          style="width: 180px; height: 60px; color: #fff; font-size: 18px"
          type="primary"
          color="#BDAFFA"
          >一起开启旅程吧</el-button
        >
        <div class="button">
          <img :src="video" alt="video" />
          <span>演示视频</span>
        </div>
      </div>
    </div>
    <div class="image">
      <img :src="banner1" alt="banner1" />
    </div>
  </div>
</template>

<style scoped lang="scss">
.banner-wrapper {
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 200px;
  .detail {
    display: flex;
    flex-direction: column;
    gap: 20px;
    .title {
      font-size: 48px;
      font-weight: 700;
      span {
        display: block;
      }
    }
    .note {
      font-size: 16px;
      color: #7f7e7d;
    }
    .buttons {
      margin-top: 40px;
      display: flex;
      gap: 20px;
      .button {
        display: flex;
        gap: 10px;
        cursor: pointer;
        align-items: center;
        img {
          width: 40px;
        }
      }
    }
  }
  .image {
    img {
      width: 600px;
    }
  }
}
</style>
