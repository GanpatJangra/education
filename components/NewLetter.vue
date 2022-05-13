<template>
  <div>
    <div class="flex flex-col sm:flex-row sm:items-center my-10 bg-[#331B00] w-full pt-5 sm:pt-0">
      <div class="sm:w-[45%] text-white ml-5">
        <h1 class="lg:text-[4rem] text-4xl leading-tight font-semibold">Share with us What you know</h1>
        <p class="my-4 text-sm">On Coursew it’s about mastering a timeless skill cultivating new perspectives, and connecting with fascinating people from around the world</p>
        <button class="flex items-center justify-center w-56 h-14 text-lg uppercase bg-yellow-500 shadow-sm shadow-second/50">
          <h1>BOOK FREE LESSON</h1>
          <svg class="w-8 h-8 ml-4 text-third" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
          </svg>
        </button>
      </div>
      <div class="sm:w-[55%] mt-8 sm:mt-0 bg-[url('~/assets/images/webcom/Vector.png')] bg-cover">
        <img class="h-52 sm:h-1/3 mx-auto" src="../assets/images/webcom/image4.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewLetter",
};
</script>
