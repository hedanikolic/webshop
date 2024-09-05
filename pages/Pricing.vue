<template>
  <div class="min-h-screen flex flex-col pt-24 lg:pt-32">
    <Navbar />
    <div class="min-h-screen">
      <div class="container mx-auto p-4 justify-center">
        <div class="grid gap-8 xs:px-24 md:px-12 xl:px-48 md:gap-12 md:grid-cols-2">
          <div class="flex flex-col h-full bg-white rounded-2xl overflow-hidden shadow-lg transition duration-200 ease-in-out transform hover:scale-105">
            <div class="px-4 py-6">
              <h2 class="text-2xl font-semibold text-gray-800 mb-2 pl-2">Standard</h2>
              <p class="text-gray-600 mb-4 pl-2 text-sm">More affordable but equally beautiful!</p> 
              <div class="text-2xl font-semibold text-gray-800 mb-8 pl-2">10-20€<span
                  class="text-base font-normal text-gray-600 pl-2">/piece of jewelry</span></div>
              <ul class="text-gray-600 text-md px-2">
                <li class="flex items-center mb-3 gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Silver, gold and mixed metal colorway
                </li>
                <li class="flex items-center mb-3 gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Jewelry made of titanium, stainless steel, gold plated stainless steel and zirconia
                </li>
                <li class="flex items-center mb-3 gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Personal consultation and advising
                </li>
                <li class="flex items-center gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Up to 3 custom sketches and ideas
                </li>
              </ul>
            </div>
            <div class="mt-auto px-4 pb-6">
              <a href="/Contact" class="flex justify-center">
                <button
                  class="text-white font-semibold py-2 px-3 rounded-full bg-blue-500 transition duration-200 ease-in-out transform hover:scale-105">
                  Get Started
                </button>
              </a>
            </div>
          </div>

          <div class="bg-white rounded-2xl overflow-hidden shadow-lg transition duration-200 ease-in-out transform hover:scale-105">
            <div class="px-4 py-6">
              <h2 class="text-2xl font-semibold text-gray-800 mb-2 pl-2">Luxury</h2>
              <p class="text-gray-600 mb-4 pl-2 text-sm">High quallity jewelry pieces!</p>
              <div class="text-2xl font-semibold text-gray-800 mb-8 pl-2">20-150€<span
                  class="text-base font-normal text-gray-600 pl-2">/piece of jewelry</span></div>
              <ul class="text-gray-600 text-md px-2">
                <li class="flex items-center mb-3 gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Silver, gold and mixed metal colorway
                </li>
                <li class="flex items-center mb-3 gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Jewelry made of titanium, stainless steel, gold plated stainless steel, zirconia + sterling silver 925, 14K gold and precious stones
                </li>
                <li class="flex items-center mb-3 gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Personal consultation and advising
                </li>
                <li class="flex items-center gap-2">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Unlimited number of custom sketches and ideas
                </li>
              </ul>
              <div class="flex mt-auto justify-center">
                <a href="/Contact">
                  <button class="flex justify-end mt-8 text-white font-semibold py-2 px-3 rounded-full transition duration-200 ease-in-out transform hover:scale-105">
                    Get Started
                  </button>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-col justify-center pb-10 px-8 md:pt-2 lg:pt-8">
      <p class="text-center text-gray-600">Please have in mind that there is a deposit of 30€ before the first sketch is made. That amount will be deducted from the final price.</p>
      <p class="text-center text-gray-600 text-md">You are welcome to change the pricing option at any time or to request pieces from the other category of jewelry.</p>
      <p class="text-center text-gray-600 text-md">If you have any questions about the pricing, feel free to contact us.</p>
    </div>

    </div>
    
    <Footer />
  </div>
</template>

  
<script>

</script>
  
<style scoped>
button{
      background-color: indianred;
    }
    button:hover{
      background-color: #bf4e4e;
    }
</style>
  