<script setup lang="ts">
interface TeamMemberProps {
  name: string;
  imageSrc: string;
  ratingImageSrc?: string;
  starsSrc?: string;
  role?: string;
  highlighted?: boolean;
}


defineProps<TeamMemberProps>();
</script>

<template>
  <article
    :class="[
      'flex flex-col grow px-14 py-10 w-full leading-none max-md:px-5 max-md:mt-8',
      highlighted ? 'bg-orange-50' : 'bg-zinc-100'
    ]"
  >
    <img :src="imageSrc" :alt="`Profile photo of ${name}`" class="object-contain self-center w-32 max-w-full rounded-full aspect-square" />
    
    <h2 class="mt-5 text-3xl font-bold tracking-tighter text-gray-800">{{ name }}</h2>
    
    <p v-if="role" class="text-sm text-center text-zinc-500">{{ role }}</p>
    
    <img
      v-if="ratingImageSrc"
      :src="ratingImageSrc"
      alt="Rating"
      class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58]"
    />
    
    <img
      v-else-if="starsSrc"
      :src="starsSrc"
      alt="Stars"
      class="object-contain self-center mt-5 w-28 max-w-full aspect-[6.58]"
    />
  </article>
</template>
