<script setup lang="ts">
import { RouterView } from "vue-router";
import NavBar from "@/components/NavBar.vue";

document.body.style.background = "#1F2937";
</script>

<template>
  <div class="font-mono">
    <NavBar />
    <RouterView />
  </div>
</template>

<style scoped>
nav {
  display: inline;
}
</style>
