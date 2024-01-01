<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/dashboard">Dashboard</RouterLink>
    </nav>
  </header>
  <main>
    <div class="cautious-hero">
      <p>Cautions Hero Midset!</p>
      <img src="@/assets/CautiousHero.webp" alt="Cautious Hero" />
    </div>
    <RouterView />
  </main>
  <footer></footer>
</template>

<style scoped>
header {
  position: sticky;
  top: 0;
  height: 10vh;
  padding: 10px;
  background-color: rgba(45, 137, 11, 0.2);
  backdrop-filter: blur(10px);
}
nav {
  a.router-link-active {
    font-size: 20px;
  }
}
.cautious-hero {
  img {
    width: 100%;
    height: 25vh;
    object-fit: contain;
  }
}
</style>
