<script setup>
import heads from "@/components/Heading.vue"
</script>
<!-- <template>
    <div class="textgrp">
        <heads msg="Welcome"/>
    </div>
    <div class="wrapper">
  <div class="static-txt">I'm a</div>
  <ul class="dynamic-txts">
    <li><span>App Developer</span></li>
    <li><span>Shopify Developer</span></li>
    <li><span>Wordpress Developer</span></li>
    <li><span>Product Manager</span></li>
    <li><span>Backend Developer</span></li>
  </ul>
</div>

</template> -->


<template>
    <div class="relative flex flex-row justify-between  w-full h-[652px] text-left font-inter text-black">
      <div class=" flex flex-row">
        <div class="container flex flex-column  pt-[100px]">
            <heads msg="Welcome"/>
        <!-- <div class="absolute top-[320px] left-[167px] font-medium leading-[150%]">View Portfolio</div> -->
        <!-- <img class="absolute top-[315px] left-[275.19px] w-[33.6px] h-[33.6px] object-contain" alt="" src="Frame.png" /> -->
        <div class="relative text-[58px] mt-3 leading-[70px] text-[#ffd330]">
          <p class="m-0">
            <span class="font-semibold">I have</span>
            <span> App</span>
          </p>
          <p class="m-0">
            <span class="tracking-[-0.01em]">
              <b>Developer</b>
              <span class="font-inter text-white font-semibold"> Experience</span>
            </span>
          </p>
        </div>
        <div class="relative mt-6 leading-[150%] text-white inline-block w-[540px]">
          <p class="m-0">I’m Tanvir, a creative Product Designer. I’ve been helping businesses</p>
          <p class="m-0">to solve their problems with my design for 2 years.</p>
        </div>
        <div class="relative mt-10  w-[138px] h-[56px] text-center">
          <!-- <img class="absolute top-0 left-0 w-[138px] h-[56px] rounded-lg" alt="" src="Rectangle 2023.svg" /> -->
          <a class="!justify-start hover:no-underline" href=""><div class="font-semibold bg-[#ffd330] rounded-[12px] px-4 py-3 leading-[150%]">Contact Me</div></a>
        </div>
        </div>
        <!-- <div class="absolute top-0 left-0 w-[99px] h-[42px] text-[20px] text-[#ffd330]">
          <div class="absolute top-[6px] left-[5px] font-medium leading-[145%]">Welcome</div>
          <div class="absolute top-0 left-0 w-[99px] h-[42px] rounded-full border border-[#ffd330] box-border"></div>
        </div> -->
        
      </div>
      <div class="relative pt-[60px] ">
        <div class="relative top-0  w-[602px] h-[652px]">
        <div class="absolute  left-[41px] w-[420px] h-[420px] bg-[#ffd330] rounded-[2px]"></div>
        <div class="absolute top-[60px] left-0 w-[406px] h-[406px] border-[5px] border-white box-border rounded-[2px]"></div>
      </div>
      </div>
      <div class="relative flex flex-col  pt-[100px]  pl-5 text-[#fccc1c]">
        <div class="relative transform rotate-90 right-7 ">Follow me on:</div>
        <div class="mt-[70px] h-[64.5px] ml-3 border-l border-white box-border"></div>
        <div class="flex flex-column justify-between  mt-5">
          <a href="" class="!justify-start"><img class="overflow-hidden mt-2"  width="24px" alt="" src="@/assets/twitter.svg" /></a>
        <a href="" class="!justify-start"><img class="overflow-hidden mt-2" width="24px" alt="" src=" @/assets/instagram.svg " /></a>
        <a href="" class="!justify-start"><img class="overflow-hidden mt-2" width="24px" alt="" src="@/assets/linkedin.svg "/></a>
        </div>

      </div>
    </div>
  </template>
  


<style>
@import url("https://fonts.googleapis.com/css2?family=Mukta:wght@400;500;600;700;800&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Mukta", sans-serif;
}


.wrapper {
  display: flex;
}

.wrapper .static-txt {
  color: #ffffff;
  font-size: 3.75rem;
  font-weight: 400;
}

.wrapper .dynamic-txts {
  margin-left: 15px;
  height: 90px;
  line-height: 90px;
  overflow: hidden;
}

.dynamic-txts li {
  list-style: none;
  color: #ffd330;
  font-size: 60px;
  font-weight: 500;
  position: relative;
  top: 0;
  animation: slide 12s steps(4) infinite;
}

@keyframes slide {
  100% {
    top: -360px;
  }
}

.dynamic-txts li span {
  position: relative;
  margin: 5px 0;
  line-height: 90px;
}

.dynamic-txts li span::after {
  content: "";
  position: absolute;
  left: 0;
  height: 100%;
  width: 100%;
  background: #181818;
  border-left: 2px solid #ffd330;
  animation: typing 3s steps(10) infinite;
}

@keyframes typing {
  40%,
  60% {
    left: calc(100% + 30px);
  }

  100% {
    left: 0;
  }
}


/* Support me */
.links {
  position: fixed;
  bottom: 10px;
  right: 10px;
  font-weight: 600;
  font-size: 1.2em;
  border-radius: 15px;
  background-color: white;
  padding: 5px;
  line-height: 1.3;
  border: 5px black;
  border-style: groove;
}

a {
  text-decoration: none;
  color: black;
  display: flex;
  align-items: center;
  justify-content: center;
}

a:hover {
  text-decoration: underline;
}

a img.icon {
  display: inline-block;
  margin-left: 0.4rem;
  height: 40px;
}

</style>