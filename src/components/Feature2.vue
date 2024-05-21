<script setup lang="ts">
import banner3 from "../assets/banner3.png";
import star from "../assets/star.svg";
</script>

<template>
  <div class="feature-wrapper">
    <div class="detail">
      <div class="tip">
        <span>特色</span>
      </div>
      <div class="title">
        <span>故事板块</span>
      </div>
      <div class="feature">
        <div class="sub-title">
          <img :src="star" alt="star" />
          <span>社区</span>
        </div>
        <div class="note">
          <span>
            一个让用户分享、交流和发现创意作品的空间，用户可以浏览其他用户的绘画作品，为他们点赞、评论、分享以及制作同款。
          </span>
        </div>
      </div>
      <div class="feature">
        <div class="sub-title">
          <img :src="star" alt="star" />
          <span>自定义</span>
        </div>
        <div class="note">
          <span>
            用户可以根据喜好自定义故事概述、故事主角、画面风格等，创作独特的故事视频。
          </span>
        </div>
      </div>
      <div class="feature">
        <div class="sub-title">
          <img :src="star" alt="star" />
          <span>社区</span>
        </div>
        <div class="note">
          <span>
            一个让用户分享、交流和发现创意作品的空间，用户可以浏览其他用户的绘画作品，为他们点赞、评论、分享以及制作同款。
          </span>
        </div>
      </div>
    </div>
    <div class="image">
      <img :src="banner3" alt="banner3" />
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
