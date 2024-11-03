<template>
  <main class="flex overflow-hidden flex-col items-center bg-white">

    <section class="flex flex-col items-center mt-32 max-md:mt-10">
      <h1 class="text-base font-black leading-none text-center text-gray-800 uppercase tracking-[3px]">Contact us</h1>
      <h2
        class="mt-3 text-5xl font-bold tracking-tighter leading-none text-center text-gray-800 max-md:max-w-full max-md:text-4xl">
        Let's Start a Conversation</h2>
      <p class="mt-6 text-base leading-7 text-center text-zinc-500 w-[768px] max-md:max-w-full">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim.
      </p>
    </section>

    <section class="px-16 py-12 mt-16 max-w-full bg-amber-300 w-[768px] max-md:px-5 max-md:mt-10">
      <div class="flex gap-5 max-md:flex-col">
        <article class="flex flex-col w-6/12 max-md:ml-0 max-md:w-full">
          <div class="flex flex-col grow items-start text-xl leading-relaxed text-neutral-600 max-md:mt-10">
            <h3 class="text-sm leading-none opacity-60">Working hours</h3>
            <hr
              class="shrink-0 self-stretch mt-4 h-px border border-solid opacity-10 bg-neutral-600 border-neutral-600" />
            <p class="mt-4 font-bold">Monday To Friday</p>
            <p class="font-bold">9:00 AM to 8:00 PM</p>
            <p class="text-base leading-7 opacity-60">Our Support Team is available 24/7</p>
          </div>
        </article>
        <article class="flex flex-col ml-5 w-6/12 max-md:ml-0 max-md:w-full">
          <div class="flex flex-col items-start text-neutral-600 max-md:mt-10">
            <h3 class="text-sm leading-none opacity-60">Contact Us</h3>
            <hr
              class="shrink-0 self-stretch mt-4 h-px border border-solid opacity-10 bg-neutral-600 border-neutral-600" />
            <p class="mt-4 text-xl font-bold leading-relaxed">020 7993 2905</p>
            <p class="text-base leading-7 opacity-60">hello@finsweet.com</p>
          </div>
        </article>
      </div>
    </section>

    <form class="w-[768px] max-w-full mt-8" @submit.prevent="handleSubmit">
      <label for="fullName" class="sr-only">Full Name</label>
      <input type="text" id="fullName" name="fullName" placeholder="Full Name" required
        class="gap-2.5 self-stretch p-6 w-full text-base leading-7 text-gray-800 rounded-sm border border-solid border-zinc-500 border-opacity-50 max-md:px-5" />

      <label for="email" class="sr-only">Your Email</label>
      <input type="email" id="email" name="email" placeholder="Your Email" required
        class="gap-2.5 self-stretch p-6 mt-4 w-full text-base leading-7 text-gray-800 rounded-sm border border-solid border-zinc-500 border-opacity-50 max-md:px-5" />

      <div class="flex flex-wrap gap-4 items-center mt-3.5 w-full">
        <div class="flex-1">
          <label for="province" class="sr-only">Province</label>
          <select id="province" name="province" required
            class="w-full p-6 border border-solid border-zinc-500 border-opacity-50 text-gray-800">
            <option value="">Province</option>
          </select>
        </div>
        <div class="flex-1">
          <label for="city" class="sr-only">City</label>
          <select id="city" name="city" required
            class="w-full p-6 border border-solid border-zinc-500 border-opacity-50 text-gray-800">
            <option value="">City</option>
          </select>
        </div>
      </div>

      <label for="message" class="sr-only">Message</label>
      <textarea id="message" name="message" placeholder="Message" required
        class="gap-2.5 px-6 pt-6 pb-24 mt-5 w-full text-base leading-7 text-gray-800 rounded-sm border border-solid border-zinc-500 border-opacity-50 min-h-[144px] max-md:px-5"></textarea>

      <button type="submit"
        class="w-full px-16 py-4 mt-4 text-2xl font-bold leading-none text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 max-md:px-5">
        Send Message
      </button>
    </form>
  </main>
</template>

<script lang="ts">
  import {
    defineComponent
  } from 'vue'

  export default defineComponent({
    name: 'ContactPage',
    methods: {
      handleSubmit() {
        // Handle form submission
      },
    }
  })

</script>

<style scoped>
  .sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
  }

</style>
