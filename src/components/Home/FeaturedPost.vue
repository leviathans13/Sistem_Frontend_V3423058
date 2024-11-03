<!-- src/components/Blog/FeaturedPosts.vue -->
<template>
  <section class="featured-posts px-20 mt-32 max-md:px-5 max-md:mt-10">
    <div class="flex justify-between items-center mb-8">
      <h2 class="text-4xl font-bold tracking-tighter text-gray-800">Featured Post</h2>
      <div class="flex items-center gap-4">
        <h3 class="text-4xl font-bold tracking-tighter text-gray-800">All Posts</h3>
        <a href="#" class="text-base leading-7 text-amber-300 hover:underline">View All</a>
      </div>
    </div>

    <!-- Featured Posts Grid -->
    <div class="grid grid-cols-5 gap-5 max-md:grid-cols-1">
      <!-- Main Featured Post -->
      <article class="col-span-3 border border-zinc-500 p-8">
        <img loading="lazy"
          src="@/assets/images/home/white-concrete-building-1838640.png"
          alt="Featured post image" class="w-full aspect-[1.9] object-cover" />
        <div class="mt-8 text-sm text-amber-300">
          By <a href="#" class="hover:underline">John Doe</a> | May 23, 2022
        </div>
        <h3 class="mt-4 text-3xl font-bold tracking-tighter text-gray-800">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </h3>
        <p class="mt-4 text-zinc-500">
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        </p>
        <button
          class="mt-8 px-12 py-4 bg-blue-600 text-white text-lg hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500"
          tabindex="0">
          Read More >
        </button>
      </article>

      <!-- Side Posts -->
      <div class="col-span-2 flex flex-col gap-4">
        <article class="bg-white p-7">
          <time class="text-sm text-amber-300">Aug 23, 2021</time>
          <h3 class="mt-2 text-2xl font-bold text-gray-800">
            8 Figma design systems that you can download for free today
          </h3>
        </article>
        <article class="bg-yellow p-7">
          <time class="text-sm text-amber-300">Aug 23, 2021</time>
          <h3 class="mt-2 text-2xl font-bold text-gray-800">
            8 Figma design systems that you can download for free today
          </h3>
        </article>
        <article class="bg-white p-7">
          <time class="text-sm text-amber-300">Aug 23, 2021</time>
          <h3 class="mt-2 text-2xl font-bold text-gray-800">
            8 Figma design systems that you can download for free today
          </h3>
        </article>
        <article class="bg-white p-7">
          <time class="text-sm text-amber-300">Aug 23, 2021</time>
          <h3 class="mt-2 text-2xl font-bold text-gray-800">
            8 Figma design systems that you can download for free today
          </h3>
        </article>
        <!-- Repeat similar article structure for other posts -->
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
</script>

<style scoped>
</style>
