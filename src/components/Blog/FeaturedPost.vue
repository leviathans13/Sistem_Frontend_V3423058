<template>
  <article class="p-20 w-full bg-gray-100 max-md:px-5 max-md:max-w-full">
    <div class="flex gap-5 max-md:flex-col">
      <section class="flex flex-col w-[55%] max-md:ml-0 max-md:w-full">
        <div class="flex flex-col items-start self-stretch my-auto w-full font-medium max-md:mt-10 max-md:max-w-full">
          <span class="text-base leading-none text-gray-800 uppercase tracking-[3px]">Featured Post</span>
          <h1 class="self-stretch mt-5 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:max-w-full">
            Step-by-step guide to choosing great font pairs
          </h1>
          <time datetime="2022-05-23" class="mt-4 text-sm leading-none text-amber-300">
            By <span class="text-amber-300">John Doe</span> l May 23, 2022
          </time>
          <p class="self-stretch mt-4 text-base leading-7 text-zinc-500 max-md:max-w-full">
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            Excepteur sint occaecat cupidatat non proident.
          </p>
          <button class="gap-3 px-12 py-4 mt-8 text-lg font-bold leading-none text-white bg-blue-600 max-md:px-5"
            @click="handleReadMore" aria-label="Read more about choosing great font pairs">
            Read More &gt;
          </button>
        </div>
      </section>
      <section class="flex flex-col ml-5 w-[45%] max-md:ml-0 max-md:w-full">
        <img loading="lazy"
          src="@/assets/images/blog/man-in-white-dress-shirt-sitting-on-black-rolling-chair-while-facing-black-computer-set-and-smiling-840996.png"
          alt="Featured post illustration about font pairs"
          class="object-contain grow w-full aspect-[1.43] max-md:mt-10 max-md:max-w-full" />
      </section>
    </div>
  </article>
</template>

<script lang="ts">
import {
  defineComponent
} from 'vue'

export default defineComponent({
  name: 'FeaturedPost',
  methods: {
    handleReadMore(): void {
      // Handle read more click event
    }
  }
})

</script>
