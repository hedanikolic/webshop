<template>
    <div class="min-h-screen flex flex-col pt-24">
        <Navbar />
        <div class="flex flex-col flex-grow">
           <div>
            <h1 class="custom-shadow text-5xl font-semibold text-center p-12">Ear Curations</h1>
            </div>
            <div class="flex flex-col text-center justify-center text-lg text-gray-700 px-6">
                <p>You have a lot of piercings, but just can't make it look cohesive?</p>
                <p>Let us do it for you!</p>
            </div>
            <div class="flex flex-col p-16 text-2xl text-gray-700">
                <p>Here's how it works:</p>
                <div class="py-8 px-2 md:px-8 lg:mx-8 flex flex-col md:flex-row md:space-x-12">
                    <div class="flex flex-col space-y-16 md:flex-grow text-lg">
                        <div>
                            <div class="flex items-start md:items-center">
                                <span class="custom-shadow text-3xl font-semibold pr-4" style="color:indianred">1:</span>
                                <div>
                                    <span>Fill out the</span>
                                    <a href="/contact" class="pl-2 hover:scale-105" style="color: indianred;">application form</a>
                                    <span class="pl-2">and wait for us to contact you.</span>
                                </div>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <span class="custom-shadow text-3xl font-semibold" style="color:indianred">2:</span>
                            <span class="pl-4">
                                You send us pictures of your ears and tell us what you're looking for. Likes, dislikes, preferred colorway, type of jewelry...
                            </span>
                        </div>
                            
                        <div class="flex items-start">
                            <span class="custom-shadow text-3xl font-semibold" style="color:indianred">3:</span>
                            <span class="pl-4">
                                When we get on the same page, You send us the 30€ deposit that will be deducted from the final price.
                            </span>
                        </div>
                    </div>
                    <div class="hidden md:flex justify-center">
                        <img src="/assets/carousel1/before.jpeg" alt="Before" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
                    </div>
                </div>

                <div class="py-8 px-2 md:px-8 lg:mx-8 flex flex-col md:flex-row md:space-x-12">
                    <div class="hidden md:flex justify-center">
                        <img src="/assets/carousel1/sketch.jpeg" alt="Sketch" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
                    </div>

                    <div class="flex flex-col space-y-16 md:flex-grow text-lg">
                        <div class="flex items-start">
                            <span class="custom-shadow text-3xl font-semibold" style="color:indianred">4:</span>
                            <span class="pl-4">
                                We start working on a sketch based on all the information we have gathered to make the perfect curation for You.
                            </span>
                        </div>
                        <span class="pl-12">
                             When You get the sketch, You tell us what You think and if there's anything You wish to be changed.
                        </span>
                        <div class="flex items-start">
                            <span class="custom-shadow text-3xl font-semibold" style="color:indianred">5:</span>
                            <span class="pl-4">
                                When You're fully satisfied with the curation, we send you the final price. When we recieve Your payment,
                                the set gets shipped and should be at Your door within two weeks!
                            </span>
                        </div>
                    </div>
                </div>

                <div class="py-8 md:py-12 px-2 md:px-8 lg:mx-8 flex flex-col md:flex-row md:space-x-12">
                    <div class="flex flex-col space-y-16 md:flex-grow text-lg">
                        <div class="flex items-start md:items-center">
                            <span class="custom-shadow text-3xl font-semibold" style="color:indianred">6:</span>
                            <span class="pl-4">
                                The final step is You enjoying your newly styled set of ears!
                            </span>
                        </div>
                        <span class="pl-12">
                             We encourage You to send us pictures of the final result and share it on social media!
                        </span>
                        <div class="flex justify-center space-x-10">
                            <a href="https://facebook.com" target="_blank" class="hover:scale-110 transition-transform duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="indianred" class="w-10 h-10">
                                <path d="M512,257.555c0,-141.385 -114.615,-256 -256,-256c-141.385,0 -256,114.615 -256,256c0,127.777 93.616,233.685 216,252.89l0,-178.89l-65,0l0,-74l65,0l0,-56.4c0,-64.16 38.219,-99.6 96.695,-99.6c28.009,0 57.305,5 57.305,5l0,63l-32.281,0c-31.801,0 -41.719,19.733 -41.719,39.978l0,48.022l71,0l-11.35,74l-59.65,0l0,178.89c122.385,-19.205 216,-125.113 216,-252.89Z"/>
                            </svg>
                            </a>
                            <a href="https://instagram.com" target="_blank" class="hover:scale-110 transition-transform duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="indianred" class="w-10 h-10">
                                <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849
                                0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 
                                4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 
                                6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0
                                10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                            </svg>
                            </a>
                            <a href="https://twitter.com" target="_blank" class="hover:scale-110 transition-transform duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="indianred" class="w-10 h-10">
                                <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054
                                2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                            </svg>
                            </a>
                            <a href="https://tiktok.com" target="_blank" class="hover:scale-110 transition-transform duration-200">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="indianred" class="w-10 h-10">
                                <path d="M412.19,118.66a109.27,109.27,0,0,1-9.45-5.5,132.87,132.87,0,0,1-24.27-20.62c-18.1-20.71-24.86-41.72-27.35-56.43h.1C349.14,23.9,350,16,350.13,16H267.69V334.78c0,4.28,0,8.51-.18,12.69,0,.52-.05,1-.08,1.56,0,.23,0,.47-.05.71,0,.06,0,.12,0,.18a70,70,0,0,1-35.22,55.56,68.8,68.8,0,0,1-34.11,9c-38.41,0-69.54-31.32-69.54-70s31.13-70,
                                69.54-70a68.9,68.9,0,0,1,21.41,3.39l.1-83.94a153.14,153.14,0,0,0-118,34.52,161.79,161.79,0,0,0-35.3,43.53c-3.48,6-16.61,30.11-18.2,69.24-1,22.21,5.67,45.22,8.85,54.73v.2c2,5.6,9.75,24.71,22.38,40.82A167.53,167.53,0,0,0,115,470.66v-.2l.2.2C155.11,497.78,199.36,496,199.36,496c7.66-.31,33.32,0,62.46-13.81,32.32-15.31,50.72-38.12,50.72-38.12a158.46,
                                158.46,0,0,0,27.64-45.93c7.46-19.61,9.95-43.13,9.95-52.53V176.49c1,.6,14.32,9.41,14.32,9.41s19.19,12.3,49.13,20.31c21.48,5.7,50.42,6.9,50.42,6.9V131.27C453.86,132.37,433.27,129.17,412.19,118.66Z"/>
                            </svg>
                            </a>
                        </div>
                    </div>
                    <div class="hidden md:flex justify-center">
                        <img src="/assets/carousel1/after.jpeg" alt="After" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
                    </div>
                </div>
                <div class="flex-col justify-center py-8">
                    <div class="md:hidden flex justify-center p-8">
                        <img src="/assets/carousel1/before.jpeg" alt="Before" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
                    </div>
                    <div class="md:hidden flex justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="indianred" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-16 h-16">
                        <polyline points="6 9 12 15 18 9" />
                        </svg>
                    </div>
                    <div class="md:hidden flex justify-center p-8">
                        <img src="/assets/carousel1/sketch.jpeg" alt="Sketch" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
                    </div>
                    <div class="md:hidden flex justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="indianred" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="w-16 h-16">
                        <polyline points="6 9 12 15 18 9" />
                        </svg>
                    </div>
                    <div class="md:hidden flex justify-center p-8">
                        <img src="/assets/carousel1/after.jpeg" alt="After" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
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
 h1{
    color: indianred;
 }
 .custom-shadow {
    text-shadow: 2px 1px 1px rgba(205, 92, 92, 0.5);
  }
</style> 
  