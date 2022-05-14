<template>
  <div class="font-Epilogue">
    <div class="flex flex-col-reverse py-5 lg:flex-row lg:justify-between lg:py-24 lg:items-center">
      <div class="lg:w-[40%]">
        <div class="bg-[url('~/assets/images/webcom/graphic1.png')] bg-cover bg-no-repeat h-52 w-52 sm:h-80 sm:w-[21rem] lg:w-[28rem] lg:h-[34rem] flex items-end justify-center mx-auto lg:mx-0">
          <div class="bg-first lg:w-[25rem] lg:h-[28rem] flex items-center justify-center h-48 w-44 sm:h-72 sm:w-[18rem]">
            <!-- The button to open modal -->
            <label for="my-modal-6" class="p-5 rounded-full bg-gray-50 animate-pulse modal-button cursor-pointer">
              <svg class="w-10 h-10 text-gray-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <polygon points="23 7 16 12 23 17 23 7" />
                <rect x="1" y="5" width="15" height="14" rx="2" ry="2" /></svg
            ></label>

            <!-- Put this part before </body> tag -->
            <input type="checkbox" id="my-modal-6" class="modal-toggle" />
            <div class="modal modal-bottom sm:modal-middle">
              <div class="w-full md:w-1/3 xl:w-1/2 border-2 border-second bg-first py-2 px-2 rounded-xl ">
                <div class="codegena"><iframe width="500" height="294" src="https://www.youtube.com/embed/ow1QqW0jzTo?&theme=dark&autohide=1" frameborder="0"></iframe></div>
                <div style="font-size: 0.8em"></div>
                <div class="modal-action">
                  <label for="my-modal-6" class="bg-yellow-500 py-1 px-2 rounded-xl font-semibold cursor-pointer">close</label>
                </div>
              </div>
            </div>
          </div>
        </div>
        <h1 class="my-3 text-lg font-semibold">Oliver Charlotte</h1>
        <p class="text-sm">Unlocking Your Potential: 5 Exercises to Build Creative Confidence</p>
      </div>
      <div class="lg:w-[60%] lg:text-left sm:text-center">
        <h1 class="sm:text-[4rem] text-8xl leading-tight">
          Never stop
          <!-- <span class="relative">
            <img class="absolute top-0 left-0 w-full h-full" src="~/assets/images/webcom/graphic.png" alt="" /> -->
            <span class="bg-[url('~/assets/images/webcom/graphic.png')] font-semibold bg-no-repeat bg-cover  bg-graphic lg:bg-none"> learning. </span>
            <br />
          <!-- </span> -->
          Life never stops teaching!
        </h1>
        <div class="flex flex-col pt-10 sm:items-center lg:flex-row">
          <input class="font-semibold  pl-1 h-14 w-72 lg:w-[25rem] bg-white shadow-sm shadow-second/50 placeholder:text-black placeholder:pl-10 placeholder:font-semibold focus:outline-none block" type="text" placeholder="What do you want to learn ?" />
          <button class="flex items-center justify-center w-56 text-lg font-semibold uppercase bg-yellow-500 shadow-sm h-14 shadow-second/50">
            <h1>find tutor</h1>
            <svg class="w-8 h-8 ml-4 text-third" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
            </svg>
          </button>
        </div>
        <h1 class="py-4 text-gray-400">Ex - BCA, MBA</h1>
      </div>
    </div>

    <discover-tutor></discover-tutor>
    <e-course></e-course>
    <discover></discover>
    <testimonial></testimonial>
    <new-letter></new-letter>
  </div>
</template>

<script>
export default {
  name:'index',
}
</script>

<style>
.codegena {
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 56.27198%;
}
.codegena iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
} /*Youtube Embed Code : Created with Codegena.com */
</style>
