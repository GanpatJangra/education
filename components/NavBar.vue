<template>
  <div class="flex items-center justify-between py-5 relative">
    <div>
      <img src="../assets/images/webcom/logo.svg" alt="" />
    </div>

    <div :class="{ hidden }" class="xl:flex absolute justify-end uppercase absolute top-[5rem] xl:top-2 list-none space-y-5 lg:space-y-0 xl:bg-transparent bg-yellow-500 w-full p-5 rounded-xl lg:space-x-10 lg:text-lg">
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><a href="/#DiscoverTutor">Find tutor</a></li>
      <li><nuxt-link to="/howitwork">how it work</nuxt-link></li>
      <li><nuxt-link to="/aboutus">about us</nuxt-link></li>
      <li><nuxt-link to="/blog">blog</nuxt-link></li>
      <div class="flex pl-10 space-x-4">
        <li><nuxt-link to="/login">login</nuxt-link></li>
        <li><nuxt-link class="px-8 py-3 border-2 border-black" to="/signup">sign up</nuxt-link></li>
      </div>
    </div>

    <div class="xl:hidden">
      <button @click="hammanu()">
        <svg class="h-8 w-8 text-black" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
        </svg>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "navbar",
  data() {
    return {
      hidden: true,
    };
  },
  methods: {
    hammanu() {
      this.hidden = !this.hidden;
      console.log(this.hidden);
    },
  },
};
</script>

<style></style>
