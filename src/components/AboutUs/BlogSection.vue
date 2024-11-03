<template>
  <section class="mt-32 w-full max-w-[1207px] mx-auto max-md:mt-10 max-md:max-w-full">
    <article class="flex gap-5 max-md:flex-col">
      <figure class="flex flex-col w-[55%] max-md:ml-0 max-md:w-full">
        <img 
          loading="lazy" 
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/da6cba920407dd7f10ad9f12e05252b59b895adba0200a2508c75fa5c5f38f6c?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c" 
          alt="Blog introduction visual"
          class="object-contain grow w-full aspect-[1.21] max-md:mt-10 max-md:max-w-full" 
        />
      </figure>
      <article class="flex flex-col ml-5 w-[45%] max-md:ml-0 max-md:w-full">
        <div class="flex flex-col self-stretch my-auto font-bold text-gray-800 max-md:mt-10 max-md:max-w-full">
          <h1 class="self-start text-4xl tracking-tighter leading-none text-gray-800">
            Why we started this Blog
          </h1>
          <h2 class="mt-4 text-2xl leading-8 max-md:mr-2 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.
          </h2>
          <p class="mt-4 text-base leading-7 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat.
          </p>
        </div>
      </article>
    </article>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'BlogIntro'
})
</script>