<script setup>
defineProps({
    num:{
        type: String,
        required: true,
    },
    service:{
        type: String,
        required: true
    }
})
</script>
<template>
    <div class="parent  h-24  font-poppins">
      <div class="text-4xl font-semibold  text-yellow-400">{{num}}</div>
      <div class="mt-4 text-2xl leading-none text-white">{{service}}</div>
    </div>
  </template>