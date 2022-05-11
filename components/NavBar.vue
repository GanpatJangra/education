<template>
  <div class="flex items-center justify-between py-5">
    <div>
      <img src="../assets/images/webcom/logo.svg" alt="" />
    </div>
    <div class="flex uppercase list-none lg:space-x-8 lg:text-lg">
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><nuxt-link to="/findtutor">Find tutor</nuxt-link></li>
      <li><nuxt-link to="/howitwork">how it work</nuxt-link></li>
      <li><nuxt-link to="/aboutus">about us</nuxt-link></li>
      <li><nuxt-link to="/blog">blog</nuxt-link></li>
      <div class="flex pl-10 space-x-4">
        <li><nuxt-link to="/login">login</nuxt-link></li>
        <li><nuxt-link class="px-4 py-1 border-2 border-black" to="/blog">sign up</nuxt-link></li>
      </div>
    </div>
  </div>
</template>
