<script setup lang="ts">
import { onMounted } from "vue";
onMounted(() => {
  document.title = "Kenneth's Personal Site";
});
</script>

<template>
  <main class="bg-gray-800">
    <div class="flex justify-center pt-20">
      <h1 class="text-3xl text-white font-bold">Kenneth Pham</h1>
    </div>
    <div class="flex text-white justify-center p-4">
      Welcome to my Personal Site!
    </div>
    <div class="flex text-white justify-center px-5 pb-4">About me:</div>
    <div class="flex justify-center px-5">
      <p class="text-white">
        I graduated from UCSD in 2020 and am currently working as a Jr.
        Software Engineer at
        <a class="hover:bg-gray-600" href="https://www.moesol.com/">
          Moebius Solutions, Inc.
        </a>
      </p>
    </div>
    <div class="flex justify-center px-5">
      <p class="text-white">
        This site is to show off and host any personal projects that I have
        done.
      </p>
    </div>
  </main>
</template>
