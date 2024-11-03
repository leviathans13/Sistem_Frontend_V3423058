<template>
  <main class="flex flex-col px-20 mt-16 w-full max-md:px-5 max-md:mt-10 max-md:max-w-full">
    <header>
      <h1 class="self-start text-5xl font-bold tracking-tighter leading-none text-gray-800 max-md:text-4xl">
        All posts
      </h1>
      <hr class="shrink-0 mt-8 h-px border border-solid bg-zinc-500 border-zinc-500 opacity-[0.32] max-md:max-w-full" />
    </header>

    <section class="mt-16 w-full max-w-[1147px] max-md:mt-10 max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <aside class="flex flex-col w-[44%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col grow max-md:mt-8 max-md:max-w-full">
            <img loading="lazy" src="@/assets/images/blog/two-women-in-front-of-dry-erase-board-1181533.png" alt="Design tips article featured image" class="object-contain w-full aspect-[1.54] max-md:max-w-full" />
            <img loading="lazy" src="@/assets/images/blog/photo-of-people-doing-handshakes-3183197.png" alt="Web design clients article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
            <img loading="lazy" src="@/assets/images/blog/photo-of-woman-looking-at-man-3183173.png" alt="Logo design trends article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
            <img loading="lazy" src="@/assets/images/blog/photo-of-people-walking-on-hallway-3182811.png" alt="Figma design systems article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
            <img loading="lazy" src="@/assets/images/blog/two-women-in-front-of-dry-erase-board-1181533.png" alt="Font sizes article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
          </div>
        </aside>

        <article class="flex flex-col ml-5 w-[56%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col self-stretch my-auto text-base font-semibold leading-none text-amber-300 max-md:mt-10 max-md:max-w-full">
            <BlogPostSection
              category="Startup"
              title="Design tips for designers that cover everything you need"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Business"
              title="How to build rapport with your web design clients"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Startup"
              title="Logo design trends to avoid in 2022"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Technology"
              title="8 Figma design systems you can download for free today"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Economy"
              title="Font sizes in UI design: The complete guide to follow"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />
          </div>
        </article>
      </div>
    </section>

    <nav class="flex gap-4 self-center mt-16 ml-3.5 max-w-full font-bold text-center w-[174px] max-md:mt-10">
      <button class="grow my-auto text-2xl leading-none text-zinc-500" aria-label="Previous page">
        &lt; Prev
      </button>
      <button class="text-3xl tracking-tighter leading-none text-gray-800" aria-label="Next page">
        Next &gt;
      </button>
    </nav>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import BlogPostSection from './BlogPostSection.vue'

export default defineComponent({
  name: 'BlogPosts',
  components: {
    BlogPostSection
  }
})
</script>
