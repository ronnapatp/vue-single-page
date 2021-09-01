<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
<main class="w-full h-screen flex flex-col justify-center items-center">
  <h1 class="text-6xl text-green-400 flex flex-col">
    <span>Single</span><span>Vue</span><span>Page</span>
  </h1>

  
</main>
</template>

