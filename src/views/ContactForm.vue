  
<script setup>
import heads from '@/components/Heading.vue'
import TestimonialSlider from '@/components/TestimonialSlider.vue'
</script>

<template>
   <div class="relative flex flex-col justify-items-center align-middle mt-10  text-left font-inter text-black">
      <div class=" flex flex-row">
        <div class="container flex flex-col pt-[100px]">
            <heads msg="Contact" />
       
        <div class="relative text-[58px] mt-3 leading-[70px] text-white text-center">
          <p class="m-0">
            <span class="font-semibold">Our Customer Say 
                </span>              <span class="font-inter text-[#ffd330] font-semibold"> About Us?</span></p>
        </div>
        </div>
       
        
      </div>
      <TestimonialSlider class="" />
    </div>
  </template>

  <style scoped>
  .msgparent[data-v-d60ddbeb]{
    display: flex
;
    width: fit-content;
    align-self: anchor-center;
  }
  </style>
  