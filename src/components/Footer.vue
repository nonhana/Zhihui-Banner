<script setup lang="ts">
import logo from "../assets/logo.svg";
</script>

<template>
  <div class="footer-wrapper">
    <div class="container">
      <div class="image">
        <img :src="logo" alt="logo" />
      </div>
      <div class="links">
        <span class="title">产品</span>
        <span class="link">AI润色</span>
        <span class="link">AI故事</span>
        <span class="link">AI写真</span>
      </div>
      <div class="links">
        <span class="title">服务</span>
        <span class="link">帮助中心</span>
        <span class="link">意见反馈</span>
        <span class="link">服务条款</span>
      </div>
      <div class="links">
        <span class="title">公司</span>
        <span class="link">关于我们</span>
        <span class="link">加入我们</span>
        <span class="link">成长历程</span>
        <span class="link">媒体报道</span>
      </div>
      <div class="links">
        <span class="title">联系我们</span>
        <span class="link">17858863743</span>
        <span class="link">1040596498@qq.com</span>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.footer-wrapper {
  position: relative;
  width: 100%;
  padding: 50px 0;
  background-color: #fff;
  display: flex;
  justify-content: center;
  .container {
    display: flex;
    justify-content: space-between;
    width: 1200px;
    .image {
      img {
        width: 120px;
      }
    }
    .links {
      display: flex;
      flex-direction: column;
      gap: 20px;
      .title {
        font-size: 16px;
        font-weight: 500;
        color: #333;
      }
      .link {
        font-size: 14px;
        color: #666;
        cursor: pointer;
        &:hover {
          color: #333;
        }
      }
    }
  }
}
</style>
