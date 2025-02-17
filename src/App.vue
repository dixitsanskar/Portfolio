<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import HeadBar from '@/views/Header.vue'
import Footer from '@/views/Footer.vue'
import Hero from './views/Hero.vue'
import NumSection from '@/views/Number.vue'
import Skill from './views/SkillView.vue'
import Project from './views/ProjectView.vue'
import TestimonialView from './views/TestimonialView.vue'
import ContactForm from './views/ContactForm.vue'
</script>

<template>
  <header><HeadBar/></header>
  <Hero />
  <NumSection />
  <Skill />
  <Project/>
  <TestimonialView/>
  <ContactForm/>
  <Footer></Footer>

</template>

<style scoped>

</style>
