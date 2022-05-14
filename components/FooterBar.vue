<template>
  <div class="pb-10">
    <img class="mb-5 " src="~/assets/images/webcom/logo.svg" alt="" />
    <div class="list-none lg:flex lg:justify-between">
      <div class="sm:w-1/3">
        <p>Join the more than 1000+ tutors who use Coursew to share their knowledge. Easily create an online course or coaching business with our powerful yet simple all-in-one platform.</p>
      </div>

      <div class="flex w-1/3 leading-loose lg:my-0 my-10 font-semibold lg:justify-center lg:space-x-10">
        <div class="whitespace-nowrap lg:pl-24">
          <li><nuxt-link to="/">Home</nuxt-link></li>
          <li><a href="/#DiscoverTutor">Find tutor</a></li>
          <li><nuxt-link to="/howitwork">How it work</nuxt-link></li>
        </div>
        <div class="ml-20 lg:pl-10 whitespace-nowrap">
          <li><nuxt-link to="/blog">Blog</nuxt-link></li>

          <li><nuxt-link to="/aboutus">About us</nuxt-link></li>
        </div>
      </div>

      <div class="sm:w-1/3 lg:pl-24">
        <h1 class="text-xl">Subscribe to our newsletter</h1>
        <div class="flex items-center mt-5 mb-16 ">
          <input class="border-b-2 lg:w-72 w-56  border-black bg-[#FEFCEC] focus:outline-none" type="text" placeholder="Enter your email" />
          <span class="-ml-[55px]"><button>Submit</button></span>
        </div>
        <div class="flex space-x-3">
          <li><img class="bg-yellow-500 w-12" src="~/assets/images/webcom/icon/social/Group 71.svg" alt="" /></li>
          <li><img class="bg-yellow-500 w-12" src="~/assets/images/webcom/icon/social/Group 68.svg" alt="" /></li>
          <li><img class="bg-yellow-500 w-12" src="~/assets/images/webcom/icon/social/Group 70.svg" alt="" /></li>
          <li><img class="bg-yellow-500 w-12" src="~/assets/images/webcom/icon/social/Group 77.svg" alt="" /></li>
          <li><img class="bg-yellow-500 w-12" src="~/assets/images/webcom/icon/social/Group 72.svg" alt="" /></li>
        </div>
      </div>
    </div>
    <h1 class="text-sm lowercase">© COPYRIGHT 2022 Ganpat Jangra</h1>
  </div>
</template>
<script>
export default {
  name: "footer",
};
</script>
