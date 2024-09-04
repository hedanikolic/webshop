<template>
    <div class="carousel relative w-full max-w-md mx-auto overflow-hidden rounded-lg">
      <div class="slides flex transition-transform duration-500 ease-in-out" :style="{ transform: `translateX(-${currentIndex * 100}%)` }">
        <div class="slide flex-shrink-0 w-full">
            <img :src="`../_nuxt/assets/${carouselFolder}/before.jpeg`" class="w-full object-contain" alt="Before" />
        </div>
        <div class="slide flex-shrink-0 w-full">
            <img :src="`../_nuxt/assets/${carouselFolder}/sketch.jpeg`" class="w-full object-contain" alt="Sketch" />
        </div>
        <div class="slide flex-shrink-0 w-full">
            <img :src="`../_nuxt/assets/${carouselFolder}/after.jpeg`" class="w-full object-contain" alt="After" />
        </div>
      </div>
  
      <!-- Left arrow -->
      <button 
        v-if="currentIndex > 0" 
        @click="prevSlide" 
        class="absolute top-1/2 left-1 transform -translate-y-1/2 bg-gray-500 bg-opacity-50 hover:bg-opacity-75 text-white p-2 rounded-full">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"></path>
        </svg>
      </button>
  
      <!-- Right arrow -->
      <button 
        v-if="currentIndex < totalSlides - 1" 
        @click="nextSlide" 
        class="absolute top-1/2 right-2 transform -translate-y-1/2 bg-gray-500 bg-opacity-50 hover:bg-opacity-75 text-white p-2 rounded-full">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
        </svg>
      </button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        currentIndex: 0,
      };
    },
    methods: {
      prevSlide() {
        this.currentIndex = (this.currentIndex > 0) ? this.currentIndex - 1 : this.totalSlides - 1;
      },
      nextSlide() {
        this.currentIndex = (this.currentIndex < this.totalSlides - 1) ? this.currentIndex + 1 : 0;
      },
    },
    computed: {
      totalSlides() {
        return 3;
      },
    },
    props: {
        carouselFolder: {
        type: String,
        default: ''
        },
    },
  };
  </script>
  
  <style scoped>
  .carousel {
    
  }
  
  .slides {
    display: flex;
    width: 100%;
  }
  
  .slide {
    width: 100%;
    height: 300px;
  }
  
  img {
    max-width: 100%;
    height: 300px;
    display: block;
  }
  </style>
  