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

        <section class="w-full">
    <div class="w-full h-[520px] bg-[url('https://images.unsplash.com/photo-1449844908441-8829872d2607?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w0NzEyNjZ8MHwxfHNlYXJjaHw2fHxob21lfGVufDB8MHx8fDE3MTA0MDE1NDZ8MA&ixlib=rb-4.0.3&q=80&w=1080')] bg-cover bg-no-repeat bg-center flex flex-col justify-center items-center ">
    <!-- Photo by '@insolitus' on Unsplash -->
        <div>
            <h1 class="text-white text-center xl:text-5xl lg:text-4xl md:text-3xl sm:text-2xl xs:text-xl font-semibold bg-gray-800 p-2 bg-opacity-40 rounded-sm">Discover Your New Home</h1>
        </div>
        <div class="w-full mx-auto">
            <form>
                <div class="xl:w-1/2 lg:w-[60%] md:w-[70%] sm:w-[70%] xs:w-[90%] mx-auto flex gap-2 md:mt-6 xs:mt-4 mx-4">
                    <input type="text" class="border border-gray-400 w-full p-2 rounded-md text-xl pl-2"
                            placeholder="" />
                    <button type="submit" class="px-[10px] p-[10px] bg-blue-500 text-lg text-white rounded-md font-semibold">Search</button>
                </div>
            </form>
        </div>
    </div>
</section>
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
            
            
        <div>
            <div class="text-gray-600 dark:text-gray-300 pt-8 dark:bg-gray-900" id="reviews">
                <div class="max-w-7xl mx-auto px-6 md:px-12 xl:px-6">
                    <div class="mb-10 space-y-4 px-6 md:px-0">
                            <h2 class="text-center text-2xl font-bold text-green-800 dark:text-white md:text-4xl">
                            YOU CAN SEE GUIDES INFORMATION HERE!
                            </h2>
                            </div> 

            <div class="md:columns-2 lg:columns-3 gap-8 space-y-8">
                <div class="aspect-auto p-8 border border-gray-100 rounded-3xl bg-white dark:bg-gray-800 dark:border-gray-700 shadow-2xl shadow-gray-600/10 dark:shadow-none">
                   <div class="flex gap-4">
                            <img class="w-20 h-20 rounded-full" src="/src/assets/Kigali.jpg" alt="user avatar" width="400" height="400" loading="lazy">
                         <div>
                                    <h6 class="text-lg font-medium text-gray-700 dark:text-white">Sobanukirwa</h6>
                                    <p class="text-sm text-gray-500 dark:text-gray-300">serivise wifuza</p>
                               </div>
                                   </div>      
                                                <p class="mt-8"> Ushobora kwaka gahunda yo gukemura ikibazo cyawe munzego zose wifuza muri leta ugabwa uburenganzira ndetse bikagufasha kutica igihe
                                        cyawe, mugihe harizindi gahunda ufite bikagufasha kwihutisha gahunda zawe mugihe kikunogeye kandi cyoroheje. niyo mpanvu iyi Website yakozwe kugirango 
                                        tubashe gukoresha igihe neza hatagize imirimo yangirika.
                                        </p>
                                            </div>


                                <div class="aspect-auto p-8 border border-gray-100 rounded-3xl bg-white dark:bg-gray-800 dark:border-gray-700 shadow-2xl shadow-gray-600/10 dark:shadow-none">
                             <div class="flex gap-4">
                                       <img class="w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/women/14.jpg" alt="user avatar" width="200" height="200" loading="lazy">
                        
                          <div>
                                        <h6 class="text-lg font-medium text-gray-700 dark:text-white">Jane doe</h6>
                                        <p class="text-sm text-gray-500 dark:text-gray-300">Marketing</p>
                     </div>
                  </div>
                            <p class="mt-8"> Lorem ipsum dolor laboriosam deleniti aperiam ab veniam sint non cumque quis tempore
                                cupiditate. Sint libero voluptas veniam at reprehenderit, veritatis harum et rerum.
                            </p>
            </div>
          <div class="aspect-auto p-8 border border-gray-100 rounded-3xl bg-white dark:bg-gray-800 dark:border-gray-700 shadow-2xl shadow-gray-600/10 dark:shadow-none">
        <div class="flex gap-4">
                        <img class="w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/women/18.jpg" alt="user avatar" width="200" height="200" loading="lazy">
      <div>
                                    <h6 class="text-lg font-medium text-gray-700 dark:text-white">Yanick Doe</h6>
                                    <p class="text-sm text-gray-500 dark:text-gray-300">Developer</p>
           </div>
               </div>
                    <p class="mt-8">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Architecto laboriosam deleniti
                    aperiam ab veniam sint non cumque quis tempore cupiditate. Sint libero voluptas veniam at
                    reprehenderit, veritatis harum et rerum.
                      </p>
                         </div>


                              <div class="aspect-auto p-8 border border-gray-100 rounded-3xl bg-white dark:bg-gray-800 dark:border-gray-700 shadow-2xl shadow-gray-600/10 dark:shadow-none">
                                   <div class="flex gap-4">
                                       <img class="w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/women/2.jpg" alt="user avatar" width="200" height="200" loading="lazy">
                                       <div>
                                             <h6 class="text-lg font-medium text-gray-700 dark:text-white">Jane Doe</h6>
                                             <p class="text-sm text-gray-500 dark:text-gray-300">Mobile dev</p>
                                            </div>
                                        </div>
                                            <p class="mt-8">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Architecto laboriosam deleniti
                                                aperiam ab veniam sint non cumque quis tempore cupiditate. Sint libero voluptas veniam at
                                                reprehenderit, veritatis harum et rerum.
                                             </p>
                                     </div>
                                   <div class="aspect-auto p-8 border border-gray-100 rounded-3xl bg-white dark:bg-gray-800 dark:border-gray-700 shadow-2xl shadow-gray-600/10 dark:shadow-none">
                               <div class="flex gap-4">
                                            <img class="w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/women/62.jpg" alt="user avatar" width="200" height="200" loading="lazy">
                            <div>
                                    <h6 class="text-lg font-medium text-gray-700 dark:text-white">Andy Doe</h6>
                                     <p class="text-sm text-gray-500 dark:text-gray-300">Manager</p>
                          </div>
                     </div>
                                <p class="mt-8"> Lorem ipsum dolor sit amet consectetur, adipisicing elit. Architecto laboriosam
                                deleniti aperiam ab veniam sint non cumque quis tempore cupiditate. Sint libero voluptas veniam at
                                reprehenderit, veritatis harum et rerum.
                            </p>
               </div> 
              <div
                            class="aspect-auto p-8 border border-gray-100 rounded-3xl bg-white dark:bg-gray-800 dark:border-gray-700 shadow-2xl shadow-gray-600/10 dark:shadow-none">
                    <div class="flex gap-4">
                                <img class="w-12 h-12 rounded-full" src="https://randomuser.me/api/portraits/women/19.jpg" alt="user avatar" width="400" height="400" loading="lazy">
                    <div>
                                    <h6 class="text-lg font-medium text-gray-700 dark:text-white">Yanndy Doe</h6>
                                    <p class="text-sm text-gray-500 dark:text-gray-300">Mobile dev</p>
                        </div>
                        </div>
                            <p class="mt-8">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Architecto laboriosam deleniti
                                aperiam ab veniam sint non cumque quis tempore cupiditate. Sint libero voluptas veniam at
                                reprehenderit, veritatis harum et rerum.
                     </p>
                </div>

            </div>
        </div>
        </div>
    </div>
</div>
</template>