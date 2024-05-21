<script setup lang="ts">
import banner2 from "../assets/banner2.png";
import star from "../assets/star.svg";
</script>

<template>
  <div class="feature-wrapper">
    <div class="image">
      <img :src="banner2" alt="banner2" />
    </div>
    <div class="detail">
      <div class="tip">
        <span>特色</span>
      </div>
      <div class="title">
        <span>涂鸦板块</span>
      </div>
      <div class="feature">
        <div class="sub-title">
          <img :src="star" alt="star" />
          <span>智能画笔</span>
        </div>
        <div class="note">
          <span>
            根据用户的需求提供不同的画笔效果，如油画、水彩、铅笔等，让用户在绘画时能够更加轻松地实现各种绘画效果。
          </span>
        </div>
      </div>
      <div class="feature">
        <div class="sub-title">
          <img :src="star" alt="star" />
          <span>实时反馈</span>
        </div>
        <div class="note">
          <span>
            AI能够实时分析用户的绘画过程，提供反馈和建议，帮助用户及时调整绘画方法，更好地实现创作意图。
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.feature-wrapper {
  position: relative;
  margin: 0 auto;
  width: 1300px;
  height: 100vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  .image {
    img {
      width: 600px;
    }
  }
  .detail {
    width: 600px;
    display: flex;
    flex-direction: column;
    gap: 20px;
    .tip {
      font-size: 24px;
      color: #bdaffa;
      span {
        display: block;
      }
    }
    .title {
      font-size: 48px;
      font-weight: 700;
      span {
        display: block;
      }
    }
    .feature {
      display: flex;
      flex-direction: column;
      gap: 10px;
      .sub-title {
        display: flex;
        align-items: center;
        gap: 10px;
        img {
          width: 24px;
          height: 24px;
        }
        span {
          font-size: 20px;
          font-weight: 700;
        }
      }
      .note {
        font-size: 18px;
        color: #7f7e7d;
      }
    }
  }
}
</style>
