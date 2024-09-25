<script >
export default {
  methods: {
    resume(){
      window.open("https://drive.google.com/file/d/1KdMOnaznK40WbPFDbsWFkzWJhK24YdtZ/view?usp=drive_link", "_blank", 'noopener,noreferrer');

    }
  }
}
</script>
<template>
        <header class="d-flex flex-wrap justify-content-between py-3 mb-4">
      <a href="/" class="d-flex align-items-center mb-3 mb-md-0 link-body-emphasis text-decoration-none">
        <img class="mt-[-2rem]"src="@/assets/slogo.png" height="105px" width="105px">
      </a>

      <ul class="nav nav-pills flex justify-between">
        <li class="nav-item"><a href="#" class="nav-link" aria-current="page">About</a></li>
        <li class="nav-item"><a href="#" class="nav-link">Skills</a></li>
        <li class="nav-item"><a href="#" class="nav-link">Portfolio</a></li>
        <li class="nav-item"><a href="#" class="nav-link">Testimonial</a></li>
      </ul>

      <ul class="nav nav-pills">
      
      <li class="nav-item"><button class="nav-link active bg-transparent !text-[#ffd22f] !border-[#ffd22f] border " :onclick="resume"> Download Resume</button></li>

      </ul>

      
    </header>
    
</template>
<style scoped>
.nav-link{
  color:white;
}
</style>
