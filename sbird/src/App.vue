<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
// import HelloWorld from './components/HelloWorld.vue'
import Sidebar from "./components/Sidebar.vue";
import Content from "./components/Content.vue";
</script>

<template>
<div class="container">
  <Sidebar type="user" />
  <Content />
  <Sidebar type="trends" />
</div>
</template>

<style lang="scss" scoped>
.container {
  display: flex;
}
</style>
