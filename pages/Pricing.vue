<template>
  <div class="min-h-screen flex flex-col pt-32">
    <Navbar />
    <div class="flex-grow">
      <div class="container mx-auto p-2 justify-center h-screen">
        <div class="grid md:px-48 grid-cols-2 md:gap-24">
          <div class="flex flex-col h-full bg-white rounded-3xl overflow-hidden shadow-lg transition duration-200 ease-in-out transform hover:scale-105">
            <div class="px-6 py-8 flex-grow">
              <h2 class="text-3xl font-semibold text-gray-800 mb-2 pl-2">Standard</h2>
              <p class="text-gray-600 mb-4 pl-2">More affordable but equally beautiful!</p>
              <div class="text-3xl font-bold text-gray-800 mb-8 pl-2">10-20€<span
                  class="text-lg font-normal text-gray-600 pl-2">/piece of jewelry</span></div>
              <ul class="text-gray-600 px-4">
                <li class="flex items-center mb-4 gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Silver, gold and mixed metal colorway
                </li>
                <li class="flex items-center mb-4 gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Jewelry made of titanium, stainless steel, gold plated stainless steel and zirconia
                </li>
                <li class="flex items-center mb-4 gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Personal consultation and advising
                </li>
                <li class="flex items-center gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Up to 3 custom sketches and ideas
                </li>
              </ul>
            </div>
            <div class="px-6 pb-8">
              <a href="/Contact" class="flex justify-center">
                <button
                  class="text-white font-semibold py-2 px-4 rounded-full bg-blue-500 transition duration-200 ease-in-out transform hover:scale-105">
                  Get Started
                </button>
              </a>
            </div>
          </div>

          <div class="bg-white rounded-3xl overflow-hidden shadow-lg transition duration-200 ease-in-out transform hover:scale-105">
            <div class="px-6 py-8">
              <h2 class="text-3xl font-semibold text-gray-800 mb-2 pl-2">Luxury</h2>
              <p class="text-gray-600 mb-4 pl-2">High quallity jewelry pieces!</p>
              <div class="text-3xl font-bold text-gray-800 mb-8 pl-2">20-150€<span
                  class="text-lg font-normal text-gray-600 pl-2">/piece of jewelry</span></div>
              <ul class="text-gray-600 px-4">
                <li class="flex items-center mb-4 gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Silver, gold and mixed metal colorway
                </li>
                <li class="flex items-center mb-4 gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Jewelry made of titanium, stainless steel, gold plated stainless steel, zirconia + sterling silver 925, 14K gold and precious stones
                </li>
                <li class="flex items-center mb-4 gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Personal consultation and advising
                </li>
                <li class="flex items-center gap-4">
                  <img src="~/assets/check.png" class="w-4 h-4">
                  Unlimited number of custom sketches and ideas
                </li>
              </ul>
              <div class="flex justify-center">
                <a href="/Contact">
                  <button class="mt-10 text-white font-semibold py-2 px-4 rounded-full transition duration-200 ease-in-out transform hover:scale-105">
                    Get Started
                  </button>
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="flex flex-col justify-center mt-10">
          <p class="text-center text-gray-600">Please have in mind that there is a deposit of 30€ before the first sketch is made. That amount will be deducted from the final price.</p>
          <p class="text-center text-gray-600">You are welcome to change the pricing option at any time or to request pieces from the other category of jewelry.</p>
          <p class="text-center text-gray-600">If you have any questions about the pricing, feel free to contact us.</p>
        </div>
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
  