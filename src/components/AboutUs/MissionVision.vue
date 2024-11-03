<!-- src/components/About/MissionVision.vue -->
<script lang="ts">
export default {
  name: 'MissionVision'
}
</script>

<template>
  <section class="flex relative flex-col items-start px-20 pt-12 mx-auto max-w-full min-h-[444px] w-[1280px] max-md:px-5 max-md:pt-24 bg-gray-100">
    <div class="w-full max-w-[1400px] text-left">
      <div class="flex gap-12 max-md:flex-col">
        <!-- Our Mission Section -->
        <article class="flex flex-col w-[50%] max-md:w-full">
          <div class="flex flex-col grow text-gray-800">
            <h2 class="text-lg font-semibold uppercase tracking-wider text-gray-600">Our Mission</h2>
            <h3 class="mt-6 text-4xl font-bold tracking-tight text-gray-900">
              Creating valuable content for creatives all around the world
            </h3>
            <p class="mt-6 text-lg leading-8 text-gray-600">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.
            </p>
          </div>
        </article>

        <!-- Our Vision Section -->
        <article class="flex flex-col w-[50%] max-md:w-full">
          <div class="flex flex-col grow text-gray-800">
            <h2 class="text-lg font-semibold uppercase tracking-wider text-gray-600">Our Vision</h2>
            <h3 class="mt-6 text-4xl font-bold tracking-tight text-gray-900">
              A platform that empowers individuals to improve
            </h3>
            <p class="mt-6 text-lg leading-8 text-gray-600">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Scelerisque viverra mauris in aliquam sem.
            </p>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Optional additional styling */
</style>
