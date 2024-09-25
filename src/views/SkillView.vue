<script setup>
import heads from "@/components/Heading.vue"
import sbox from "@/components/SkillBox.vue"
</script>

<template>
    <div class="relative flex flex-row justify-items-center align-middle mt-10  text-left font-inter text-black">
      <div class=" flex flex-row">
        <div class="container flex flex-col  pt-[100px]">
            <heads msg="My Skills"/>
       
        <div class="relative text-[58px] mt-3 leading-[70px] text-[#ffd330]">
          <p class="m-0">
            <span class="font-semibold">Why Hire Me For Your</span>
          </p>
          <p class="m-0">
            <span class="tracking-[-0.01em]">
              <b>Next</b>
              <span class="font-inter text-white font-semibold"> Project?</span>
            </span>
          </p>
        </div>
        <div class="relative mt-6 leading-[150%] text-white inline-block w-[540px]">
          <p class="m-0">I’m specialist in UI/UX Designe. My passion is designing & solving </p>
          <p class="m-0">problems through user experience and research.</p>
        </div>
        <div class="relative mt-10  w-[138px] h-[56px] text-center">
          <a class="!justify-start hover:no-underline" href=""><div class="font-semibold bg-[#ffd330] rounded-[12px] px-4 py-3 leading-[150%]">Hire Me</div></a>
        </div>
        </div>
       
        
      </div>
      <div class="flex justify-between px-20 pt-28 gap-5 ">
        <div class="flex flex-col justify-between gap-4  ">
          <sbox  heding="App Development" para=" sdfksdnfjk nfdsjfjnf nfdjsdfn fudf " sr="src/assets/flutter.svg" />
      <sbox  heding="CMS" para=" sdfksdnfjk nfdsjfjnf nfdjsdfn fudf " sr="src/assets/flutter.svg" />
        </div>

        <div class=" flex flex-col pt-20 ">   
      <sbox class="" heding="Web Development" para=" sdfksdnfjk nfdsjfjnf nfdjsdfn fudf " sr="src/assets/flutter.svg" />
        </div>
       
     
      </div>
    </div>
  </template>
  

