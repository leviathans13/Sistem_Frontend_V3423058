<template>
  <article class="flex flex-col items-start font-bold text-gray-800 max-w-[666px] mx-auto mt-12 mb-12">
    <header class="flex flex-col items-start gap-2">
      <div class="flex items-center gap-4 text-amber-300 text-3xl tracking-tighter leading-none w-full">
        <img
          loading="lazy"
          src="@/assets/images/blog-post/ProfilePicture.png"
          alt="Profile picture of Andrew Jonson"
          class="object-contain w-12 h-12 rounded-full"
        />
        <Router-Link to="/author" class="flex flex-col items-start leading-tight">
          <h1 class="opacity-[0.87]">Andrew Jonson</h1>
          <p class="text-sm text-gray-500 font-normal">Posted on 27th January 2022</p>
        </Router-Link>
      </div>
    </header>

    <h2 class="self-start mt-9 text-5xl tracking-tighter leading-[64px] max-md:max-w-full max-md:text-4xl max-md:leading-[60px]">
        Step-by-step guide to choosing great font pairs
    </h2>

    <section class="flex items-center gap-2 mt-4 text-2xl text-gray-600 whitespace-nowrap">
      <img
        loading="lazy"
        src="@/assets/images/home/Icon2.png"
        alt="Startup category icon"
        class="object-contain w-6 h-6"
      />
      <p class="text-2xl">Startup</p>
    </section>
  </article>
  <section class="image-container mt-12 px-4 mb-12">
    <img
      loading="lazy"
      src="@/assets/images/blog-post/photo-of-woman-wearing-eyeglasses-3184405.png"
      alt=""
      class="object-contain w-full max-w-[90%] mx-auto aspect-[2.2]"
      role="presentation"
    />
  </section>
</template>

<style scoped>
.builder-component {
  max-width: none !important;
}
</style>
