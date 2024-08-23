<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import HeadBar from '@/views/Header.vue'
import Footer from '@/views/Footer.vue'
import Hero from './views/HeadBanner.vue'
</script>

<template>
  <header><HeadBar/></header>
  <Hero />
  <Footer></Footer>
</template>

<style scoped>

</style>
