<template>
    <div class="min-h-screen flex flex-col pt-32">
        <Navbar />
   
        <div class="min-h-screen">
          <div class="container mx-auto p-8 justify-center">
            <div class="grid px-32 md:grid-cols-5 gap-12">
              <!-- Left column -->
              <div class="bg-white md:col-span-3 p-8 rounded-lg shadow-lg">
                <h2 class="font-semibold text-center text-2xl pt-4 pb-1">Ready for your curation?</h2>
                <p class="text-sm text-center pb-8">Fill out the form and we'll contact you!</p>
                
                <form action="#" method="POST">
                  <div class="grid grid-cols-1 md:grid-cols-2 gap-4 px-8">
                    <div class="mb-2">
                      <label for="firstName" class="block text-xs font-medium text-gray-700">FIRST NAME</label>
                      <input type="text" id="firstName" name="firstName" class="mt-1 block w-full px-3 py-2 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="First name">
                    </div>
                    <div class="mb-4">
                      <label for="lastName" class="block text-xs font-medium text-gray-700">LAST NAME</label>
                      <input type="text" id="lastName" name="lastName" class="mt-1 block w-full px-3 py-2 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="Last name">
                    </div>
                  </div>
                  <div class="mb-4 px-8">
                    <label for="email" class="block text-xs font-medium text-gray-700">E-MAIL</label>
                    <input type="email" id="email" name="email" class="mt-1 block w-full px-3 py-2 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="Your e-mail adress">
                  </div>
                  <div class="mb-4 px-8">
                    <label for="number" class="block text-xs font-medium text-gray-700">PHONE NUMBER</label>
                    <input id="number" name="number" class="mt-1 block w-full px-3 py-2 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="Your phone number">
                  </div>
                  <div class="grid md:grid-cols-3 flex justify-between px-8 py-2 gap-8">
                    <div class="flex flex-col col-span-2 gap-4">
                      <p class="text-xs font-medium text-gray-700 mr-4">PREFERRED METHOD OF COMMUNICATION:</p>
                      <div class="flex flex-col justify-center mx-4">
                        <div class="flex items-center mb-2 ">
                          <input type="radio" id="contactEmail" name="preferredContact" value="email" class="focus:ring-gray-500 h-4 w-4 text-gray-600 border-gray-300">
                          <label for="contactEmail" class="ml-3 text-sm font-medium text-gray-700">
                            E-mail
                          </label>
                        </div>
                        <div class="flex items-center">
                          <input type="radio" id="contactPhone" name="preferredContact" value="phone" class="focus:ring-gray-500 h-4 w-4 text-gray-600 border-gray-300">
                          <label for="contactPhone" class="ml-3 text-sm font-medium text-gray-700">
                            Phone
                          </label>
                        </div>
                      </div>
                    </div>
                    <div class="flex flex-col gap-4 col-span-1">
                      <p class="text-xs font-medium text-gray-700">PRICING OPTION:</p>
                      <div class="flex flex-col justify-center mx-4">
                        <div class="flex items-center mb-2">
                          <input type="radio" id="standardPricing" name="pricingOption" value="standard" class="focus:ring-gray-500 h-4 w-4 text-gray-600 border-gray-300">
                          <label for="standardPricing" class="ml-3 text-sm font-medium text-gray-700">
                            Standard
                          </label>
                        </div>
                        <div class="flex items-center">
                          <input type="radio" id="luxuryPricing" name="pricingOption" value="luxury" class="focus:ring-gray-500 h-4 w-4 text-gray-600 border-gray-300">
                          <label for="luxuryPricing" class="ml-3 text-sm font-medium text-gray-700">
                            Luxury
                          </label>
                        </div>
                      </div>
                    </div>
                  </div>
                  
                  <div class="mt-8 mb-2">
                    <div class="flex justify-center">
                      <button type="submit" class="text-white font-semibold py-2 px-6 rounded-lg transition duration-300 ease-in-out transform hover:scale-105">Submit</button>
                    </div>
                  </div>
                </form>
              </div>

              <!-- Right column -->
              <div class="bg-white md:col-span-2 p-4 rounded-lg shadow-lg text-center">
                <h2 class="font-semibold text-xl mt-8 mb-16">Contact information</h2>
                <div class="flex flex-col justify-center">
                  <p class="text-md px-4">Have any questions for us?</p>
                  <p class="text-md px-4 pb-8">Send them our way through e-mail or give us a call during our working hours!</p>
                  <div class="flex flex-col justify-between p-4">
                    <div class="flex flex-row items-center p-4">
                      <img src="~/assets/mail.png" alt="Mail" style="height: 20px; width: 20px;" />
                      <span class="ml-4">earcurations@gmail.com</span>
                    </div>
                    <div class="flex flex-row items-center p-4">
                      <img src="~/assets/phone.png" alt="Phone" style="height: 20px; width: 20px;" />
                      <span class="ml-4">+123 456 789</span>
                    </div>
                    <div class="flex flex-row items-center p-4">
                      <img src="~/assets/clock.png" alt="Hours" style="height: 20px; width: 20px;" />
                      <span class="ml-4">Mon - Fri: 8:00 - 16:00</span>
                    </div>
                  </div>
                </div>
              </div>
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
  