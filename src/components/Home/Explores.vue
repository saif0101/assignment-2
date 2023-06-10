<template>
  <div class="custome-container py-20">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-x-20 gap-y-8">
      <div>
        <div class="relative">
          <div
            id="customVideo"
            class="w-auto h-auto lg:w-[560px] lg:h-[534px] overflow-hidden flex items-center justify-center"
          >
            <button
              @click="customVideo()"
              class="absolute inset-0 m-auto left-1/3"
            >
              <img
                src="../../assets/home/Group 53 Copy@1x.png"
                alt="play-button"
              />
            </button>
            <figure>
              <img src="../../assets/home/video-thum.jpg" alt="thumbnail" />
            </figure>
          </div>
        </div>
      </div>

      <div class="flex items-center">
        <div>
          <p class="text-[20px] leading-[30px] font-bold text-[#0F1A43]">
            Explore our innovation stories
          </p>
          <h3 class="text-[20px] leading-[30px] lg:text-[32px] lg:leading-[40px] font-light mt-4">Were not a world of men “ it's as simple as that™: how gender diversity in clinical trials improves health outcomes for women</h3>
          <button class="bg-[#0F1A43] py-3 px-14 rounded-full  text-white font-bold mt-5"> Learn more</button>
        </div>
      </div>



    </div>
  </div>
</template>

<script setup>
function customVideo() {
  document.getElementById("customVideo").innerHTML =
    '<iframe width="100%" height="100%" src="https://www.youtube.com/embed/sZmtypVN0uc?autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; allow="autoplay; &muted=1 ; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>';
}
</script>
