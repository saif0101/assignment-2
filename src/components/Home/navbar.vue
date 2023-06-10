<template>
    <nav class="bg-[#001844] text-white font-openSans border-b border-[#6D6E70]/20">
      <div class=" ">
        <div class="max-w-[1170px] mx-auto px-5 xl:px-0">
          <header class="">
            <div class="relative px-2 py-4">
              <div class="mx-auto flex justify-between items-center">
                <div class="flex justify-between items-center gap-x-11">
                  <a class="font-bold">
                      YOUR LOGO
                  </a>
  
                 
                </div>
                <div>
                    <ul class="hidden lg:flex items-center justify-between space-x-8 text-base">
                    <li class="">
                      <a class="">All Resources </a>
                    </li>
                    <li>
                        <button class="border border-white py-1 px-5 rounded-full">log in</button>
                    </li>

  
                  </ul>
                </div>
  
              
  
                <!-- Mobile menu icon -->
  
                <div class="lg:hidden z-10">
                  <!-- Mobile menu icon -->
                  <button id="mobile-icon">
                    <svg
                      onclick="changeIcon(this)"
                      width="18"
                      height="12"
                      viewBox="0 0 18 12"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M17 5H1C0.4 5 0 5.4 0 6C0 6.6 0.4 7 1 7H17C17.6 7 18 6.6 18 6C18 5.4 17.6 5 17 5ZM1 2H17C17.6 2 18 1.6 18 1C18 0.4 17.6 0 17 0H1C0.4 0 0 0.4 0 1C0 1.6 0.4 2 1 2ZM17 10H1C0.4 10 0 10.4 0 11C0 11.6 0.4 12 1 12H17C17.6 12 18 11.6 18 11C18 10.4 17.6 10 17 10Z"
                        fill="white"
                      />
                    </svg>
                  </button>
                </div>
              </div>
  
              <!-- Mobile menu -->
              <div id="app" class="lg:hidden flex justify-center mt-3 w-full relative z-10">
                <div id="mobile-menu" class="mobile-menu absolute top-23 w-screen">
                  <!-- add hidden here later -->
                  <ul class="bg-[#181818] shadow-lg leading-9 h-screen space-y-3 py-4 pl-4">
                    <li class="flex items-center relative">
                      <a class="text-[#8C8D8F] font-medium text-[15px] leading-4" href="#">
                        <div>
                        
                        </div>
                      </a>
                    </li>
  
                    <li class="pt-4">
                      <div class=" ">
                        <li class="">
                          <a
                         
                            class="font-semibold text-[#8C8D8F]"
                            >All Resources
                          </a>
                        </li>
                      </div>
                    </li>
  
                    <li class="pt-4">
                      <div class=" ">
                        <Link
                          
                          class="text-[#8C8D8F] font-medium text-[15px] leading-4"
                          >Pricing
                        </Link>
                      </div>
                    </li>
  
                    <li
                     
                      class="flex items-center gap-x-3 pl-4 pt-[30%]"
                    >
                      <button
                 
                        class="py-[10px] px-[14px] text-[#8C8D8F] font-medium text-[16px] leading-4 rounded-[4px]"
                      >
                        Sign In
                      </button>
  
                      <button
                  
                        class="rounded-md py-2 px-5 cursor-pointer z-10 bg-[#2D68FF]"
                      >
                        Hire us
                      </button>
                    </li>
  
                  
                  </ul>
                </div>
              </div>
            </div>
          </header>
        </div>
      </div>
  
     
    </nav>
  </template>
  
  <script setup>
 import { onMounted } from "vue";

  
  const openCloseMenu = () => {
    document.getElementById("mobile-menu").classList.toggle("block");
    document.getElementById("mobile-menu").classList.toggle("active");
  };
  
  const changeIcon = (icon) => {
    icon.classList.toggle("fa-xmark");
  };
  
  onMounted(() => {
    document.getElementById("mobile-icon").addEventListener("click", openCloseMenu);
  });
  </script>
  
  <style>
  .mobile-menu {
    left: -200%;
    transition: 0.5s;
  }
  
  .mobile-menu.active {
    left: -30px;
    background-color: white;
  }
  
  .mobile-menu ul li ul {
    display: none;
  }
  
  .mobile-menu ul li:hover ul {
    display: block;
  }
  </style>
  