<template>
  <section class="px-20 py-12 max-md:px-5">
    <h2 class="text-4xl font-bold tracking-tighter text-left text-gray-800 mb-12">
      All Categories
    </h2>
    <div class="grid grid-cols-4 gap-5 max-md:grid-cols-1">
      <!-- Category Cards -->
      <router-link to="/category">
        <article class="category-card border border-zinc-500 p-8 transition-transform duration-300 hover:scale-105 hover:shadow-lg hover:bg-blue-500 hover:text-white">
          <img loading="lazy"
            src="@/assets/images/home/Icon1.png"
            alt="Business category icon" class="w-12 aspect-square" />
          <h3 class="mt-4 text-3xl font-bold text-gray-800 hover:text-white">Business</h3>
          <p class="mt-1 text-zinc-500 hover:text-white">
            Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
          </p>
        </article>
      </router-link>
      <article class="category-card border border-zinc-500 p-8 transition-transform duration-300 hover:scale-105 hover:shadow-lg hover:bg-blue-500 hover:text-white">
        <img loading="lazy"
          src="@/assets/images/home/Icon2.png"
          alt="Startup category icon" class="w-12 aspect-square" />
        <h3 class="mt-4 text-3xl font-bold text-gray-800 hover:text-white">Startup</h3>
        <p class="mt-1 text-zinc-500 hover:text-white">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        </p>
      </article>
      <article class="category-card border border-zinc-500 p-8 transition-transform duration-300 hover:scale-105 hover:shadow-lg hover:bg-blue-500 hover:text-white">
        <img loading="lazy"
          src="@/assets/images/home/Icon3.png"
          alt="Economy category icon" class="w-12 aspect-square" />
        <h3 class="mt-4 text-3xl font-bold text-gray-800 hover:text-white">Economy</h3>
        <p class="mt-1 text-zinc-500 hover:text-white">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        </p>
      </article>
      <article class="category-card border border-zinc-500 p-8 transition-transform duration-300 hover:scale-105 hover:shadow-lg hover:bg-blue-500 hover:text-white">
        <img loading="lazy"
          src="@/assets/images/home/Icon4.png"
          alt="Technology category icon" class="w-12 aspect-square" />
        <h3 class="mt-4 text-3xl font-bold text-gray-800 hover:text-white">Technology</h3>
        <p class="mt-1 text-zinc-500 hover:text-white">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        </p>
      </article>
      <!-- Repeat similar structure for other categories -->
    </div>
  </section>
</template>

<script setup lang="ts">
</script>

<style scoped>
.category-card {
  transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease, color 0.3s ease;
}

.category-card:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  background-color: #3b82f6; /* Tailwind blue-500 */
  color: #ffffff; /* White text on hover */
}

.category-card h3,
.category-card p {
  transition: color 0.3s ease;
}
</style>
