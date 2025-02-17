<script setup>
import { onMounted, ref } from "vue";

const carouselRef = ref(null);

const loadScript = (src) => {
  return new Promise((resolve, reject) => {
    const script = document.createElement("script");
    script.src = src;
    script.async = true;
    script.onload = resolve;
    script.onerror = reject;
    document.head.appendChild(script);
  });
};

onMounted(async () => {
  try {
    await loadScript("https://code.jquery.com/jquery-3.4.1.min.js");
    await loadScript("https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js");

    $(carouselRef.value).owlCarousel({
      loop: true,
      margin: 0,
      responsiveClass: true,
      autoplay: true,
      responsive: {
        0: {
          items: 1,
          nav: true,
        },
        600: {
          items: 2,
          nav: false,
        },
        1000: {
          items: 3,
          nav: false,
        },
      },
    });
  } catch (error) {
    console.error("Failed to load scripts:", error);
  }
});
</script>

<template>
  <div style="padding: 30px 0; background-color: transparent;">
    <div class="container">
      <div style="text-align: center;">
        <div ref="carouselRef" class="carousel-testimonial owl-carousel">
          <div class="item" style="padding: 30px 10px;">
            <div class="testimonial-content">
              <p>Picked up heels for dancing. They are incredible...</p>
              <p class="name">Neha Sharma</p>
            </div>
          </div>
          <div class="item" style="padding: 30px 10px;">
            <div class="testimonial-content">
              <p>I love the quality and comfort of the Natya collection...</p>
              <p class="name">Rahul Verma</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css');
@import url('https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css');
@import url('https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css');

.testimonial-content {
  background: #fff;
  padding: 30px;
  border: 1px solid rgba(0,0,0,.03);
  border-radius: 5px;
  box-shadow: 0 0 20px rgba(0, 0, 0, .08);
  text-align: left;
}

.name {
  font-weight: bold;
  color: #453232;
  margin-top: 1rem;
}
</style>
