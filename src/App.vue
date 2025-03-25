<script setup lang="ts">
import About from './components/About.vue';
import Experience from './components/Experience.vue';
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'

</script>

<template>
  <div class="w-full flex flex-col h-screen  bg-black text-white pt-20 ">
    <Header />
    <Hero />
    <About />
    <Experience />
    <div>home page</div>
  </div>
</template>
