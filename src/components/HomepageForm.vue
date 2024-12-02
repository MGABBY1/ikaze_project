<template>
   <div class="max-w-5xl mx-auto mt-12 px-4 text-center">
    <div class="w-full max-w-3xl mx-auto">
        <h1 class="text-4xl font-bold mt-2 mb-6">WELCOME TO OUR SERVICES<br></h1>
   <p>Choose your desire Service below!</p>

     
        <div class="p-4 max-w-lg mx-auto mt-24">
    <details class="mb-2">
        <summary class="bg-gray-200 p-4 rounded-lg cursor-pointer shadow-md mb-4">
            <span class="font-semibold">Main Dropdown</span>
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
        </ul>
    </details>

    <details class="mb-2">
        <summary class="bg-gray-200 p-4 rounded-lg cursor-pointer shadow-md mb-4">
            <span class="font-semibold">Another Dropdown</span>
        </summary>
        <ul class="ml-8 space-y-4">
            <li>
                <details class="mb-2">
                    <summary class="bg-gray-100 p-3 rounded-lg cursor-pointer shadow">
                        <span class="font-semibold">Nested Item 1</span>
                    </summary>
                    <div class="bg-white p-4">
                        <p class="text-gray-800">Content for Nested Item 1</p>
                    </div>
                </details>
            </li>
            <li>
                <details class="mb-2">
                    <summary class="bg-gray-100 p-3 rounded-lg cursor-pointer shadow">
                        <span class="font-semibold">Nested Item 2</span>
                    </summary>
                    <div class="bg-white p-4">
                        <p class="text-gray-800">Content for Nested Item 2</p>
                    </div>
                </details>
            </li>
        </ul>
    </details>
</div>
        <div>
            <a class="inline-block py-4 px-8 leading-none text-white bg-slate-800 hover:bg-pink-600 rounded shadow text-sm font-bold"
                href="/signup">Sign-up for free</a>
        </div>
       
    </div>
</div>
</template>