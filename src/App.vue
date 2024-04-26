<template>
  <left-nav class="left-nav"></left-nav>
  <top-nav class="top-nav"></top-nav>
  <div class="view-wrapper">
    <router-view class="view" />
  </div>
</template>

<script setup lang="ts">
import LeftNav from "./components/LeftNav.vue";
import TopNav from "./components/TopNav.vue";
</script>

<style scoped>
.top-nav {
  z-index: 8888;
}
.left-nav {
  z-index: 7777;
}
.view-wrapper {
  margin-left: 275px;
}
.view {
  margin-top: 50px;
}
</style>
