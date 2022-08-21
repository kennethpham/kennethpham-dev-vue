<script setup lang="ts">
import { RouterView } from "vue-router";
import Navbar from "@/components/Navbar.vue";

document.body.style.background = "#1F2937";
</script>

<template>
  <div class="font-mono">
    <Navbar />
    <RouterView />
  </div>
</template>

<style scoped>
nav {
  display: inline;
}
</style>
