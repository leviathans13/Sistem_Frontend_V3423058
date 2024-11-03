<template>
  <section class="w-full max-w-screen-xl mx-auto px-6 py-4 mt-20 bg-[#faf6ea] rounded-lg relative">
    <div class="flex flex-col md:flex-row items-center ml-20 mt-20 md:items-start gap-8">
      <!-- Left Section (Testimonial Heading) -->
      <div class="max-w-sm text-center md:text-left">
        <p class="uppercase text-[#232536] text-base font-semibold tracking-[3px] mb-2">Testimonials</p>
        <h2 class="text-[#232536] text-4xl font-bold font-['Sen'] leading-[48px] mb-4">
          What people say about our blog
        </h2>
        <p class="text-[#232536] text-base font-normal font-['Inter'] leading-7">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.
        </p>
      </div>

      <!-- Divider -->
      <div class="hidden md:block w-px h-[350px] bg-[#6d6e75] opacity-40"></div>

      <!-- Right Section (Testimonial Content) -->
      <div class="flex flex-col items-center md:items-start gap-4 max-w-md">
        <blockquote class="text-[#232536] text-2xl font-bold font-['Sen'] leading-loose text-center md:text-left">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </blockquote>

        <!-- Profile Information -->
        <div class="flex items-center gap-4 mt-20">
          <img src="@/assets/images/home/ProfilePicture.png" alt="Profile picture" class="w-12 h-12 rounded-full">
          <div>
            <p class="text-[#232536] text-xl font-bold font-['Sen']">Jonathan Vallem</p>
            <p class="text-[#6d6e75] text-base font-normal font-['Inter']">New York, USA</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Navigation Buttons -->
    <div class="flex gap-4 mt-8 justify-center md:justify-end">
      <button class="w-12 h-12 bg-white border border-[#6d6e75] rounded-full flex items-center justify-center hover:bg-gray-200 focus:outline-none">
        <span class="sr-only">Previous</span>
        <img src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/d3f5ae0b05f88175949425804e6e1196fc776b109748d2aa18fea9d1861879d4?apiKey=92b2ee4c788248c09a09fdb756b52067&" alt="Previous" class="w-5 h-5">
      </button>
      <button class="w-12 h-12 bg-[#232536] text-white rounded-full flex items-center justify-center hover:bg-[#1a1a27] focus:outline-none">
        <span class="sr-only">Next</span>
        <img src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/07b676eb085c0c013528d5ff088726665c65f255584b47cb51e5c4e4b02268d0?apiKey=92b2ee4c788248c09a09fdb756b52067&" alt="Next" class="w-5 h-5">
      </button>
    </div>
  </section>
</template>

<script lang="ts">
export default {
  name: 'TestimonialLayout',
};
</script>
