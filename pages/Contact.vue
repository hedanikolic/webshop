<template>
    <div class="min-h-screen flex flex-col pt-32">
        <Navbar />
   
        <div class="min-h-screen">
          <!-- Container for the entire contact page -->
          <div class="container mx-auto p-4 justify-center">
            <!-- Grid layout that changes based on screen size -->
            <div class="grid px-32 md:grid-cols-3 gap-8">
              <!-- Left column content -->
              <div class="bg-gray-100 md:col-span-2 p-8 rounded shadow">
                <h2 class="font-semibold text-center text-2xl pt-4 pb-1">Ready for your curation?</h2>
                <p class="text-sm text-center pb-8">Fill out the form and we'll contact you!</p>
                <!-- Example form -->
                <form action="#" method="POST">
                  <div class="grid grid-cols-1 md:grid-cols-2 gap-4 px-16 py-2">
                    <div class="mb-4">
                      <label for="firstName" class="block text-xs font-medium text-gray-700">FIRST NAME</label>
                      <input type="text" id="firstName" name="firstName" class="mt-1 block w-full px-3 py-3 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="First name">
                    </div>
                    <div class="mb-4">
                      <label for="lastName" class="block text-xs font-medium text-gray-700">LAST NAME</label>
                      <input type="text" id="lastName" name="lastName" class="mt-1 block w-full px-3 py-3 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="Last name">
                    </div>
                  </div>
                  <div class="mb-4 px-16 py-2">
                    <label for="email" class="block text-xs font-medium text-gray-700">E-MAIL</label>
                    <input type="email" id="email" name="email" class="mt-1 block w-full px-3 py-3 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="Your e-mail adress">
                  </div>
                  <div class="mb-4 px-16 py-2">
                    <label for="number" class="block text-xs font-medium text-gray-700">PHONE NUMBER</label>
                    <input id="number" name="number" class="mt-1 block w-full px-3 py-3 bg-white border shadow-sm border-gray-300 rounded-md focus:outline-none focus:ring-gray-900 focus:border-gray-900 sm:text-sm" placeholder="Your phone number">
                  </div>
                  <div class="px-16 py-2">
                    <div class="flex">
                      <p class="text-xs font-medium text-gray-700 mr-4">PREFERRED METHOD OF COMMUNICATION:</p>
                      <div class="flex flex-col justify-center ml-10">
                        <div class="flex items-center mb-2">
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
                  </div>
                  <div class="mb-4 px-8 pt-4">
                    <div class="flex justify-center">
                      <button type="submit" class="text-white font-bold py-2 px-4 rounded shadow-md">Submit</button>
                    </div>
                  </div>
                </form>
              </div>
              <!-- Right column content -->
              <div class="bg-gray-100 md:col-span-1 p-4 rounded shadow">
                <h2 class="font-semibold text-lg">Contact Information</h2>
                <p class="text-sm text-gray-600">Have any questions for us?</p>
                
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
  