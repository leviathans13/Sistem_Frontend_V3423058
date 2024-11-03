  <!-- src/components/Category/CategorySection.vue -->
  <template>
    <section class="px-20 py-12 max-md:px-5">
      <h2 class="text-4xl font-bold tracking-tighter text-center text-gray-800 mb-12">
        Choose A Category
      </h2>
      <div class="grid grid-cols-4 gap-5 max-md:grid-cols-1">
        <!-- Category Cards -->
        <article class="border border-zinc-500 p-8">
          <img loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/1f6caa464f89441947adf7010f508de88e396385dc4e183a16249f0d3d4ce590?apiKey=c67971bfdb224af7ac1abd38d94b93d0&"
            alt="Business category icon" class="w-12 aspect-square" />
          <h3 class="mt-4 text-3xl font-bold text-gray-800">Business</h3>
          <p class="mt-1 text-zinc-500">
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
  </style>

