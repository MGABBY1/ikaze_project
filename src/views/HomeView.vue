<template>
     <!--YOU CAN GO TO NAV CODE JUST CLIK Ctrl+ok or Enter -->

            <Nav class=""></Nav>
            
          
<div class="relative h-screen w-full">
    <img src="../assets/rwandaP.png" alt="Background Image" 
    class="absolute inset-0 w-full h-full object-cover"> 
    
    <div class="absolute inset-0 flex flex-col items-center justify-center">
        <p><router-link :to="{ name: 'homePageForm'}" class="text-5xl text-black font-bold">Click here</router-link></p>

        <p class="text-xl text-white mt-9">We help you to save your time!</p>
    </div>
</div>

   
        <div class="flex flex-col max-h-screen">
            <main class="flex-grow">
        <!-- Content goes here -->
            </main>
            <footer class="bg-gray-800 text-white py-2/5">
                <div class="container mx-auto text-center"> 
                    <div class="flex justify-center space-x-5">
                <p>&copy; 2024 My Website. All rights reserved.</p> 
                <a href="https://facebook.com" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.icons8.com/fluent/30/000000/facebook-new.png" />
                </a>
                <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.icons8.com/fluent/30/000000/linkedin-2.png" />
                </a>
                <a href="https://instagram.com" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.icons8.com/fluent/30/000000/instagram-new.png" />
                </a>
                <a href="https://messenger.com" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.icons8.com/fluent/30/000000/facebook-messenger--v2.png" />
                </a>
                <a href="https://twitter.com" target="_blank" rel="noopener noreferrer">
                    <img src="https://img.icons8.com/fluent/30/000000/twitter.png" />
                
                </a>
         
        </div>
         
    </div>
    
</footer>
</div>
</template>

<script setup>
import Nav from '../components/Nav.vue';
</script>