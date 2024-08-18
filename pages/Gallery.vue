<template>
    <div class="min-h-screen flex flex-col">
        <div class="flex-grow">  
            <Navbar />
            <h1 class="text-xl md:text-xl lg:text-3xl text-center my-8">These are some of our previous works!</h1>
        </div>
        <div class="grid grid-cols-2 md:grid-cols-3 gap-3 md:gap-6 py-6 px-2 md:px-48">

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
      <Gallery_card :imageFolder="carousel2" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
        <Gallery_card :imageFolder="carousel2" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
        <Gallery_card :imageFolder="carousel3" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
        <Gallery_card :imageFolder="carousel4" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
       <Gallery_card :imageFolder="carousel5" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
        <Gallery_card :imageFolder="carousel6" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
        <Gallery_card :imageFolder="carousel7" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
        <Gallery_card :imageFolder="carousel8" />
    </div>

    <div class="bg-gray-200 p-2 md:p-4 rounded shadow">
        <Gallery_card :imageFolder="carousel9" />
    </div>

  </div>
      <Footer />
    </div>
  </template>
  
  <script>


  </script>
  
  <style scoped>
  </style>
  