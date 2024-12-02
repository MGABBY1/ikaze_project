<template>
    <div class="flex items-center justify-center flex-col w-full">
        <div class="flex w-full items-center w-full">
            <header class="bg-green-600 sticky w-full">
                <div class=" py-7 ">
                    
    
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
            <div class="w-full grid grid-rows-3">
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

                <div class="flex flex-1 items-center justify-center p-5">
                    <div class="w-full max-w-4xl">
                        <form class="mt-1/2 sm:flex sm:items-center">
                            <input id="q" name="q" class="inline w-full rounded-md border border-gray-300 bg-white py-3 pl-3 pr-3 leading-5 placeholder-gray-500 focus:border-indigo-500 focus:placeholder-gray-400 focus:outline-none focus:ring-1 focus:ring-indigo-500 sm:text-sm" placeholder="Searching Service" type="search" autofocus="" value="">
                            <button type="submit" class="mt-1/3 inline-flex w-full items-center justify-center rounded-md border border-transparent bg-indigo-600 px-2 py-2 font-medium text-white shadow-sm hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2 sm:mt-0 sm:ml-3 sm:w-auto sm:text-sm">
                                Search
                            </button>
                        </form>
                    </div>
                </div>

            </div>

        </div>
        
    </div>
</template>

<script setup>
let cells = [

  "Akabahizi", "Akabeza", "Gacyamo", "Kigarama", "Kinyange", "Kora", "Nyamweru", "Nzove", "Taba", 
  "Kigali", "Mwendo", "Nyabugogo", "Ruriba", "Rwesero", "Kimisagara", "Mageregere", "Muhima", 
  "Nyakabanda", "Nyamirambo", "Nyarugenge", "Rwezamenyo", "Bumbogo", "Gatsata", "Gikomero", "Gisozi", 
  "Jabana", "Jali", "Kacyiru", "Kimihurura", "Kimironko", "Kinyinya", "Ndera", "Nduba", "Remera", 
  "Rusororo", "Rutunga", "Gahanga", "Gatenga", "Gikondo", "Kagarama", "Kanombe", "Kicukiro", "Kigarama", 
  "Masaka", "Niboye", "Nyarugunga", "Busasamana", "Busoro", "Cyabakamyi", "Kibilizi", "Kigoma", "Mukingo", 
  "Muyira", "Ntyazo", "Nyagisozi","Rwabicuma","Gikonko", "Gishubi",
    "Kansi", "Kibirizi",
    "Kigembe",
    "Mamba",
    "Muganza",
    "Mugombwa",
    "Mukindo",
    "Mwendo",
    "Musha",
    "Ndora",
    "Nyanza",
    "Save",
    "Busanze",
    "Cyahinda",
    "Kibeho",
    "Kivu",
    "Mata",
    "Muganza",
    "Munini",
    "Ngera",
    "Ngoma",
    "Nyabimata",
    "Nyagisozi",
    "Ruheru",
    "Ruramba",
    "Rusenge",
    "Gishamvu",
    "Huye",
    "Karama",
    "Kigoma",
    "Kinazi",
    "Maraba",
    "Mbazi",
    "Mukura",
    "Ngoma",
    "Ruhashya",
    "Rusatira",
    "Rwaniro",
    "Simbi",
    "Tumba",
    "Buruhukiro",
    "Cyanika",
    "Gasaka",
    "Gatare",
    "Kaduha",
    "Kamegeri",
    "Kibilizi",
    "Kibumbwe",
    "Kitabi",
    "Mbazi",
    "Mugano",
    "Musange",
    "Musebeya",
    "Mushubi",
    "Uwinkingi",
    "Bweramana",
    "Byimana",
    "Kabagali",
    "Kinazi",
    "Kinihira",
    "Mbuye",
    "Mwendo",
    "Ntongwe",
    "Ruhango",
    "Cyeza",
    "Kabacuzi",
    "Kiyumba",
    "Muhanga",
    "Mushishiro",
    "Nyabinoni",
    "Nyamabuye",
    "Nyarusange",
    "Rongi",
    "Rugendabari",
    "Shyogwe",
    "Gacurabwenge",
    "Karama",
    "Kayenzi",
    "Kayumbu",
    "Mugina",
    "Musambira",
    "Ngamba",
    "Nyamiyaga",
    "Nyarubaka",
    "Rugarika",
    "Rukoma",
    "Runda",
    "Bwishyura",
    "Gashari",
    "Gishyita",
    "Gitesi",
    "Mubuga",
    "Murambi",
    "Murundi",
    "Mutuntu",
    "Rubengera",
    "Rugabano",
    "Ruganda",
    "Rwankuba",
    "Twumba",
    "Boneza",
    "Gihango",
    "Kigeyo",
    "Kivumu",
    "Manihira",
    "Mukura",
    "Murunda",
    "Musasa",
    "Mushonyi",
    "Mushubati",
    "Nyabirasi",
    "Ruhango",
    "Rusebeya",
    "Bugeshi",
    "Busasamana",
    "Cyanzarwe",
    "Gisenyi",
    "Kanama",
    "Kanzenze",
    "Mudende",
    "Nyakiriba",
    "Nyamyumba",
    "Nyundo",
    "Rubavu",
    "Rugerero",
    "Bigogwe",
    "Jomba",
    "Kabatwa",
    "Karago",
    "Kintobo",
    "Makamira",
    "Muringa",
    "Rambura",
    "Rugera",
    "Rurembo",
    "Shyira",
    "BWIRA",
    "Gatumba",
    "Hindiro",
    "Kabaya",
    "Kageyo",
    "Kavumu",
    "Matyazo",
    "Muhanda",
    "Muhororo",
    "Ndaro",
    "Ngororero",
    "Nyange",
    "Sovu",
    "Bugarama",
    "Butare",
    "Bweyeye",
    "Gashonga",
    "Giheke",
    "Gihundwe",
    "Gikundamvura",
    "Gitambi",
    "Kamembe",
    "Muganza",
    "Mururu",
    "Nkanka",
    "Nkombo",
    "Nkungu",
    "Nyakabuye",
    "Nyakarenzo",
    "Nzahaha",
    "Rwimbogo",
    "Bushekeri",
    "Bushenge",
    "Cyato",
    "Gihombo",
    "Kagano",
    "Kanjongo",
    "Karambi",
    "Karengera",
    "Kirimbi",
    "Macuba",
    "Mahembe",
    "Nyabitekeri",
    "Rangiro",
    "Ruharambuga",
    "Shangi",
    "BASE",
    "BUREGA",
    "Bushoki",
    "BUYOGA",
    "CYINZUZI",
    "CYUNGO",
    "KINIHIRA",
    "KISARO",
    "MASORO",
    "MBOGO",
    "Murambi",
    "NGOMA",
    "Ntarabana",
    "RUKOZO",
    "RUSIGA",
    "Shyorongi",
    "TUMBA",
    "Busengo",
    "Coko",
    "Cyabingo",
    "Gakenke",
    "Gashenyi",
    "Janja",
    "Kamubuga",
    "Karambo",
    "Kivuruga",
    "Mataba",
    "Minazi",
    "Mugunga",
    "Muhondo",
    "Muyongwe",
    "Muzo",
    "Nemba",
    "Ruli",
    "Rusasa"
]
// let sectors 




function changeColor(){
    let button = document.getElementById('change-button');
    let colors = ["red", "blue", "green", "yellow", "pink", "purple", "gray"];  //Add more colors from tailwind design pallete as per requirement
    let color = colors[Math.floor(Math.random() * colors.length)]; 
    button.className = '';  
    button.classList.add('px-4', 'py-2','rounded-lg','text-white',`bg-${color}-500`);
}

setInterval(() => {
    changeColor();
}, 500);    //Color change duration is 500 ms, you can adjust the duration.


</script>