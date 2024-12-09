<template>
<div class="flex items-center justify-center flex-col w-full">
        <div class="flex w-full items-center w-full">
            <header class="bg-green-600 sticky w-full">
                <div class=" py-4 ">
                    
    
                    <div class="flex md:hidden">
                        <button id="hamburger" class="text-white focus:-none">
                        <svg class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                        </svg>
                        </button>
                    </div>

                  
                    <span class="flex item-center justify-center">
                         
                     <marquee> <a href="#home" class="text-white hover:text-secondary font-bold">WELCOME TO RWANDA LOCAL GOVERNMENT RESERVATION!</a> </marquee>
              
                  
                    </span>


                </div>
            </header>
        </div>

    
        <div class="bg-[#243c5a] w-full p-4 h-50">
            <div class="w-full grid grid-rows-2">
                <div class="flex justify-between py-4 row-span-1">
                        
                    <div class="w-1/4">
                        <div class="flex items-center justify-center col-span-1 ">
                            <button id="change-button" class="bg-red-500 text-white px-4 py-2 rounded-lg ">
                                <router-link :to="{ name: 'home'}" class="text-2xl">IKAZE RESERVATION rw</router-link>
                            </button>
                        </div>
                    </div>

                    <ul class="flex gap-16 text-white">
                        <router-link :to="{ name: 'login'}" class="font-bold hover:text-red-700">Login</router-link>
                        <router-link :to="{ name: 'signup'}" class="font-bold hover:text-red-700">Signup</router-link>
                        <router-link :to="{ name: 'guide'}" class="font-bold hover:text-red-700">Guide</router-link>
                        <router-link :to="{ name: 'contactUs'}" class="font-bold hover:text-red-700">Contact us</router-link>
                        <div class="dropdown dropdown-end">
                            <div tabindex="0" role="button" class="font-bold">Languages</div>
                            <ul tabindex="0" class="dropdown-content menu bg-base-100 rounded-box z-[1] w-40 p-2 shadow text-black">
                                <li><a>English</a></li>
                                <li><a>Kinyarwanda</a></li>
                            </ul>
                        </div>
                    </ul>
                </div>
             </div>
         </div>

    <div class="flex flex-col items-center pt-6 ">
        <div class="max-w-xl py-6 px-8 h-80 mt-20 bg-white rounded shadow-xl">
            <form action="">
                <div class="mb-6">
                <label for="name" class="block text-gray-800 font-bold">Your phone number or Email</label>
                <input type="text" name="name" id="name" placeholder="Phone number or Email" class="w-full border border-gray-300 py-2 pl-3 rounded mt-2 outline-none focus:ring-indigo-600 :ring-indigo-600"/>
                </div>
                <div>
                <label for="email" class="block text-gray-800 font-bold">Your Password</label>
                <input type="text" name="email" id="email" placeholder="Enter your password" class="w-full border border-gray-300 py-2 pl-3 rounded mt-2 outline-none focus:ring-indigo-600 :ring-indigo-600"/>
                <a href="#" class="text-sm font-thin text-gray-800 hover:underline mt-2 inline-block hover:text-indigo-600">Forget Password</a>
                </div>
                <button class="cursor-pointer py-2 px-4 block mt-6 bg-indigo-500 text-white font-bold w-full text-center rounded">Login</button>
            </form>
        </div>
    </div>
    </div>
</template>