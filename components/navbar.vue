<template>
    <header class="lg:px-16 px-4 bg-white flex flex-wrap items-center py-4 shadow-md">
        <div class="flex-1 flex justify-between items-center">
      
      <nuxt-link to="/" class="custom-shadow text-xl text-gray-100 flex items-center" style="color: rgb(60, 60, 60);">
        <img src="~/assets/ear_logo.webp" alt="Logo" style="height: 50px; width: 50px;" class="h-8 w-8 mr-2" />
        Ear Curations
      </nuxt-link>
    </div>
  
      <!-- Hamburger button -->
      <button @click="toggleMenu" class="md:hidden block text-gray-900">
        <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20">
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
        </svg>
      </button>
  
      <!-- Navbar links -->
      <div :class="isMenuOpen ? 'block' : 'hidden'" class="md:flex md:items-center md:w-auto w-full">
        <nav>
          <ul class="md:flex items-center justify-between text-base text-gray-700 pt-4 md:pt-0">
            <li><NuxtLink to="/" class="nav-link md:p-4 py-3 px-0 block">Home</NuxtLink></li>
            <li><NuxtLink to="/gallery" class="nav-link md:p-4 py-3 px-0 block">Gallery</NuxtLink></li>
            <li><NuxtLink to="/pricing" class="nav-link md:p-4 py-3 px-0 block">Pricing</NuxtLink></li>
            <li><NuxtLink to="/contact" class="nav-link md:p-4 py-3 px-0 block md:mb-0 mb-2">Contact Us</NuxtLink></li>
          </ul>
        </nav>
      </div>
    </header>
</template>
  
<script>
  export default {
    data() {
      return {
        isMenuOpen: false,
      };
    },
    methods: {
      toggleMenu() {
        this.isMenuOpen = !this.isMenuOpen;
      },
    },
  };
</script>
  
<style scoped>
.router-link-exact-active{
    color: indianred;
}
.custom-shadow {
    text-shadow: 1px 0px 1px rgba(0, 0, 0, 0.3);
  }
</style>
  