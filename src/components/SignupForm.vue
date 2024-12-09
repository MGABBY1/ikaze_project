
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
      </div>

<section class="flex flex-col items-center pt-6">
    <div
      class="w-full bg-white rounded-lg shadow dark:border md:mt-0 sm:max-w-md xl:p-0 dark:bg-gray-800 dark:border-gray-700">
      <div class="p-6 space-y-4 md:space-y-6 sm:p-8">
        <h1 class="text-xl font-bold leading-tight tracking-tight text-gray-900 md:text-2xl dark:text-white">Create an
            account
        </h1>
            <form class="space-y-4 md:space-y-6" method="POST">
            <div>
                <label for="name" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Your full name</label>
                <input type="text" name="name" id="name" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Emelia Erickson" required="">
          </div>
          <div>
                <label for="username" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Username</label>
                <input type="text" name="username" id="username" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="emelia_erickson24" required="">
            </div>
            <div>
                <label for="password" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Password</label>
                <input type="password" name="password" id="password" placeholder="••••••••" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-600 focus:border-blue-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" required="">
          </div>
          <button type="submit" class="w-full text-white bg-blue-600 hover:bg-blue-700 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Create an account</button>
          <p class="text-sm font-light text-gray-500 dark:text-gray-400">Already have an account? <a
              class="font-medium text-blue-600 hover:underline dark:text-blue-500" href="/signin">Sign in here</a>
          </p>
        </form>
      </div>
    </div>
  </section>
  </template>