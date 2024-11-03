<template>
  <section class="relative flex items-center justify-center mt-20 px-20 py-32 bg-white-100 max-w-full min-h-[600px] max-md:px-5 max-md:py-20">
    <!-- Gambar di sebelah kiri -->
    <div class="absolute inset-0 w-1/2 h-full ml-20 overflow-hidden max-md:relative max-md:w-full">
      <img
        loading="lazy"
        src="@/assets/images/home/home3.png"
        alt="Team photo"
        class="object-cover w-full h-full"
      />
    </div>

    <!-- Konten teks di sebelah kanan -->
    <article class="relative z-10 flex flex-col items-start ml-60 mt-20 mb-0 p-10 bg-white shadow-lg w-1/2 max-md:w-full max-md:p-8">
      <h2 class="text-sm font-semibold uppercase tracking-widest text-gray-500">
        Why we started
      </h2>
      <h3 class="mt-4 text-4xl font-bold leading-snug text-gray-900 max-md:text-3xl">
        It started out as a simple idea and evolved into our passion
      </h3>
      <p class="mt-4 text-lg leading-relaxed text-gray-600">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
      </p>
      <button
        class="px-6 py-3 mt-6 text-lg font-semibold text-white bg-blue-600 rounded hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2"
      >
        Discover our story &gt;
      </button>
    </article>
  </section>
</template>

<script lang="ts">
export default {
  name: 'WhyWeStarted'
}
</script>

<style scoped>
/* Custom CSS to adjust layout */
@media (min-width: 768px) {
  .relative > div:first-of-type {
    border-radius: 8px 0 0 8px;
  }
  .relative > article {
    border-radius: 0 8px 8px 0;
  }
}
</style>
