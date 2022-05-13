<template>
  <div class="my-10">
    <h1 class="font-semibold text-8xl">Testimonials</h1>
    <ssr-carousel :show-arrows="true" show-dots loop class="relative">
      <div class="slide">
        <div>
          <div class="flex justify-center flex-col sm:flex-row items-center">
            <img class="w-40 sm:w-[25%] mx-auto" src="../assets/images/webcom/image3.svg" alt="" />

            <p class="sm:w-[60%] font-semibold text-xl sm:pr-24 xl:pr-32">
              I took online programming course of coursew, and here I’m to say it was really cool. I spent only few dollars but get lifelong skills and knowledge here. Highly recommended.
            </p>
          </div>
        </div>
      </div>
      <div class="slide">
        <div>
          <div class="flex justify-center flex-col sm:flex-row items-center">
            <img class="w-40 sm:w-[25%] mx-auto" src="../assets/images/webcom/image3.svg" alt="" />

            <p class="sm:w-[60%] font-semibold text-xl sm:pr-24 xl:pr-32">
              I took online programming course of coursew, and here I’m to say it was really cool. I spent only few dollars but get lifelong skills and knowledge here. Highly recommended.
            </p>
          </div>
        </div>
      </div>
      <div class="slide">
        <div>
          <div class="flex justify-center flex-col sm:flex-row items-center">
            <img class="w-40 sm:w-[25%] mx-auto" src="../assets/images/webcom/image3.svg" alt="" />

            <p class="sm:w-[60%] font-semibold text-xl sm:pr-24 xl:pr-32">
              I took online programming course of coursew, and here I’m to say it was really cool. I spent only few dollars but get lifelong skills and knowledge here. Highly recommended.
            </p>
          </div>
        </div>
      </div>
      <div class="slide">
        <div>
          <div class="flex justify-center flex-col sm:flex-row items-center">
            <img class="w-40 sm:w-[25%] mx-auto" src="../assets/images/webcom/image3.svg" alt="" />

            <p class="sm:w-[60%] font-semibold text-xl sm:pr-24 xl:pr-32">
              I took online programming course of coursew, and here I’m to say it was really cool. I spent only few dollars but get lifelong skills and knowledge here. Highly recommended.
            </p>
          </div>
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
</template>

<script>
export default {
  name:'Testimonial',
  data() {
    return {
      helllo: "true",
    };
  },
  methods: {},
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
