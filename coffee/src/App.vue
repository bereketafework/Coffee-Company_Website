 <template>
  <div class="bg-gray-100">
  <section id="" class=" sticky top-0 overflow-hidden z-50 ">
    <div class=" ">
 <!-- Header and Navigations -->
<header class="lg:px-16 px-2  flex flex-wrap items-center py-4 shadow-md bg-[#7cea72]">
    <div class="flex-1 flex justify-between items-center ">
     
      <a href="" class="flex flex-row">
      <img src="./assets/logo/nokka-logo.png" class="w-[70px]">
   
    <button class="text-3xl font-bold hover:scale-105 ml-2  ">NOKKA COFFEE
      
    </button>
  </a>
    </div>

    <label for="menu-toggle" class="pointer-cursor md:hidden block">
      <svg class="fill-current text-gray-900"
        xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20">
        <title>menu</title>
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
      </svg>
    </label>
    <input class="hidden" type="checkbox" id="menu-toggle" />

    <div class="hidden md:flex md:items-center md:w-auto w-full " id="menu">
        <nav>
            <ul class="md:flex items-center justify-between text-black text-balance font-bold pt-4 md:pt-0 gap-10">
                <li><a class="md:p-4 py-3 px-0  block hover:text-gray-500" href="#">Home</a></li>
                <li><a class="md:p-4 py-3 px-0 block hover:text-gray-700" href="#about">About Us</a></li>
                <li><a class="md:p-4 py-3 px-0 block hover:text-gray-700" href="#gallery">Gallery</a></li>
                <li><a class="md:p-4 py-3 px-0 block hover:text-gray-700" href="#team">Team</a></li>
                <li><a class="md:p-4 py-3 px-0 block hover:text-gray-700" href="#contact">Contact Us</a></li>
                
            </ul>
        </nav>
    </div>
</header>
</div>
</section>

<!-- parallex effect and Home page -->

<section id="home">
  
  <div class="relative  h-screen text-white overflow-hidden shadow-inner">
  <div class="absolute inset-0 mt-0">
    <img src="./assets/images/qilleenso-01.png" alt="Background Image" class="object-cover object-center w-full h-full" />
    <div class="absolute inset-0 bg-black opacity-50"></div>
  </div>
  
  <div class="relative z-10 flex flex-col justify-center items-center h-full text-center">
    <h1 class="text-5xl font-bold leading-tight mb-4" >Welcome to  <span class="hover:text-red-950" >Nokka Coffee</span> </h1>
    <p class="text-lg text-gray-300 mb-8">Coffee Harvesting And Exporting.</p>
    <div class="flex flex-row gap-20">
    <a href="#" class="bg-emerald-600 text-gray-200  py-2 px-6 rounded-md text-lg font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg">About Us</a>
    <a href="#contact" class="transparent text-emerald-500 border-emerald-500 border-[2px] py-2 px-6 rounded-lg text-lg font-semibold transition duration-300 ease-in-out transform hover:scale-105 hover:shadow-lg">Contact Us</a>
</div>
</div>
</div>
</section>

<!-- about and Core Values section -->

<section id="about" class="bg-gray-100 ">
<div class="w-full h-full">
    
       <div class="container mx-auto py-16 px-4 sm:px-6 lg:px-8">
           <div class="grid grid-cols-1 md:grid-cols-2 items-center gap-8">
               <div class="max-w-lg">
                   <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">About Us</h2>
                   <p class="mt-4 text-gray-700 text-lg">
                     Nokka Coffeeis a family-owned business inspired by the legacy of our father, Nokka Tenko, a visionary coffee farmer and successful entrepreneur. Building on his footsteps, we have expanded our operations to produce high-quality coffee on our own farmland, as well as purchasing beans from local farmers in the region.,
   
   Our coffee is carefully processed at our state-of-the-art washing and dry processing facilities located in Bardaye Chabiti and Haro, within the West Guji zone of Southern Oromia. Committed to quality and sustainability, Nokka Coffee strives to elevate the rich coffee heritage of our community while delivering exceptional products to coffee lovers around the world.
                   </p>
                   
               </div>
               <div class="mt-12 md:mt-0 w-80 h-72 border-none flex items-start justify-start ">
                   <img src="./assets/logo/nokka-logo.png" alt="About Us Image" class="object-cover  mr-36">
                 
               </div>
           </div>
       </div>
   
   
   <div class="bg-gray-100 py-16">
       <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
           <h2 class="text-3xl font-extrabold text-gray-900">Our Business is based on our core values</h2>
           <div class="mt-12 grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
               <div class=" hover:scale-110 hover:border-2 rounded-md">
                   <div class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white m-2 ">
                       <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                           stroke="currentColor" class="w-6 h-6">
                           <path stroke-linecap="round" stroke-linejoin="round"
                               d="M12 21v-8.25M15.75 21v-8.25M8.25 21v-8.25M3 9l9-6 9 6m-1.5 12V10.332A48.36 48.36 0 0012 9.75c-2.551 0-5.056.2-7.5.582V21M3 21h18M12 6.75h.008v.008H12V6.75z" />
                       </svg>
   
                   </div>
                   <div class="mt-5">
                       <h3 class="text-lg font-medium text-gray-900 m-2">Mission</h3>
                       <p class="mt-2 text-base text-gray-500 m-2">Provide high-quality, organic, and traceable Ethiopian coffee beans along with effective, client-focused, amiable, and competent services.</p>
                   </div>
               </div>
               <div class=" hover:scale-110 hover:border-2 rounded-md">
                   <div class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white m-2">
                       <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                           stroke="currentColor" class="w-6 h-6">
                           <path stroke-linecap="round" stroke-linejoin="round"
                               d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5" />
                       </svg>
   
                   </div>
                   <div class="mt-5">
                       <h3 class="text-lg font-medium text-gray-900 m-2">Values</h3>
                       <p class="mt-2 text-base text-gray-500 m-2">to become one of the nation's most competent and to export coffee of superior quality in order to get international recognition.</p>
                   </div>
               </div>
               <div class=" hover:scale-110 hover:border-2 rounded-md">
                   <div class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white m-2">
                       <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                           stroke="currentColor" class="w-6 h-6">
                           <path stroke-linecap="round" stroke-linejoin="round"
                               d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                           <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                       </svg>
   
                   </div>
                   <div class="mt-5">
                       <h3 class="text-lg font-medium text-gray-900 m-2">Vision</h3>
                       <p class="mt-2 text-base text-gray-500 m-2">
                         to be the pioneer in tying the industry's and technology together with quality among coffee exporters and producers while taking environmental responsibility.
                       </p>
                   </div>
               </div>
           </div>
   
       </div>
      </div>
   
    </div>
  </section>

  <!-- gallery section -->

<section id="gallery">
  <div>
    <div class="top-0"> 
      <section class="px-4 py-4 mx-auto max-w-7xl">
  <div class="w-full mx-auto text-left md:w-10/12 xl:w-10/12 md:text-center">
    <h1 class="mb-6 text-4xl font-extrabold leading-none tracking-normal text-gray-900 md:text-6xl md:tracking-tight">
      <span class="block w-full text-transparent bg-clip-text bg-gradient-to-r from-green-400 to-red-950 lg:inline">Wellcome to Nokka Coffee Gallery</span>
    </h1>
  </div>
</section>
  </div>
  <div class="p-1 flex flex-wrap items-center justify-center bg-gray-100 ">
  
    <div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/bardayee-01.png" alt="Buying a Coffee From Farmers ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
Collecting Coffee From Farms
        </span>
    </div>
    
</div>

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/coffee-buying-from-farmer-01.png" alt="Buying a Coffee From Farmers ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
 Buying a Coffee From Farmers 
        </span>
    </div>
    
</div>

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/coffee-drying-process-01.png" alt="Coffee coffee-drying-process  ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
 Coffee Drying process 
        </span>
    </div>
    
</div>


<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/coffee-drying-process-2-01.png" alt=" ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
 Coffee Drying process 
        </span>
    </div>
    
</div>

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/coffee-drying-process-3-01.png" alt=" ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
 Coffee Drying process 
        </span>
    </div>
</div>

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/coffee-drying-process-4-01.png" alt=" ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
 Coffee Drying process 
        </span>
    </div>
    
</div>

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/coffee-grinding-01.png" alt=" ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
          Coffee Grinding process 
        </span>
    </div>
    
</div>

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/coggee-grinding-process-01.png" alt=" ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
          Coffee Grinding process 
        </span>
    </div>
    
</div>
<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/oggo-01.png" alt=" ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
 Our Teams In Farm
        </span>
    </div>
    
</div>

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
    <svg class="absolute bottom-0 left-0 mb-8 scale-150 group-hover:scale-[2.65] transition-transform"
        viewBox="0 0 375 283" fill="none" style="opacity: 0.1;">
        <rect x="159.52" y="175" width="152" height="152" rx="8" transform="rotate(-45 159.52 175)" fill="white" />
        <rect y="107.48" width="152" height="152" rx="8" transform="rotate(-45 0 107.48)" fill="white" />
    </svg>
    <div class="relative pt-6 px-6 flex items-center justify-center group-hover:scale-110 transition-transform flex-col">
        
        <img class="relative w-56" src="./assets/images/qarchaa-01.png" alt=" ">
        <span class=" flex min-w-fit text-[10px] font-extralight text-gray-500 opacity-100 hover:opacity-0">
Our Team In Farm
        </span>
    </div>
    
</div>

 
  </div>
</div>
</section>
 
<!-- Team members Personal Card -->

<section id="team">
  <div class=" flex justify-center " >
    <div class="max-w-screen-xl mx-auto p-5 sm:p-10 md:p-16 ">
<div class="justify-center flex m-4 underline-offset-4">
      <h1 class="text-2xl text-black md:text-3xl pl-2 pr-2 my-2 border-l-4   border-r-4   font-sans font-bold border-teal-400  dark:text-gray-200 ">
    Our Teams
</h1>

</div>
<div class="grid grid-cols-1 sm:grid-cols-2  gap-10 ">
  <div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
  <div class="relative"><a href="#">
              <img class="w-full"
                  src="./assets/TeamImage/photo_2024-11-12_10-14-50.jpg"
                  alt="Sunset in the mountains">
              <div
                  class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25">
              </div>
          </a>
      </div>
    <div class="relative  flex items-center justify-center transition-transform flex-col">
        
      <div class="px-6 py-4 mb-auto">
          <a href="#"
              class="font-medium text-lg inline-block hover:text-blue-500 transition duration-500 ease-in-out  mb-2">Mr. Shibiru Nokka</a>
          <p class="text-gray-500 text-sm">
              General Manager
          </p>
      </div>
      <div class="px-6 py-3 flex flex-row items-center justify-center bg-gray-100">
        <div class=" flex items-center justify-center  ">
  <div class="flex items-center justify-center gap-x-5 ">
      <a href="" aria-label="Find us on LinkedIn"
          target="_blank" rel="noopener" class=" rounded-md ">
          <svg class="transition-all duration-300 hover:scale-110 h-10 w-10"
    xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 72 72" fill="none">
      <path d="M46.4927 38.6403L47.7973 30.3588H39.7611V24.9759C39.7611 22.7114 40.883 20.4987 44.4706 20.4987H48.1756V13.4465C46.018 13.1028 43.8378 12.9168 41.6527 12.8901C35.0385 12.8901 30.7204 16.8626 30.7204 24.0442V30.3588H23.3887V38.6403H30.7204V58.671H39.7611V38.6403H46.4927Z" fill="#337FFF"/>
    </svg>

      </a>
      <a href="" aria-label="Find us on Twitter" target="_blank" rel="noopener"  class=" rounded-md ">
        <svg class="transition-all duration-300 hover:scale-110 h-10 w-10" width="28" height="28" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M27.4456 35.7808C27.4456 31.1786 31.1776 27.4468 35.7826 27.4468C40.3875 27.4468 44.1216 31.1786 44.1216 35.7808C44.1216 40.383 40.3875 44.1148 35.7826 44.1148C31.1776 44.1148 27.4456 40.383 27.4456 35.7808ZM22.9377 35.7808C22.9377 42.8708 28.6883 48.618 35.7826 48.618C42.8768 48.618 48.6275 42.8708 48.6275 35.7808C48.6275 28.6908 42.8768 22.9436 35.7826 22.9436C28.6883 22.9436 22.9377 28.6908 22.9377 35.7808ZM46.1342 22.4346C46.1339 23.0279 46.3098 23.608 46.6394 24.1015C46.9691 24.595 47.4377 24.9797 47.9861 25.2069C48.5346 25.4342 49.1381 25.4939 49.7204 25.3784C50.3028 25.2628 50.8378 24.9773 51.2577 24.5579C51.6777 24.1385 51.9638 23.6041 52.0799 23.0222C52.1959 22.4403 52.1367 21.8371 51.9097 21.2888C51.6828 20.7406 51.2982 20.2719 50.8047 19.942C50.3112 19.6122 49.7309 19.436 49.1372 19.4358H49.136C48.3402 19.4361 47.5771 19.7522 47.0142 20.3144C46.4514 20.8767 46.1349 21.6392 46.1342 22.4346ZM25.6765 56.1302C23.2377 56.0192 21.9121 55.6132 21.0311 55.2702C19.8632 54.8158 19.0299 54.2746 18.1538 53.4002C17.2777 52.5258 16.7354 51.6938 16.2827 50.5266C15.9393 49.6466 15.533 48.3214 15.4222 45.884C15.3009 43.2488 15.2767 42.4572 15.2767 35.781C15.2767 29.1048 15.3029 28.3154 15.4222 25.678C15.5332 23.2406 15.9425 21.918 16.2827 21.0354C16.7374 19.8682 17.2789 19.0354 18.1538 18.1598C19.0287 17.2842 19.8612 16.7422 21.0311 16.2898C21.9117 15.9466 23.2377 15.5406 25.6765 15.4298C28.3133 15.3086 29.1054 15.2844 35.7826 15.2844C42.4598 15.2844 43.2527 15.3106 45.8916 15.4298C48.3305 15.5408 49.6539 15.9498 50.537 16.2898C51.7049 16.7422 52.5382 17.2854 53.4144 18.1598C54.2905 19.0342 54.8308 19.8682 55.2855 21.0354C55.6289 21.9154 56.0351 23.2406 56.146 25.678C56.2673 28.3154 56.2915 29.1048 56.2915 35.781C56.2915 42.4572 56.2673 43.2466 56.146 45.884C56.0349 48.3214 55.6267 49.6462 55.2855 50.5266C54.8308 51.6938 54.2893 52.5266 53.4144 53.4002C52.5394 54.2738 51.7049 54.8158 50.537 55.2702C49.6565 55.6134 48.3305 56.0194 45.8916 56.1302C43.2549 56.2514 42.4628 56.2756 35.7826 56.2756C29.1024 56.2756 28.3125 56.2514 25.6765 56.1302ZM25.4694 10.9322C22.8064 11.0534 20.9867 11.4754 19.3976 12.0934C17.7518 12.7316 16.3585 13.5878 14.9663 14.977C13.5741 16.3662 12.7195 17.7608 12.081 19.4056C11.4626 20.9948 11.0403 22.8124 10.9191 25.4738C10.7958 28.1394 10.7676 28.9916 10.7676 35.7808C10.7676 42.57 10.7958 43.4222 10.9191 46.0878C11.0403 48.7494 11.4626 50.5668 12.081 52.156C12.7195 53.7998 13.5743 55.196 14.9663 56.5846C16.3583 57.9732 17.7518 58.8282 19.3976 59.4682C20.9897 60.0862 22.8064 60.5082 25.4694 60.6294C28.138 60.7506 28.9893 60.7808 35.7826 60.7808C42.5759 60.7808 43.4286 60.7526 46.0958 60.6294C48.759 60.5082 50.5774 60.0862 52.1676 59.4682C53.8124 58.8282 55.2066 57.9738 56.5989 56.5846C57.9911 55.1954 58.8438 53.7998 59.4842 52.156C60.1026 50.5668 60.5268 48.7492 60.6461 46.0878C60.7674 43.4202 60.7956 42.57 60.7956 35.7808C60.7956 28.9916 60.7674 28.1394 60.6461 25.4738C60.5248 22.8122 60.1026 20.9938 59.4842 19.4056C58.8438 17.7618 57.9889 16.3684 56.5989 14.977C55.2088 13.5856 53.8124 12.7316 52.1696 12.0934C50.5775 11.4754 48.7588 11.0514 46.0978 10.9322C43.4306 10.811 42.5779 10.7808 35.7846 10.7808C28.9913 10.7808 28.138 10.809 25.4694 10.9322Z" fill="url(#paint0_radial_7092_54471)"/>
      <path d="M27.4456 35.7808C27.4456 31.1786 31.1776 27.4468 35.7826 27.4468C40.3875 27.4468 44.1216 31.1786 44.1216 35.7808C44.1216 40.383 40.3875 44.1148 35.7826 44.1148C31.1776 44.1148 27.4456 40.383 27.4456 35.7808ZM22.9377 35.7808C22.9377 42.8708 28.6883 48.618 35.7826 48.618C42.8768 48.618 48.6275 42.8708 48.6275 35.7808C48.6275 28.6908 42.8768 22.9436 35.7826 22.9436C28.6883 22.9436 22.9377 28.6908 22.9377 35.7808ZM46.1342 22.4346C46.1339 23.0279 46.3098 23.608 46.6394 24.1015C46.9691 24.595 47.4377 24.9797 47.9861 25.2069C48.5346 25.4342 49.1381 25.4939 49.7204 25.3784C50.3028 25.2628 50.8378 24.9773 51.2577 24.5579C51.6777 24.1385 51.9638 23.6041 52.0799 23.0222C52.1959 22.4403 52.1367 21.8371 51.9097 21.2888C51.6828 20.7406 51.2982 20.2719 50.8047 19.942C50.3112 19.6122 49.7309 19.436 49.1372 19.4358H49.136C48.3402 19.4361 47.5771 19.7522 47.0142 20.3144C46.4514 20.8767 46.1349 21.6392 46.1342 22.4346ZM25.6765 56.1302C23.2377 56.0192 21.9121 55.6132 21.0311 55.2702C19.8632 54.8158 19.0299 54.2746 18.1538 53.4002C17.2777 52.5258 16.7354 51.6938 16.2827 50.5266C15.9393 49.6466 15.533 48.3214 15.4222 45.884C15.3009 43.2488 15.2767 42.4572 15.2767 35.781C15.2767 29.1048 15.3029 28.3154 15.4222 25.678C15.5332 23.2406 15.9425 21.918 16.2827 21.0354C16.7374 19.8682 17.2789 19.0354 18.1538 18.1598C19.0287 17.2842 19.8612 16.7422 21.0311 16.2898C21.9117 15.9466 23.2377 15.5406 25.6765 15.4298C28.3133 15.3086 29.1054 15.2844 35.7826 15.2844C42.4598 15.2844 43.2527 15.3106 45.8916 15.4298C48.3305 15.5408 49.6539 15.9498 50.537 16.2898C51.7049 16.7422 52.5382 17.2854 53.4144 18.1598C54.2905 19.0342 54.8308 19.8682 55.2855 21.0354C55.6289 21.9154 56.0351 23.2406 56.146 25.678C56.2673 28.3154 56.2915 29.1048 56.2915 35.781C56.2915 42.4572 56.2673 43.2466 56.146 45.884C56.0349 48.3214 55.6267 49.6462 55.2855 50.5266C54.8308 51.6938 54.2893 52.5266 53.4144 53.4002C52.5394 54.2738 51.7049 54.8158 50.537 55.2702C49.6565 55.6134 48.3305 56.0194 45.8916 56.1302C43.2549 56.2514 42.4628 56.2756 35.7826 56.2756C29.1024 56.2756 28.3125 56.2514 25.6765 56.1302ZM25.4694 10.9322C22.8064 11.0534 20.9867 11.4754 19.3976 12.0934C17.7518 12.7316 16.3585 13.5878 14.9663 14.977C13.5741 16.3662 12.7195 17.7608 12.081 19.4056C11.4626 20.9948 11.0403 22.8124 10.9191 25.4738C10.7958 28.1394 10.7676 28.9916 10.7676 35.7808C10.7676 42.57 10.7958 43.4222 10.9191 46.0878C11.0403 48.7494 11.4626 50.5668 12.081 52.156C12.7195 53.7998 13.5743 55.196 14.9663 56.5846C16.3583 57.9732 17.7518 58.8282 19.3976 59.4682C20.9897 60.0862 22.8064 60.5082 25.4694 60.6294C28.138 60.7506 28.9893 60.7808 35.7826 60.7808C42.5759 60.7808 43.4286 60.7526 46.0958 60.6294C48.759 60.5082 50.5774 60.0862 52.1676 59.4682C53.8124 58.8282 55.2066 57.9738 56.5989 56.5846C57.9911 55.1954 58.8438 53.7998 59.4842 52.156C60.1026 50.5668 60.5268 48.7492 60.6461 46.0878C60.7674 43.4202 60.7956 42.57 60.7956 35.7808C60.7956 28.9916 60.7674 28.1394 60.6461 25.4738C60.5248 22.8122 60.1026 20.9938 59.4842 19.4056C58.8438 17.7618 57.9889 16.3684 56.5989 14.977C55.2088 13.5856 53.8124 12.7316 52.1696 12.0934C50.5775 11.4754 48.7588 11.0514 46.0978 10.9322C43.4306 10.811 42.5779 10.7808 35.7846 10.7808C28.9913 10.7808 28.138 10.809 25.4694 10.9322Z" fill="url(#paint1_radial_7092_54471)"/>
      <defs>
      <radialGradient id="paint0_radial_7092_54471" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(17.4144 61.017) scale(65.31 65.2708)">
      <stop offset="0.09" stop-color="#FA8F21"/>
      <stop offset="0.78" stop-color="#D82D7E"/>
      </radialGradient>
      <radialGradient id="paint1_radial_7092_54471" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(41.1086 63.257) scale(51.4733 51.4424)">
      <stop offset="0.64" stop-color="#8C3AAA" stop-opacity="0"/>
      <stop offset="1" stop-color="#8C3AAA"/>
      </radialGradient>
      </defs>
      </svg>

      </a>
      <a href="" aria-label="Find us on Facebook" target="_blank"
          rel="noopener">
          <svg class="transition-all duration-300 hover:scale-110 h-10 w-10" width="28" height="28" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M45.6721 29.4285C48.7387 31.6085 52.4112 32.7733 56.1737 32.7592V25.3024C55.434 25.3045 54.6963 25.2253 53.9739 25.0663V31.0068C50.203 31.0135 46.5252 29.8354 43.4599 27.6389V42.9749C43.4507 45.4914 42.7606 47.9585 41.4628 50.1146C40.165 52.2706 38.3079 54.0353 36.0885 55.2215C33.8691 56.4076 31.37 56.9711 28.8563 56.852C26.3426 56.733 23.9079 55.9359 21.8105 54.5453C23.7506 56.5082 26.2295 57.8513 28.9333 58.4044C31.6372 58.9576 34.4444 58.6959 36.9994 57.6526C39.5545 56.6093 41.7425 54.8312 43.2864 52.5436C44.8302 50.256 45.6605 47.5616 45.6721 44.8018V29.4285ZM48.3938 21.8226C46.8343 20.1323 45.8775 17.9739 45.6721 15.6832V14.7139H43.5842C43.8423 16.1699 44.4039 17.5553 45.2326 18.78C46.0612 20.0048 47.1383 21.0414 48.3938 21.8226ZM26.645 48.642C25.9213 47.6957 25.4779 46.5653 25.365 45.3793C25.2522 44.1934 25.4746 42.9996 26.0068 41.9338C26.5391 40.8681 27.3598 39.9731 28.3757 39.3508C29.3915 38.7285 30.5616 38.4039 31.7529 38.4139C32.4106 38.4137 33.0644 38.5143 33.6916 38.7121V31.0068C32.9584 30.9097 32.2189 30.8682 31.4794 30.8826V36.8728C29.9522 36.39 28.2992 36.4998 26.8492 37.1803C25.3992 37.8608 24.2585 39.0621 23.6539 40.5454C23.0494 42.0286 23.0252 43.6851 23.5864 45.1853C24.1475 46.6855 25.2527 47.9196 26.6823 48.642H26.645Z" fill="#EE1D52"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M43.4589 27.5892C46.5241 29.7857 50.2019 30.9638 53.9729 30.9571V25.0166C51.8243 24.5623 49.8726 23.4452 48.3927 21.8226C47.1372 21.0414 46.0601 20.0048 45.2315 18.78C44.4029 17.5553 43.8412 16.1699 43.5831 14.7139H38.09V44.8018C38.0849 46.1336 37.6629 47.4304 36.8831 48.51C36.1034 49.5897 35.0051 50.3981 33.7425 50.8217C32.4798 51.2453 31.1162 51.2629 29.8431 50.872C28.57 50.4811 27.4512 49.7012 26.6439 48.642C25.3645 47.9965 24.3399 46.9387 23.7354 45.6394C23.1309 44.3401 22.9818 42.875 23.3121 41.4805C23.6424 40.0861 24.4329 38.8435 25.556 37.9535C26.6791 37.0634 28.0693 36.5776 29.5023 36.5745C30.1599 36.5766 30.8134 36.6772 31.4411 36.8728V30.8826C28.7288 30.9477 26.0946 31.8033 23.8617 33.3444C21.6289 34.8855 19.8946 37.0451 18.8717 39.5579C17.8489 42.0708 17.5821 44.8276 18.1039 47.49C18.6258 50.1524 19.9137 52.6045 21.8095 54.5453C23.9073 55.9459 26.3458 56.7512 28.8651 56.8755C31.3845 56.9997 33.8904 56.4383 36.1158 55.2509C38.3413 54.0636 40.2031 52.2948 41.5027 50.133C42.8024 47.9712 43.4913 45.4973 43.4962 42.9749L43.4589 27.5892Z" fill="black"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M53.9736 25.0161V23.4129C52.0005 23.4213 50.0655 22.8696 48.3934 21.8221C49.8695 23.4493 51.8229 24.5674 53.9736 25.0161ZM43.5838 14.7134C43.5838 14.4275 43.4968 14.1292 43.4596 13.8434V12.874H35.8785V42.9744C35.872 44.6598 35.197 46.2738 34.0017 47.4621C32.8064 48.6504 31.1885 49.3159 29.503 49.3126C28.5106 49.3176 27.5311 49.0876 26.6446 48.6415C27.4519 49.7007 28.5707 50.4805 29.8438 50.8715C31.1169 51.2624 32.4805 51.2448 33.7432 50.8212C35.0058 50.3976 36.1041 49.5892 36.8838 48.5095C37.6636 47.4298 38.0856 46.1331 38.0907 44.8013V14.7134H43.5838ZM31.4418 30.8696V29.167C28.3222 28.7432 25.1511 29.3885 22.4453 30.9977C19.7394 32.6069 17.6584 35.0851 16.5413 38.0284C15.4242 40.9718 15.337 44.2067 16.2938 47.206C17.2506 50.2053 19.195 52.792 21.8102 54.5448C19.9287 52.5995 18.6545 50.1484 18.1433 47.4908C17.6321 44.8333 17.906 42.0844 18.9315 39.5799C19.957 37.0755 21.6897 34.924 23.918 33.3882C26.1463 31.8524 28.7736 30.9988 31.4791 30.9318L31.4418 30.8696Z" fill="#69C9D0"/>
    </svg>
    

      </a>
      <a href="" aria-label="Find us on Instagram" target="_blank"
          rel="noopener">
          <svg class="transition-all duration-300 hover:scale-110 h-10 w-10" xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 71 72" fill="none">
    <path d="M12.5762 56.8405L15.8608 44.6381C13.2118 39.8847 12.3702 34.3378 13.4904 29.0154C14.6106 23.693 17.6176 18.952 21.9594 15.6624C26.3012 12.3729 31.6867 10.7554 37.1276 11.1068C42.5685 11.4582 47.6999 13.755 51.5802 17.5756C55.4604 21.3962 57.8292 26.4844 58.2519 31.9065C58.6746 37.3286 57.1228 42.7208 53.8813 47.0938C50.6399 51.4668 45.9261 54.5271 40.605 55.7133C35.284 56.8994 29.7125 56.1318 24.9131 53.5513L12.5762 56.8405ZM25.508 48.985L26.2709 49.4365C29.7473 51.4918 33.8076 52.3423 37.8191 51.8555C41.8306 51.3687 45.5681 49.5719 48.4489 46.7452C51.3298 43.9185 53.1923 40.2206 53.7463 36.2279C54.3002 32.2351 53.5143 28.1717 51.5113 24.6709C49.5082 21.1701 46.4003 18.4285 42.6721 16.8734C38.9438 15.3184 34.8045 15.0372 30.8993 16.0736C26.994 17.11 23.5422 19.4059 21.0817 22.6035C18.6212 25.801 17.2903 29.7206 17.2963 33.7514C17.293 37.0937 18.2197 40.3712 19.9732 43.2192L20.4516 44.0061L18.6153 50.8167L25.508 48.985Z" fill="#00D95F"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M44.0259 36.8847C43.5787 36.5249 43.0549 36.2716 42.4947 36.1442C41.9344 36.0168 41.3524 36.0186 40.793 36.1495C39.9524 36.4977 39.4093 37.8134 38.8661 38.4713C38.7516 38.629 38.5833 38.7396 38.3928 38.7823C38.2024 38.8251 38.0028 38.797 37.8316 38.7034C34.7543 37.5012 32.1748 35.2965 30.5122 32.4475C30.3704 32.2697 30.3033 32.044 30.325 31.8178C30.3467 31.5916 30.4555 31.3827 30.6286 31.235C31.2344 30.6368 31.6791 29.8959 31.9218 29.0809C31.9756 28.1818 31.7691 27.2863 31.3269 26.5011C30.985 25.4002 30.3344 24.42 29.4518 23.6762C28.9966 23.472 28.4919 23.4036 27.9985 23.4791C27.5052 23.5546 27.0443 23.7709 26.6715 24.1019C26.0242 24.6589 25.5104 25.3537 25.168 26.135C24.8256 26.9163 24.6632 27.7643 24.6929 28.6165C24.6949 29.0951 24.7557 29.5716 24.8739 30.0354C25.1742 31.1497 25.636 32.2144 26.2447 33.1956C26.6839 33.9473 27.163 34.6749 27.6801 35.3755C29.3607 37.6767 31.4732 39.6305 33.9003 41.1284C35.1183 41.8897 36.42 42.5086 37.7799 42.973C39.1924 43.6117 40.752 43.8568 42.2931 43.6824C43.1711 43.5499 44.003 43.2041 44.7156 42.6755C45.4281 42.1469 45.9995 41.4518 46.3795 40.6512C46.6028 40.1675 46.6705 39.6269 46.5735 39.1033C46.3407 38.0327 44.9053 37.4007 44.0259 36.8847Z" fill="#00D95F"/>
    </svg>

      </a>
      <a href="" aria-label="Find us on Instagram" target="_blank"
          rel="noopener">
          <svg class="transition-all duration-300 hover:scale-110" xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 72 72" fill="none">
      <path d="M40.7568 32.1716L59.3704 11H54.9596L38.7974 29.383L25.8887 11H11L30.5205 38.7983L11 61H15.4111L32.4788 41.5869L46.1113 61H61L40.7557 32.1716H40.7568ZM34.7152 39.0433L32.7374 36.2752L17.0005 14.2492H23.7756L36.4755 32.0249L38.4533 34.7929L54.9617 57.8986H48.1865L34.7152 39.0443V39.0433Z" fill="black"/>
    </svg>
      </a>
      
  </div>
</div>
</div>
    </div>
    
</div>

  

<div class="flex-shrink-0 m-6 relative overflow-hidden rounded-md max-w-xs shadow-md shadow-gray-600 group bg-white">
  <div class="relative"><a href="#">
              <img class="w-full"
                  src="./assets/TeamImage/user-01.png"
                  alt="">
              <div
                  class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25">
              </div>
          </a>
      </div>
    <div class="relative  flex items-center justify-center transition-transform flex-col">
        
      <div class="px-6 py-4 mb-auto">
          <a href="#"
              class="font-medium text-lg inline-block hover:text-blue-500 transition duration-500 ease-in-out  mb-2">Mr. Geleta Tesema</a>
          <p class="text-gray-500 text-sm">
              Marketing Manager
          </p>
      </div>
      <div class="px-6 py-3 flex flex-row items-center justify-center bg-gray-100">
        <div class=" flex items-center justify-center  ">
  <div class="flex items-center justify-center gap-x-5 ">
      <a href="" aria-label="Find us on LinkedIn"
          target="_blank" rel="noopener" class=" rounded-md ">
          <svg class="transition-all duration-300 hover:scale-110 h-10 w-10"
    xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 72 72" fill="none">
      <path d="M46.4927 38.6403L47.7973 30.3588H39.7611V24.9759C39.7611 22.7114 40.883 20.4987 44.4706 20.4987H48.1756V13.4465C46.018 13.1028 43.8378 12.9168 41.6527 12.8901C35.0385 12.8901 30.7204 16.8626 30.7204 24.0442V30.3588H23.3887V38.6403H30.7204V58.671H39.7611V38.6403H46.4927Z" fill="#337FFF"/>
    </svg>

      </a>
      <a href="" aria-label="Find us on Twitter" target="_blank" rel="noopener"  class=" rounded-md ">
        <svg class="transition-all duration-300 hover:scale-110 h-10 w-10" width="28" height="28" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M27.4456 35.7808C27.4456 31.1786 31.1776 27.4468 35.7826 27.4468C40.3875 27.4468 44.1216 31.1786 44.1216 35.7808C44.1216 40.383 40.3875 44.1148 35.7826 44.1148C31.1776 44.1148 27.4456 40.383 27.4456 35.7808ZM22.9377 35.7808C22.9377 42.8708 28.6883 48.618 35.7826 48.618C42.8768 48.618 48.6275 42.8708 48.6275 35.7808C48.6275 28.6908 42.8768 22.9436 35.7826 22.9436C28.6883 22.9436 22.9377 28.6908 22.9377 35.7808ZM46.1342 22.4346C46.1339 23.0279 46.3098 23.608 46.6394 24.1015C46.9691 24.595 47.4377 24.9797 47.9861 25.2069C48.5346 25.4342 49.1381 25.4939 49.7204 25.3784C50.3028 25.2628 50.8378 24.9773 51.2577 24.5579C51.6777 24.1385 51.9638 23.6041 52.0799 23.0222C52.1959 22.4403 52.1367 21.8371 51.9097 21.2888C51.6828 20.7406 51.2982 20.2719 50.8047 19.942C50.3112 19.6122 49.7309 19.436 49.1372 19.4358H49.136C48.3402 19.4361 47.5771 19.7522 47.0142 20.3144C46.4514 20.8767 46.1349 21.6392 46.1342 22.4346ZM25.6765 56.1302C23.2377 56.0192 21.9121 55.6132 21.0311 55.2702C19.8632 54.8158 19.0299 54.2746 18.1538 53.4002C17.2777 52.5258 16.7354 51.6938 16.2827 50.5266C15.9393 49.6466 15.533 48.3214 15.4222 45.884C15.3009 43.2488 15.2767 42.4572 15.2767 35.781C15.2767 29.1048 15.3029 28.3154 15.4222 25.678C15.5332 23.2406 15.9425 21.918 16.2827 21.0354C16.7374 19.8682 17.2789 19.0354 18.1538 18.1598C19.0287 17.2842 19.8612 16.7422 21.0311 16.2898C21.9117 15.9466 23.2377 15.5406 25.6765 15.4298C28.3133 15.3086 29.1054 15.2844 35.7826 15.2844C42.4598 15.2844 43.2527 15.3106 45.8916 15.4298C48.3305 15.5408 49.6539 15.9498 50.537 16.2898C51.7049 16.7422 52.5382 17.2854 53.4144 18.1598C54.2905 19.0342 54.8308 19.8682 55.2855 21.0354C55.6289 21.9154 56.0351 23.2406 56.146 25.678C56.2673 28.3154 56.2915 29.1048 56.2915 35.781C56.2915 42.4572 56.2673 43.2466 56.146 45.884C56.0349 48.3214 55.6267 49.6462 55.2855 50.5266C54.8308 51.6938 54.2893 52.5266 53.4144 53.4002C52.5394 54.2738 51.7049 54.8158 50.537 55.2702C49.6565 55.6134 48.3305 56.0194 45.8916 56.1302C43.2549 56.2514 42.4628 56.2756 35.7826 56.2756C29.1024 56.2756 28.3125 56.2514 25.6765 56.1302ZM25.4694 10.9322C22.8064 11.0534 20.9867 11.4754 19.3976 12.0934C17.7518 12.7316 16.3585 13.5878 14.9663 14.977C13.5741 16.3662 12.7195 17.7608 12.081 19.4056C11.4626 20.9948 11.0403 22.8124 10.9191 25.4738C10.7958 28.1394 10.7676 28.9916 10.7676 35.7808C10.7676 42.57 10.7958 43.4222 10.9191 46.0878C11.0403 48.7494 11.4626 50.5668 12.081 52.156C12.7195 53.7998 13.5743 55.196 14.9663 56.5846C16.3583 57.9732 17.7518 58.8282 19.3976 59.4682C20.9897 60.0862 22.8064 60.5082 25.4694 60.6294C28.138 60.7506 28.9893 60.7808 35.7826 60.7808C42.5759 60.7808 43.4286 60.7526 46.0958 60.6294C48.759 60.5082 50.5774 60.0862 52.1676 59.4682C53.8124 58.8282 55.2066 57.9738 56.5989 56.5846C57.9911 55.1954 58.8438 53.7998 59.4842 52.156C60.1026 50.5668 60.5268 48.7492 60.6461 46.0878C60.7674 43.4202 60.7956 42.57 60.7956 35.7808C60.7956 28.9916 60.7674 28.1394 60.6461 25.4738C60.5248 22.8122 60.1026 20.9938 59.4842 19.4056C58.8438 17.7618 57.9889 16.3684 56.5989 14.977C55.2088 13.5856 53.8124 12.7316 52.1696 12.0934C50.5775 11.4754 48.7588 11.0514 46.0978 10.9322C43.4306 10.811 42.5779 10.7808 35.7846 10.7808C28.9913 10.7808 28.138 10.809 25.4694 10.9322Z" fill="url(#paint0_radial_7092_54471)"/>
      <path d="M27.4456 35.7808C27.4456 31.1786 31.1776 27.4468 35.7826 27.4468C40.3875 27.4468 44.1216 31.1786 44.1216 35.7808C44.1216 40.383 40.3875 44.1148 35.7826 44.1148C31.1776 44.1148 27.4456 40.383 27.4456 35.7808ZM22.9377 35.7808C22.9377 42.8708 28.6883 48.618 35.7826 48.618C42.8768 48.618 48.6275 42.8708 48.6275 35.7808C48.6275 28.6908 42.8768 22.9436 35.7826 22.9436C28.6883 22.9436 22.9377 28.6908 22.9377 35.7808ZM46.1342 22.4346C46.1339 23.0279 46.3098 23.608 46.6394 24.1015C46.9691 24.595 47.4377 24.9797 47.9861 25.2069C48.5346 25.4342 49.1381 25.4939 49.7204 25.3784C50.3028 25.2628 50.8378 24.9773 51.2577 24.5579C51.6777 24.1385 51.9638 23.6041 52.0799 23.0222C52.1959 22.4403 52.1367 21.8371 51.9097 21.2888C51.6828 20.7406 51.2982 20.2719 50.8047 19.942C50.3112 19.6122 49.7309 19.436 49.1372 19.4358H49.136C48.3402 19.4361 47.5771 19.7522 47.0142 20.3144C46.4514 20.8767 46.1349 21.6392 46.1342 22.4346ZM25.6765 56.1302C23.2377 56.0192 21.9121 55.6132 21.0311 55.2702C19.8632 54.8158 19.0299 54.2746 18.1538 53.4002C17.2777 52.5258 16.7354 51.6938 16.2827 50.5266C15.9393 49.6466 15.533 48.3214 15.4222 45.884C15.3009 43.2488 15.2767 42.4572 15.2767 35.781C15.2767 29.1048 15.3029 28.3154 15.4222 25.678C15.5332 23.2406 15.9425 21.918 16.2827 21.0354C16.7374 19.8682 17.2789 19.0354 18.1538 18.1598C19.0287 17.2842 19.8612 16.7422 21.0311 16.2898C21.9117 15.9466 23.2377 15.5406 25.6765 15.4298C28.3133 15.3086 29.1054 15.2844 35.7826 15.2844C42.4598 15.2844 43.2527 15.3106 45.8916 15.4298C48.3305 15.5408 49.6539 15.9498 50.537 16.2898C51.7049 16.7422 52.5382 17.2854 53.4144 18.1598C54.2905 19.0342 54.8308 19.8682 55.2855 21.0354C55.6289 21.9154 56.0351 23.2406 56.146 25.678C56.2673 28.3154 56.2915 29.1048 56.2915 35.781C56.2915 42.4572 56.2673 43.2466 56.146 45.884C56.0349 48.3214 55.6267 49.6462 55.2855 50.5266C54.8308 51.6938 54.2893 52.5266 53.4144 53.4002C52.5394 54.2738 51.7049 54.8158 50.537 55.2702C49.6565 55.6134 48.3305 56.0194 45.8916 56.1302C43.2549 56.2514 42.4628 56.2756 35.7826 56.2756C29.1024 56.2756 28.3125 56.2514 25.6765 56.1302ZM25.4694 10.9322C22.8064 11.0534 20.9867 11.4754 19.3976 12.0934C17.7518 12.7316 16.3585 13.5878 14.9663 14.977C13.5741 16.3662 12.7195 17.7608 12.081 19.4056C11.4626 20.9948 11.0403 22.8124 10.9191 25.4738C10.7958 28.1394 10.7676 28.9916 10.7676 35.7808C10.7676 42.57 10.7958 43.4222 10.9191 46.0878C11.0403 48.7494 11.4626 50.5668 12.081 52.156C12.7195 53.7998 13.5743 55.196 14.9663 56.5846C16.3583 57.9732 17.7518 58.8282 19.3976 59.4682C20.9897 60.0862 22.8064 60.5082 25.4694 60.6294C28.138 60.7506 28.9893 60.7808 35.7826 60.7808C42.5759 60.7808 43.4286 60.7526 46.0958 60.6294C48.759 60.5082 50.5774 60.0862 52.1676 59.4682C53.8124 58.8282 55.2066 57.9738 56.5989 56.5846C57.9911 55.1954 58.8438 53.7998 59.4842 52.156C60.1026 50.5668 60.5268 48.7492 60.6461 46.0878C60.7674 43.4202 60.7956 42.57 60.7956 35.7808C60.7956 28.9916 60.7674 28.1394 60.6461 25.4738C60.5248 22.8122 60.1026 20.9938 59.4842 19.4056C58.8438 17.7618 57.9889 16.3684 56.5989 14.977C55.2088 13.5856 53.8124 12.7316 52.1696 12.0934C50.5775 11.4754 48.7588 11.0514 46.0978 10.9322C43.4306 10.811 42.5779 10.7808 35.7846 10.7808C28.9913 10.7808 28.138 10.809 25.4694 10.9322Z" fill="url(#paint1_radial_7092_54471)"/>
      <defs>
      <radialGradient id="paint0_radial_7092_54471" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(17.4144 61.017) scale(65.31 65.2708)">
      <stop offset="0.09" stop-color="#FA8F21"/>
      <stop offset="0.78" stop-color="#D82D7E"/>
      </radialGradient>
      <radialGradient id="paint1_radial_7092_54471" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(41.1086 63.257) scale(51.4733 51.4424)">
      <stop offset="0.64" stop-color="#8C3AAA" stop-opacity="0"/>
      <stop offset="1" stop-color="#8C3AAA"/>
      </radialGradient>
      </defs>
      </svg>

      </a>
      <a href="" aria-label="Find us on Facebook" target="_blank"
          rel="noopener">
          <svg class="transition-all duration-300 hover:scale-110 h-10 w-10" width="28" height="28" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M45.6721 29.4285C48.7387 31.6085 52.4112 32.7733 56.1737 32.7592V25.3024C55.434 25.3045 54.6963 25.2253 53.9739 25.0663V31.0068C50.203 31.0135 46.5252 29.8354 43.4599 27.6389V42.9749C43.4507 45.4914 42.7606 47.9585 41.4628 50.1146C40.165 52.2706 38.3079 54.0353 36.0885 55.2215C33.8691 56.4076 31.37 56.9711 28.8563 56.852C26.3426 56.733 23.9079 55.9359 21.8105 54.5453C23.7506 56.5082 26.2295 57.8513 28.9333 58.4044C31.6372 58.9576 34.4444 58.6959 36.9994 57.6526C39.5545 56.6093 41.7425 54.8312 43.2864 52.5436C44.8302 50.256 45.6605 47.5616 45.6721 44.8018V29.4285ZM48.3938 21.8226C46.8343 20.1323 45.8775 17.9739 45.6721 15.6832V14.7139H43.5842C43.8423 16.1699 44.4039 17.5553 45.2326 18.78C46.0612 20.0048 47.1383 21.0414 48.3938 21.8226ZM26.645 48.642C25.9213 47.6957 25.4779 46.5653 25.365 45.3793C25.2522 44.1934 25.4746 42.9996 26.0068 41.9338C26.5391 40.8681 27.3598 39.9731 28.3757 39.3508C29.3915 38.7285 30.5616 38.4039 31.7529 38.4139C32.4106 38.4137 33.0644 38.5143 33.6916 38.7121V31.0068C32.9584 30.9097 32.2189 30.8682 31.4794 30.8826V36.8728C29.9522 36.39 28.2992 36.4998 26.8492 37.1803C25.3992 37.8608 24.2585 39.0621 23.6539 40.5454C23.0494 42.0286 23.0252 43.6851 23.5864 45.1853C24.1475 46.6855 25.2527 47.9196 26.6823 48.642H26.645Z" fill="#EE1D52"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M43.4589 27.5892C46.5241 29.7857 50.2019 30.9638 53.9729 30.9571V25.0166C51.8243 24.5623 49.8726 23.4452 48.3927 21.8226C47.1372 21.0414 46.0601 20.0048 45.2315 18.78C44.4029 17.5553 43.8412 16.1699 43.5831 14.7139H38.09V44.8018C38.0849 46.1336 37.6629 47.4304 36.8831 48.51C36.1034 49.5897 35.0051 50.3981 33.7425 50.8217C32.4798 51.2453 31.1162 51.2629 29.8431 50.872C28.57 50.4811 27.4512 49.7012 26.6439 48.642C25.3645 47.9965 24.3399 46.9387 23.7354 45.6394C23.1309 44.3401 22.9818 42.875 23.3121 41.4805C23.6424 40.0861 24.4329 38.8435 25.556 37.9535C26.6791 37.0634 28.0693 36.5776 29.5023 36.5745C30.1599 36.5766 30.8134 36.6772 31.4411 36.8728V30.8826C28.7288 30.9477 26.0946 31.8033 23.8617 33.3444C21.6289 34.8855 19.8946 37.0451 18.8717 39.5579C17.8489 42.0708 17.5821 44.8276 18.1039 47.49C18.6258 50.1524 19.9137 52.6045 21.8095 54.5453C23.9073 55.9459 26.3458 56.7512 28.8651 56.8755C31.3845 56.9997 33.8904 56.4383 36.1158 55.2509C38.3413 54.0636 40.2031 52.2948 41.5027 50.133C42.8024 47.9712 43.4913 45.4973 43.4962 42.9749L43.4589 27.5892Z" fill="black"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M53.9736 25.0161V23.4129C52.0005 23.4213 50.0655 22.8696 48.3934 21.8221C49.8695 23.4493 51.8229 24.5674 53.9736 25.0161ZM43.5838 14.7134C43.5838 14.4275 43.4968 14.1292 43.4596 13.8434V12.874H35.8785V42.9744C35.872 44.6598 35.197 46.2738 34.0017 47.4621C32.8064 48.6504 31.1885 49.3159 29.503 49.3126C28.5106 49.3176 27.5311 49.0876 26.6446 48.6415C27.4519 49.7007 28.5707 50.4805 29.8438 50.8715C31.1169 51.2624 32.4805 51.2448 33.7432 50.8212C35.0058 50.3976 36.1041 49.5892 36.8838 48.5095C37.6636 47.4298 38.0856 46.1331 38.0907 44.8013V14.7134H43.5838ZM31.4418 30.8696V29.167C28.3222 28.7432 25.1511 29.3885 22.4453 30.9977C19.7394 32.6069 17.6584 35.0851 16.5413 38.0284C15.4242 40.9718 15.337 44.2067 16.2938 47.206C17.2506 50.2053 19.195 52.792 21.8102 54.5448C19.9287 52.5995 18.6545 50.1484 18.1433 47.4908C17.6321 44.8333 17.906 42.0844 18.9315 39.5799C19.957 37.0755 21.6897 34.924 23.918 33.3882C26.1463 31.8524 28.7736 30.9988 31.4791 30.9318L31.4418 30.8696Z" fill="#69C9D0"/>
    </svg>
    

      </a>
      <a href="" aria-label="Find us on Instagram" target="_blank"
          rel="noopener">
          <svg class="transition-all duration-300 hover:scale-110 h-10 w-10" xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 71 72" fill="none">
    <path d="M12.5762 56.8405L15.8608 44.6381C13.2118 39.8847 12.3702 34.3378 13.4904 29.0154C14.6106 23.693 17.6176 18.952 21.9594 15.6624C26.3012 12.3729 31.6867 10.7554 37.1276 11.1068C42.5685 11.4582 47.6999 13.755 51.5802 17.5756C55.4604 21.3962 57.8292 26.4844 58.2519 31.9065C58.6746 37.3286 57.1228 42.7208 53.8813 47.0938C50.6399 51.4668 45.9261 54.5271 40.605 55.7133C35.284 56.8994 29.7125 56.1318 24.9131 53.5513L12.5762 56.8405ZM25.508 48.985L26.2709 49.4365C29.7473 51.4918 33.8076 52.3423 37.8191 51.8555C41.8306 51.3687 45.5681 49.5719 48.4489 46.7452C51.3298 43.9185 53.1923 40.2206 53.7463 36.2279C54.3002 32.2351 53.5143 28.1717 51.5113 24.6709C49.5082 21.1701 46.4003 18.4285 42.6721 16.8734C38.9438 15.3184 34.8045 15.0372 30.8993 16.0736C26.994 17.11 23.5422 19.4059 21.0817 22.6035C18.6212 25.801 17.2903 29.7206 17.2963 33.7514C17.293 37.0937 18.2197 40.3712 19.9732 43.2192L20.4516 44.0061L18.6153 50.8167L25.508 48.985Z" fill="#00D95F"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M44.0259 36.8847C43.5787 36.5249 43.0549 36.2716 42.4947 36.1442C41.9344 36.0168 41.3524 36.0186 40.793 36.1495C39.9524 36.4977 39.4093 37.8134 38.8661 38.4713C38.7516 38.629 38.5833 38.7396 38.3928 38.7823C38.2024 38.8251 38.0028 38.797 37.8316 38.7034C34.7543 37.5012 32.1748 35.2965 30.5122 32.4475C30.3704 32.2697 30.3033 32.044 30.325 31.8178C30.3467 31.5916 30.4555 31.3827 30.6286 31.235C31.2344 30.6368 31.6791 29.8959 31.9218 29.0809C31.9756 28.1818 31.7691 27.2863 31.3269 26.5011C30.985 25.4002 30.3344 24.42 29.4518 23.6762C28.9966 23.472 28.4919 23.4036 27.9985 23.4791C27.5052 23.5546 27.0443 23.7709 26.6715 24.1019C26.0242 24.6589 25.5104 25.3537 25.168 26.135C24.8256 26.9163 24.6632 27.7643 24.6929 28.6165C24.6949 29.0951 24.7557 29.5716 24.8739 30.0354C25.1742 31.1497 25.636 32.2144 26.2447 33.1956C26.6839 33.9473 27.163 34.6749 27.6801 35.3755C29.3607 37.6767 31.4732 39.6305 33.9003 41.1284C35.1183 41.8897 36.42 42.5086 37.7799 42.973C39.1924 43.6117 40.752 43.8568 42.2931 43.6824C43.1711 43.5499 44.003 43.2041 44.7156 42.6755C45.4281 42.1469 45.9995 41.4518 46.3795 40.6512C46.6028 40.1675 46.6705 39.6269 46.5735 39.1033C46.3407 38.0327 44.9053 37.4007 44.0259 36.8847Z" fill="#00D95F"/>
    </svg>

      </a>
      <a href="" aria-label="Find us on Instagram" target="_blank"
          rel="noopener">
          <svg class="transition-all duration-300 hover:scale-110" xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 72 72" fill="none">
      <path d="M40.7568 32.1716L59.3704 11H54.9596L38.7974 29.383L25.8887 11H11L30.5205 38.7983L11 61H15.4111L32.4788 41.5869L46.1113 61H61L40.7557 32.1716H40.7568ZM34.7152 39.0433L32.7374 36.2752L17.0005 14.2492H23.7756L36.4755 32.0249L38.4533 34.7929L54.9617 57.8986H48.1865L34.7152 39.0443V39.0433Z" fill="black"/>
    </svg>
      </a>
      
  </div>
</div>
</div>
    </div>
    
</div>
</div>

</div>
</div>
</section>
 
<!-- partners list section -->

 <section id="partner" class="bg-transparent  h-full w-full flex justify-center items-center dark:bg-gray-900 p-8">
   
  
    <div class="max-w-screen-xl px-4 pb-8 mx-auto lg:pb-16 place-content-center mt-0">
      <div class="justify-center flex m-4 underline-offset-4">
      <h1 class="text-2xl md:text-3xl pl-2 pr-2 my-2 border-b-[4px]  text-black      font-sans font-bold border-teal-300  dark:text-gray-200 ">
    Our Partners
</h1>

</div>

        <div class="grid grid-cols-2 gap-8 text-gray-500 sm:gap-12 sm:grid-cols-3 lg:grid-cols-auto dark:text-gray-400 align-center ">
        
            <a class="flex items-center lg:justify-center" target="_blank">
                <img src="./assets/PartnersLogo/oroagrilogo.jpg">
            </a>
            <a class="flex items-center lg:justify-center" target="_blank">
                <img src="./assets/PartnersLogo/oromia-irrigation-and-pastoral-development-bureau-oipdb-390024.jpg">
            </a>
            <a class="flex items-center lg:justify-center" target="_blank">
                <img src="./assets/PartnersLogo/ECX_Logo.jpg">
            </a>
         
        </div>
     
    </div>
 
</section>
 <!-- Contact us form and details section -->
<section id="contact" class="py-24">
      <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 </div>">
        <div class="grid lg:grid-cols-2 grid-cols-1">
            <div class="lg:mb-0 mb-10 flex w-fit">
                
              <div class="flex items-center justify-center">
                    <div class="max-w-full mx-auto rounded-lg overflow-hidden">
                        <div class="px-6 py-4">
                            <h3 class="text-lg  text-gray-900 font-bold">Our Address</h3>
                            <p class="mt-1 text-gray-600">Bule Hore, Oromia, Ethiopia</p>
                        </div>
                        <div class="border-t border-gray-200 px-6 py-4">
                            <h3 class="text-lg font-bold text-gray-900">Hours</h3>
                            <p class="mt-1 text-gray-600">Monday - Friday: 2:00 - 11:00</p>
                            <p class="mt-1 text-gray-600">Saturday: 3:00 - 10:00</p>
                            <p class="mt-1 text-gray-600">Sunday: Closed</p>
                        </div>
                        <div class="border-t border-gray-200 px-6 py-4">
                            <h3 class="text-lg font-medium text-gray-900">Contact</h3>
                            <p class="mt-1 text-gray-600">Email: <a href="">info@example.com</a></p>
                            <p class="mt-1 text-gray-600">Phone: +251 987654321</p>
                        </div>
                    </div>
                    </div>
              
                
            </div>

            <div class="bg-gray-100 p-5 lg:p-11 lg:rounded-r-2xl rounded-2xl">
              <div class="p-8  max-w-lg mx-auto">
    <h1 class="text-4xl text-gray-800 sm:text-4xl font-bold mb-4">Contact Form</h1>
    <form>
        <div class="p-2 w-full">
            <div class="relative">
                <label for="name" class="leading-7 py-4 text-lg text-gray-900">Name</label>
                <input type="text" id="name" name="name" required=""
                    class=" w-full bg-white rounded border border-gray-400 focus:border-blue-500 focus:bg-white focus:ring-2 focus:ring-blue-200 text-base outline-none text-gray-900 py-1 px-1 leading-8 transition-colors duration-200 ease-in-out ">
            </div>
        </div>
        <div class="p-2 w-full">
            <div class="relative">
                <label for="email" class="leading-7 py-4 text-lg text-gray-900">Email</label>
                <input type="email" id="email" name="email" required=""
                    class=" w-full bg-white rounded border border-gray-400 focus:border-blue-500 focus:bg-white focus:ring-2 focus:ring-blue-200 text-base outline-none text-gray-900 py-1 px-1 leading-8 transition-colors duration-200 ease-in-out">
            </div>
        </div>
        <div class="p-2 w-full">
            <div class="relative">
                <label for="message" class="leading-7 py-4 text-lg text-gray-900">Message</label>
                <textarea id="message" name="message" required=""
                    class=" w-full bg-white rounded border border-gray-400 focus:border-blue-500 focus:bg-white focus:ring-2 focus:ring-blue-200 h-32 text-base outline-none text-gray-900 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
            </div>
        </div>
        <div class="p-2 w-full">
            <div>
                <button type="submit"
                    class="flex text-white bg-gray-900 border-0 py-3 px-6 focus:outline-none hover:bg-blue-900 rounded text-xl font-bold shadow-lg mx-0 flex-col text-center">
                    Send
                </button>
            </div>
            </div>
    </form>
</div>
</div>
      </div>
      </div>
    </section>

<!-- footer page -->

 <footer class="bg-gray-800 text-white py-4 px-3 mb-0 ">
    <div class="container mx-auto flex flex-wrap items-center justify-between">
        <div class="w-full md:w-1/2 md:text-center md:mb-0 mb-8 flex flex-row  gap-10">
            <p class="text-xs text-gray-400 md:text-sm">Copyright 2024 &copy; All Rights Reserved</p>
            <p class="text-xs text-gray-400 md:text-sm mt-auto mb-0">Designed by: <a href="https://t.me/Bksmile">Foora Technologies Plc</a> </p>
        </div>
        <div class="w-full md:w-1/2 md:text-center md:mb-0 mb-8">
            <ul class="list-reset flex justify-center flex-wrap text-xs md:text-sm gap-3">
                <li><a href="#" class="text-gray-400 hover:text-white">Contact</a></li>
                <li class="mx-4"><a href="#" class="text-gray-400 hover:text-white">Privacy Policy</a></li>
                <li><a href="#" class="text-gray-400 hover:text-white">Terms of Use</a></li>
                
            </ul>
        </div>
    </div>
</footer>
</div>
</template>
<script> document.addEventListener('DOMContentLoaded', function() { const menuToggle = document.getElementById('menu-toggle'); const menu = document.getElementById('menu'); menuToggle.addEventListener('change', function() { if (menuToggle.checked) { menu.classList.remove('hidden'); } else { menu.classList.add('hidden'); } }); }); </script>
<style> #menu-toggle:checked + #menu { display: block; } </style>