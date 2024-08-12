<template>
    <div>
        <Navbar />
      <h1>Welcome to My Website</h1>
      <p>This is the home page.</p>
    </div>
  </template>
  
  <script>
import Navbar from '../components/navbar.vue';

  export default {
    name: 'HomePage',
    components: { Navbar }
};
  </script>
  
  <style scoped>
  /* Add your styles here */
  </style>
  