<template>
   <div class="max-w-5xl mx-auto mt-12 px-4 text-center">
        <div class="w-full max-w-3xl mx-auto">
            <h1 class="text-4xl font-bold mt-2 mb-6">WELCOME TO OUR SERVICES<br></h1>

            <p>Choose your desire Service below!</p>

            <div class="grid grid-cols-3 gap-12 h-screen w-full">
                <details v-for="name in names" :key="index" class="mb-2">
                    <summary class="bg-gray-200 p-4 rounded-lg cursor-pointer shadow-md mb-4">
                        <span class="font-semibold">{{ name }}</span>
                    </summary>
                    <ul class="ml-8 space-y-4">
                        <li>
                            <details class="mb-2">
                                <summary class="bg-gray-100 p-3 rounded-lg cursor-pointer shadow">
                                    <span class="font-semibold">Nested Dropdown 1</span>
                                </summary>
                                <div class="bg-white p-4">
                                    <p class="text-gray-800">Content for Nested Dropdown 1</p>
                                </div>
                            </details>
                        </li>
                        <li>
                            <details class="mb-2">
                                <summary class="bg-gray-100 p-3 rounded-lg cursor-pointer shadow">
                                    <span class="font-semibold">Nested Dropdown 2</span>
                                </summary>
                                <div class="bg-white p-4">
                                    <p class="text-gray-800">Content for Nested Dropdown 2</p>
                                </div>
                            </details>
                        </li>
                        <li>
                            <details class="mb-2">
                                <summary class="bg-gray-100 p-3 rounded-lg cursor-pointer shadow">
                                    <span class="font-semibold">Nested Dropdown 3</span>
                                </summary>
                                <div class="bg-white p-4">
                                    <p class="text-gray-800">Content for Nested Dropdown 3</p>
                                </div>
                            </details>
                        </li>
                        <li>
                            <details class="mb-2">
                                <summary class="bg-gray-100 p-3 rounded-lg cursor-pointer shadow">
                                    <span class="font-semibold">Nested Dropdown 4</span>
                                </summary>
                                <div class="bg-white p-4">
                                    <p class="text-gray-800">Content for Nested Dropdown 4</p>
                                </div>
                            </details>
                        </li>
                        <li>
                            <details class="mb-2">
                                <summary class="bg-gray-100 p-3 rounded-lg cursor-pointer shadow">
                                    <span class="font-semibold">Nested Dropdown 5</span>
                                </summary>
                                <div class="bg-white p-4">
                                    <p class="text-gray-800">Content for Nested Dropdown 5</p>
                                </div>
                            </details>
                        </li>
                            
                    </ul>
                </details>

            </div> 
        </div>
    </div>


    <div class="flex flex-col min-h-screen">
    <main class="flex-grow">
        <!-- Content goes here -->
    </main>
    <footer class="bg-gray-800 text-white py-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2024 My Website. All rights reserved.</p>
        </div>
    </footer>
</div>


</template>


<script setup>
import { ref } from 'vue'
const names = ref([
    "PROVINCES",
    "DISTRICTS",
    "SECTORS",
    "CELLS",
    "Mukindo",
    "Mwendo",
])

const variable = ref([
    "test",
    "test1",
    "test2",
    "test2",
    
])


</script>