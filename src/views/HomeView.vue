<template>
  <MainLayout>
    <HeroSection />
    <FeaturedPosts />
    <AboutSection />
    <CategorySection />
    <StorySection />
    <AuthorGrid />
    <LogoSection />
    <TestimonialSection />
  </MainLayout>
</template>

<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue';
import HeroSection from '@/components/Home/HeroSection.vue';
import FeaturedPosts from '@/components/Home/FeaturedPost.vue';
import AboutSection from '@/components/Home/AboutSection.vue';
import CategorySection from '@/components/Home/CategorySection.vue';
import StorySection from '@/components/Home/StorySection.vue';
import AuthorGrid from '@/components/Home/AuthorGrid.vue';
import LogoSection from '@/components/Home/LogoSection.vue';
import TestimonialSection from '@/components/Home/TestimonialSection.vue';
</script>
