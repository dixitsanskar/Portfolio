  
<script setup>
import heads from '@/components/Heading.vue'
import TestimonialSlider from '@/components/TestimonialSlider.vue'
</script>

<template>
   <div class="relative flex flex-col justify-items-center align-middle mt-10  text-left font-inter text-black">
      <div class=" flex flex-row">
        <div class="container flex flex-col  pt-[100px]">
            <heads msg="Reviews"/>
       
        <div class="relative text-[58px] mt-3 leading-[70px] text-white">
          <p class="m-0">
            <span class="font-semibold">Our Customer Say 
                </span>
          </p>
          <p class="m-0">
            <span class="tracking-[-0.01em]">
              <b>Something</b>
              <span class="font-inter text-[#ffd330] font-semibold"> About Us?</span>
            </span>
          </p>
        </div>
        </div>
       
        
      </div>
      <TestimonialSlider class="" />
    </div>
  </template>

  <style scoped></style>
  