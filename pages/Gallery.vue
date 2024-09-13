<template>
    <div class="min-h-screen flex flex-col pt-32">
        <div class="flex-grow">  
            <Navbar />
            <h1 class="text-xl md:text-xl lg:text-3xl text-center text-gray-700 my-8">These are some of our previous works!</h1>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-3 md:gap-6 gap-y-8 md:gap-y-16 py-6 md:py-16 px-2 md:px-48">

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
            <Gallery_card :imageFolder="'carousel1'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
                <Gallery_card :imageFolder="'carousel2'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
                <Gallery_card :imageFolder="'carousel3'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
                <Gallery_card :imageFolder="'carousel4'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
            <Gallery_card :imageFolder="'carousel5'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
                <Gallery_card :imageFolder="'carousel6'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
                <Gallery_card :imageFolder="'carousel7'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
                <Gallery_card :imageFolder="'carousel8'" />
            </div>

            <div class="p-1 md:p-4 sm:w-1/2 md:w-full mx-auto">
                <Gallery_card :imageFolder="'carousel9'" />
            </div>

        </div>
      <Footer />
    </div>
</template>
  
<script>
   
</script>
  
<style scoped>
    
</style>
  