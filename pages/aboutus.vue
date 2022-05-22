<template>
  <div>
    <section >
      <div class="container px-4 mx-auto">
        <div class="flex flex-wrap -mx-4">
          <div class="w-full px-4 lg:w-1/2">
            <div class="max-w-md py-24 mx-auto">
              <h2 class="mb-12 text-5xl md:text-6xl lg:text-7xl font-heading">Form</h2>
              <form action="">
                <input class="block w-full px-4 py-2 mb-6 text-lg border-b border-gray-400 outline-none rounded-4xl" type="text" placeholder="Name" />
                <input class="block w-full px-4 py-2 mb-6 text-lg border-b border-gray-400 outline-none rounded-4xl" type="text" placeholder="Surname" />
                <input class="block w-full px-4 py-2 mb-6 text-lg border-b border-gray-400 outline-none rounded-4xl" type="text" placeholder="Mail address" />
                <textarea class="block w-full px-4 py-2 mb-6 text-lg border-b border-gray-400 outline-none resize-none rounded-4xl" name="" id="" cols="30" rows="10" placeholder="Form message"></textarea>

                <button class="block w-full px-8 py-3 font-bold text-black transition duration-200 bg-yellow-500 rounded-4xl text-third hover:bg-yellow-400">Send Now</button>
              </form>
            </div>
          </div>
          <div class=" w-full px-4 lg:w-1/2 lg:pl-24">
            <div class=" max-w-md py-24 mx-auto xl:max-w-lg">
              <h2 class="mb-12 text-5xl md:text-6xl lg:text-7xl font-heading">Contact</h2>
              <p class="text-third">Is the answer to your question missing?</p>
              <p class="mb-20">Get in touch with us.</p>
              <div class="flex flex-wrap -mx-4">
                <div class="w-full px-4 mb-10 lg:w-1/2">
                  <p class="text-gray-500">E-mail</p>
                  <a class="inline-block text-black hover:underline" href="mailto:contact@pstls.com">contact@pstls.com</a>
                </div>
                <div class="w-full px-4 mb-10 lg:w-1/2">
                  <p class="text-gray-500">Phone</p>
                  <p>+1-2020-555-109</p>
                </div>
              </div>
              <div class="flex flex-wrap -mx-4">
                <div class="w-full px-4 mb-10 lg:w-1/2">
                  <p class="mb-2 text-gray-500">Socials</p>
                  <a class="inline-block" href="#">
                    <img src="~/assets/images/webcom/icon/social/Group 70.svg" alt="" />
                  </a>
                  <a class="inline-block" href="#">
                    <img src="~/assets/images/webcom/icon/social/Group 71.svg" alt="" />
                  </a>
                  <a class="inline-block" href="#">
                    <img src="~/assets/images/webcom/icon/social/Group 72.svg" alt="" />
                  </a>
                </div>
                <div class="w-full px-4 lg:w-1/2">
                  <p class="text-gray-500">Office</p>
                  <p>3177 Tecumsah LaneKeithville, Louisiana</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name:'about',
}
</script>