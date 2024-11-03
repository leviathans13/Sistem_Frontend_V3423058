<script setup lang="ts">
import TeamMember from './AuthorMember.vue';
import medsosIcon from '@/assets/images/home/medsos.png';
import authIcon1 from '@/assets/images/home/man-in-yellow-button-up-shirt-wearing-black-framed-eyeglasses-7562313.png';
import authIcon2 from '@/assets/images/home/woman-in-white-and-black-striped-shirt-wearing-black-sunglasses-3671083.png';
import authIcon3 from '@/assets/images/home/fashion-woman-cute-shoes-5704849.png';
import authIcon4 from '@/assets/images/home/content-baker-with-delicious-puff-in-cafeteria-6205509.png';


const teamMembers = [
  {
    name: 'Floyd Miles',
    role: 'Content Writer @Company',
    imageSrc: authIcon1,
    ratingImageSrc: medsosIcon
  },
  {
    name: 'Diane Russell',
    role: 'Content Writer @Company',
    imageSrc: authIcon2,
    ratingImageSrc: medsosIcon
  },
  {
    name: 'Jenny Wilson',
    role: 'Content Writer @Company',
    imageSrc: authIcon3,
    ratingImageSrc: medsosIcon
  },
  {
    name: 'Leslie Alexa',
    role: 'Content Writer @Company',
    imageSrc: authIcon4,
    ratingImageSrc: medsosIcon
  },
];
</script>

<template>
  <main class="mt-20 w-full mx-auto max-w-screen-xl max-md:max-w-full">
    <h4 class="text-6xl text-center font-extrabold tracking-tight leading-tight text-gray-800 max-md:text-5xl">
      List Of Authors
    </h4>
    <section
      class="mt-12 grid grid-cols-4 gap-5 max-md:flex max-md:flex-col max-md:items-center"
    >
      <div
        v-for="member in teamMembers"
        :key="member.name"
        class="flex flex-col w-full"
      >
        <TeamMember v-bind="member" />
      </div>
    </section>
  </main>
</template>

