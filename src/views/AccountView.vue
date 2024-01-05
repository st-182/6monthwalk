<script setup lang="ts">
import { ref, onMounted } from 'vue'
const courses: string[] = ['Freshlife28', 'random1']

const el = ref()

onMounted(() => {
  el.value // <div>
})
</script>

<template>
  <main>
    <p>Hi, this is your account!</p>

    <NutritionFactsGPT />
    <div class=""></div>
    registered from started {{ courses[0] }}
  </main>
</template>
