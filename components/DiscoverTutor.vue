<template>
  <div>
    <div class="mb-10">
      <h1 id="DiscoverTutor" class="font-semibold text-8xl">Discover tutor</h1>
      <ssr-carousel :show-arrows="true" show-dots loop="true" class="relative">
        <div class="slide flex flex-col sm:flex-row items-center justify-between text-center font-semibold text-xl">
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
        </div>

        <div class="slide flex flex-col sm:flex-row items-center justify-between text-center font-semibold text-xl">
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
        </div>

        <div class="slide flex flex-col sm:flex-row items-center justify-between text-center font-semibold text-xl">
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
          <div>
            <img src="../assets/images/webcom/image.svg" alt="" />
            <h1>Pixy OS</h1>
          </div>
        </div>

        <template #back-arrow="{}">
          <svg class="h-8 w-8 text-third bg-yellow-500" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" />
            <line x1="5" y1="12" x2="19" y2="12" />
            <line x1="5" y1="12" x2="9" y2="16" />
            <line x1="5" y1="12" x2="9" y2="8" />
          </svg>
        </template>

        <template #next-arrow="{}">
          <svg class="h-8 w-8 m-3 text-third bg-yellow-500" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" />
            <line x1="5" y1="12" x2="19" y2="12" />
            <line x1="15" y1="16" x2="19" y2="12" />
            <line x1="15" y1="8" x2="19" y2="12" />
          </svg>
        </template>
      </ssr-carousel>
    </div>

    <div class="flex flex-col sm:flex-row sm:items-center py-10">
      <div class="sm:w-[40%]">
        <h1 class="lg:text-[4rem] text-4xl leading-tight font-semibold">What will you discover on Coursew?</h1>
        <p class="my-8">Explore new skills, deepen existing passions, and get lost in creativity. What you find just might surprise and inspire you.</p>
        <button class="flex items-center justify-center w-48 h-12 text-lg uppercase bg-yellow-500 shadow-sm shadow-second/50">
          <h1>check it more</h1>
          <svg class="w-8 h-8 ml-4 text-third" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
          </svg>
        </button>
      </div>
      <div class="sm:w-[60%] mt-8 sm:mt-0">
        <img class="h-52 sm:h-1/3 mx-auto" src="../assets/images/webcom/image1.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DiscoverTutor",
};
</script>

<style>
.ssr-carousel-back-button,
.ssr-carousel-next-button {
  position: absolute;
  top: 100%;
  transform: translateY(-50%);
  display: inline-block;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  background: none;
  color: inherit;
  border: none;
  align-items: center;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

.ssr-carousel-back-button {
  left: 40%;
  padding-top: 40px;
}
.ssr-carousel-next-button {
  padding-top: 40px;
  right: 38%;
}
@media only screen and (max-width: 600px) {
  .ssr-carousel-next-button {
    padding-top: 40px;
    right: 25%;
  }
}
@media only screen and (max-width: 600px) {
  .ssr-carousel-back-button {
    left: 28%;
    padding-top: 40px;
  }
}

.ssr-carousel-dot-icon {
  display: inline-block;
  width: 12px;
  height: 12px;
  border-radius: 6px;

  border: 2px solid;
  margin-left: 4px;
  margin-right: 4px;
  transition: opacity 0.2s;
}

[disabled] > .ssr-carousel-dot-icon {
  opacity: 1;
  background: rgb(255 211 53);
  border: none;
  cursor: default;
}
</style>
