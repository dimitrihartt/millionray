<script setup lang="ts">
</script>

<template>
  <div>
    <a href="https://millionray.com" target="_blank">
      <img src="../assets/MillionRay.png" class="logo" alt="MillionRay logo" />      
    </a>
    <a href="https://vite.dev" target="_blank">
      <img src="../../public/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="../assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <a href="https://meta.com/" target="_blank">
      <img src="../assets/meta-logo.svg" class="logo vue"  alt="Meta logo" />
    </a>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>