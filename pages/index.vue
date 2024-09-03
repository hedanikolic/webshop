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
                        <img src="/assets/gallery12.jpeg" alt="Before" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
                    </div>
                </div>

                <div class="py-8 px-2 md:px-8 lg:mx-8 flex flex-col md:flex-row md:space-x-12">
                    <div class="hidden md:flex justify-center">
                        <img src="/assets/gallery12.jpeg" alt="Before" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
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
                    </div>
                    <div class="hidden md:flex justify-center">
                        <img src="/assets/gallery12.jpeg" alt="Before" class="max-w-xs max-h-xs rounded-lg shadow-2xl">
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
  