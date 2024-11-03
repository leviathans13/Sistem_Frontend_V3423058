<!-- src/components/Home/HeroSection.vue -->
<script lang="ts">
export default {
  name: 'HeroSection'
}
</script>

<template>
  <section class="flex justify-center items-center px-8 py-10">
    <div class="w-full max-w-[1400px] text-center">
      <div class="flex gap-12 max-md:flex-col">
        <!-- Left section with heading and subheading -->
        <article class="flex flex-col w-[60%] max-md:ml-0 max-md:w-full">
          <header class="flex flex-col grow items-start p-20 w-full text-gray-800 bg-white shadow-lg max-md:px-5 max-md:mt-8 max-md:max-w-full">
            <h2 class="text-lg font-semibold leading-none uppercase tracking-wider text-gray-600">ABOUT US</h2>
            <h1 class="mt-6 text-6xl font-extrabold tracking-tight leading-[80px] max-md:max-w-full max-md:text-5xl max-md:leading-[60px]">
              We are a team of content writers who share their learnings
            </h1>
          </header>
        </article>
        <!-- Right section with description -->
        <aside class="flex flex-col ml-8 w-[40%] max-md:ml-0 max-md:w-full">
          <p class="text-lg leading-8 text-gray-600 my-auto max-md:mt-10 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </aside>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Optional additional styling to adjust the font size or spacing */
</style>


<style scoped>
/* Tidak perlu styling tambahan */
</style>
