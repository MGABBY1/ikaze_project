<template>
    <div>
        <div class="mx-14 mt-10 border-2 border-blue-400 rounded-lg cursor-pointer rounded-lg bg-yellow-700 px-8 py-5 text-sm font-semibold text-white">
            <button onclick="history.back()">Go Back</button>
    <div class="mt-10 text-center font-bold ">Contact Us +250 78</div>
    <div class="mt-3 text-center text-4xl font-bold motion-safe:hover:-translate-x-0.5 motion-safe:transition">Make an Appointment</div>
    <div class="p-8">
        <p>Full Names</p>
        <div class="flex gap-4">
        <input type="Name" name="name" class="mt-1 block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 placeholder-slate-400 shadow-sm placeholder:font-semibold placeholder:text-gray-500 focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm" placeholder="First name *" />
        <input type="Name" name="name" class="mt-1 block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 placeholder-slate-400 shadow-sm placeholder:font-semibold placeholder:text-gray-500 focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm" placeholder="Last name *"/>
        </div>

        <div class="flex gap-4">
            <input type="email" name="email" class="mt-1 block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 placeholder-slate-400 shadow-sm placeholder:font-semibold placeholder:text-gray-500 focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm" placeholder="ID card number *" />
            <input type="email" name="email" class="mt-1 block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 placeholder-slate-400 shadow-sm placeholder:font-semibold placeholder:text-gray-500 focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm" placeholder="Email *" />
            
        </div>
       <div>

       <input type="phoneNumber" name="phoneNumber" class="mt-1 block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 placeholder-slate-400 shadow-sm placeholder:font-semibold placeholder:text-gray-500 focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm" placeholder="Your phone number" />
      </div>

        <div class="my-6 flex gap-4">
        <select name="select" id="select" class="block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 font-semibold text-gray-500 shadow-sm focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm">
            <option  class="font-semibold text-slate-300">Your country</option>    
        </select>
        </div>

            <div class="my-6 flex gape-4">
            <select name="select" id="select" class="block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 font-semibold text-gray-500 shadow-sm focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm">
            <option  class="font-semibold text-slate-300">Date of Birth</option>
                </select>  
         </div>

        <div>
        <select name="select" id="select" class="block w-1/3 rounded-md border border-slate-300 bg-white px-3 py-4 font-semibold text-gray-300 shadow-sm focus:border-sky-500 focus:outline-none focus:ring-1 focus:ring-sky-500 sm:text-sm">
            <option  class="font-semibold text-slate-300">Please choose date and time of Reservation</option>
        </select>
        </div>

        
            <div class="my-6 flex gape-4">
            <textarea name="textarea" id="text" cols="30" rows="10" class="mb-10 h-40 w-full resize-none rounded-md border border-slate-300 p-5 font-semibold text-gray-300">Message</textarea>
        </div>
            
            <div class="text-center">
            <a class="cursor-pointer rounded-lg bg-blue-700 px-8 py-5 text-sm font-semibold text-white">Book Appoinment</a>
            </div>

    </div>
    </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>