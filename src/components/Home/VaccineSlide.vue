<style>
.vaccineSlide .swiper {
  padding-bottom: 50px;
 
}
.vaccineSlide .swiper .swiper-slide-active {
  border: 1px solid #001844;
  border-radius: 8px;
 
}

.vaccineSlide .swiper-pagination-bullet-active {
  background: #1d2223;
}
.vaccineSlide .swiper-pagination-bullet {
  width: 24px;
  height: 2px;
  
}

.vaccineSlide .swiper-button-prev{
  left:24% !important;
 right: auto !important;
}
.vaccineSlide .swiper-button-next{
  left:auto!important;
 right: 68% !important;
 margin-top: -10px;
 
}
.vaccineSlide .swiper-button-prev:after{
          content: url('https://besnik-space.fra1.cdn.digitaloceanspaces.com/ezytor/theme/LuSyUKGTw9g3noD74ile1674146319.png') !important;
          display: none;
        }
.vaccineSlide .swiper-button-next:after{
          content: url('https://besnik-space.fra1.cdn.digitaloceanspaces.com/ezytor/theme/8bmWnhOTJfwlOQETS3cI1674146319.png') !important;
  display: none;
        }

        @media only screen and (min-width: 1024px) {
  .vaccineSlide .swiper {
  padding-bottom: 50px;
  margin-right:-15%;
}
.vaccineSlide .swiper-button-prev:after{
          display: block;
        }
.vaccineSlide .swiper-button-next:after{
  display: block;
        }

}

</style>


<template>
  <div class="vaccineSlide relative overflow-visible">
    <div class="custome-container font-openSans ">
    <div class="grid grid-cols-1 lg:grid-cols-3 items-center gap-3">
      <div class="">
        <h2 class="h1-semibold text-[50px] text-[#001844]">Our vaccines and medicines</h2>
        <p class="text-[#001844] mt-4">
          Getting ahead means preventing disease as well as treating it. Our R&D
          focus is to deliver new vaccines and medicines using the science of
          the immune system, human genetics and advanced technologies.
        </p>
        <div class="flex items-center gap-2 mt-5">
          <a class="text-[16px] leading-[20px] font-bold underline" href=""
            >view more</a
          >
          <svg
            width="18"
            height="16"
            viewBox="0 0 18 16"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M10 15L17 8L10 0.999999M17 8L1 8"
              stroke="#0F1A43"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>
        </div>
      </div>

      <div class=" col-span-2  ">
          <div
            class=""
          >
            <swiper
              class=" absolute inset-0 right-0"
              :modules="modules"
              :slides-per-view="3.5"
              :space-between="20"
              :loop="loop"
              navigation
              :pagination="{ clickable: true }"
              :autoplay="autoplay"
              :breakpoints="{
                300: { slidesPerView: 1 },
                740: { slidesPerView: 2 },
                1024: { slidesPerView: 3.5 },
              }"
              @swiper="onSwiper"
              @slideChange="onSlideChange"
            >
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">15</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">20+</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">1.5m</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">40%</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">15</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">15</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">15</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
              <swiper-slide>
               <article>
                <div class="border border-[#6D6E70]/40 rounded-lg p-5">
                    <h4 class="text-[72px] leading-[40px] text-[#001844]">15</h4>
                    <p class="text-[#001844] mt-8">vaccines manufacturing sites - enabling a supply capability to produce and deliver 500 million vaccine doses in 2022</p>

                </div>

               </article>
              </swiper-slide>
            </swiper>
          </div>
     
      </div>
    </div>
  </div>
  </div>
</template>
<script setup>
import { Navigation,Pagination, Scrollbar, A11y, Autoplay } from "swiper";

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";
import "swiper/css/scrollbar";

// Import Swiper styles

const onSwiper = (swiper) => {
  console.log(swiper);
};
const onSlideChange = () => {
  console.log("slide change");
};

const modules = [Navigation,Pagination, Scrollbar, A11y, Autoplay];

</script>
