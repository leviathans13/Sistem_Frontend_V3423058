<script setup lang="ts">
interface CategoryCardProps {
  title: string;
  description: string;
  iconSrc: string;
  isHighlighted?: boolean;
}

defineProps<CategoryCardProps>();
</script>

<template>
  <article class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
    <div :class="[
      'flex flex-col grow items-start p-8 w-full border border-solid',
      isHighlighted ? 'bg-blue-600' : 'border-zinc-500',
      'max-md:px-5 max-md:mt-8'
    ]">
      <img :src="iconSrc" :alt="`${title} category icon`" class="object-contain w-12 aspect-square" />
      <h3 :class="[
        'mt-4 text-3xl font-bold tracking-tighter leading-none',
        isHighlighted ? 'text-orange-50' : 'text-gray-800'
      ]">
        {{ title }}
      </h3>
      <p :class="[
        'self-stretch mt-1 text-base leading-7',
        isHighlighted ? 'text-white' : 'text-zinc-500'
      ]">
        {{ description }}
      </p>
    </div>
  </article>
</template>
