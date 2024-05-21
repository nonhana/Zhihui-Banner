<script setup lang="ts">
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import Feature1 from "./components/Feature1.vue";
import Feature2 from "./components/Feature2.vue";
import Welcome from "./components/Welcome.vue";
import Info from "./components/Info.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="app-wrapper">
    <Header />
    <Banner />
    <Feature1 />
    <Feature2 />
    <Welcome />
    <Info />
    <Footer />
  </div>
</template>

<style scoped lang="scss">
.app-wrapper {
  position: relative;
  width: 100%;
}
</style>
