<template>
  <section class="mt-16 w-full max-w-screen-xl mx-auto max-md:mt-10 max-md:max-w-full">
    <div class="flex gap-5 max-md:flex-col">
      <article class="flex flex-col w-[43%] max-md:ml-0 max-md:w-full">
        <div class="flex flex-col self-stretch my-auto font-bold text-gray-800 max-md:mt-10 max-md:max-w-full">
          <h1 class="self-start text-4xl tracking-tighter leading-none text-gray-800">
            Our team of creatives
          </h1>
          <h2 class="mt-4 text-2xl leading-8 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.
          </h2>
          <p class="mt-4 text-base leading-7 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
            fugiat.
          </p>
        </div>
      </article>
      <figure class="flex flex-col ml-5 w-[57%] max-md:ml-0 max-md:w-full">
        <img loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/209cea4fe3d9e717472696012448afc1588578827fcd02ffb1ba99d8437fa9bd?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c"
          alt="Our creative team at work"
          class="object-contain grow w-full rounded-none aspect-[1.42] max-md:mt-10 max-md:max-w-full" />
      </figure>
    </div>
  </section>
</template>

<script lang="ts">
  import {
    defineComponent
  } from 'vue'

  export default defineComponent({
    name: 'CreativeTeam'
  })

</script>
