<template>
  <section class="flex justify-center items-center gap-10 mt-24 w-full max-w-[1237px] mx-auto text-zinc-500 max-md:mt-10 max-md:max-w-full">
    <!-- Header and Image in one row -->
    <div class="flex items-center gap-6">
      <!-- Header -->
      <header class="text-left">
        <h2>
          <span class="block text-sm leading-none opacity-60">We are</span>
          <span class="block text-2xl font-bold leading-none">Featured in</span>
        </h2>
      </header>

      <!-- Image -->
      <img
        loading="lazy"
        src="@/assets/images/home/Logo1.png"
        alt="Featured publications and media outlets"
        class="object-contain w-auto h-10 max-md:h-8"
      />
      <img
        loading="lazy"
        src="@/assets/images/home/Logo2.png"
        alt="Featured publications and media outlets"
        class="object-contain w-auto h-10 max-md:h-8"
      />
      <img
        loading="lazy"
        src="@/assets/images/home/Logo3.png"
        alt="Featured publications and media outlets"
        class="object-contain w-auto h-10 max-md:h-8"
      />
      <img
        loading="lazy"
        src="@/assets/images/home/Logo4.png"
        alt="Featured publications and media outlets"
        class="object-contain w-auto h-10 max-md:h-8"
      />
    </div>
  </section>
</template>

<script lang="ts">
export default {
  name: 'FeaturedSection'
}
</script>
