<template>
    <div class="max-w-xs mx-auto">
      <div @click="openCarousel" class="cursor-pointer">
        <img :src="`../_nuxt/assets/${imageFolder}/after.jpeg`" alt="Curation" class="w-full h-full object-cover rounded-lg shadow-2xl">
      </div>
      <!-- Carousel modal -->
      <div v-if="isCarouselOpen" class="fixed inset-0 flex items-center justify-center bg-black bg-opacity-50 z-50" @click="closeCarousel">
        <div class="bg-gray-200 p-4 rounded-lg shadow-2xl" @click.stop>
            <Carousel :carouselFolder= imageFolder />
        </div>
        </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      isCarouselOpen: false,
    };
  },
  methods: {
    openCarousel() {
      this.isCarouselOpen = true;
    },
    closeCarousel() {
      this.isCarouselOpen = false;
    },
  },
  props: {
    imageFolder: {
        type: String,
        default: ''
    },
  },
  mounted() {
    console.log(this.imageSrc); // This will log the path to the console when the component mounts
  }
};
</script>