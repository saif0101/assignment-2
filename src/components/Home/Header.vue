<template>
    <header >
        <div class="hero-background bg-cover bg-no-repeat font-openSans text-white relative">
          <div class="custome-container">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-y-5 items-center  ">
                <div class="lg:py-10">
                    <h6 class="text-[26px] leading-[30px] font bold">Products</h6>
                    <h1 class="text-[26px] leading-[30px] md:text-[40px] md:leading-[60px] lg:text-[56px] lg:leading-[72px] font-light">Our Products</h1>
                    <p class="mt-5">Our company medicines treat serious illnesses and typically address diseases with a limited number of treatment options. With a presence in approximately 100 countries, we are proud to have reached millions of people with our products.</p>

                    <div class="flex flex-col sm:flex-row gap-4 mt-5">
                        <button class="text-[16px] leading-[16px] font-bold bg-white py-4 px-6 rounded-full text-[#001844] sm:w-fit">Our Products area</button>
                        <button class="text-[16px] leading-[16px] font-bold border border-white py-4 px-10 rounded-full text-white sm:w-fit">Products A-Z</button>

                    </div>
                    
                </div>

                <div class=" ">
                    <figure class="hidden xl:block lg:absolute  top-0 right-0 bottom-0">
                        <img class="h-full" src="../../assets/pexels-anna-shvets-3683102.png" alt="">
                    </figure>
                </div>

            </div>

          </div>
        </div>
    </header>
</template>
<style>
   .hero-background{
      background-image: url('../../assets/dt-bg.jpg');
   }
</style>