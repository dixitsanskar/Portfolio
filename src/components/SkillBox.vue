<script setup>
defineProps({
    sr:{
        type: Map,
        required: true,
    },
    heding:{
        type: String,
        required: true,
    },
    para:{
        type: String,
        required: true,
    }
})


</script>

<template>
    <div class="relative w-full h-[160px] text-left text-[14px] text-[#323433] font-inter">
      <div class="relative px-3 flex flex-col justify-evenly top-0 left-0 bg-white rounded-md shadow-[5px_0px_100px_rgba(247,247,247,0.5)] w-[255px] h-[160px]">
         <img class="relative    top-0 left-0 w-[28px] " alt="" :src="sr" />
      <div class="relative  w-[221px] ">
        <div class="relative font-bold  text-[20px] leading-[20px]  font-poppins text-black">{{heding}}</div>
        
       
      </div>
      <div class="relative  leading-[150%] w-[221px]">
          <p class="m-0">{{para}}</p>
        </div>
    </div>
    </div>
  </template>