<template>
    <div class="max-w-xs mx-auto">
      <div @click="openCarousel" class="cursor-pointer">
        <img src="assets/gallery11.jpeg" alt="Product Image" class="w-full h-full object-cover rounded-lg shadow-lg">
        <h2 class="mt-4 text-lg font-semibold text-center">Title</h2>
      </div>
  
      <!-- Carousel modal -->
      <div v-if="isCarouselOpen" class="fixed inset-0 flex items-center justify-center bg-black bg-opacity-50 z-50" @click="closeCarousel">
        <div class="bg-gray-200 p-4 rounded-lg shadow-lg" @click.stop>
            <Carousel />
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
};
</script>