<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import HeaderBlog from '@/components/BlogPost/HeaderBlog.vue'
import BlogContent from '@/components/BlogPost/BlogContent.vue'
import BlogPostSection from '@/components/BlogPost/BlogPostSection.vue'

</script>

<template>
  <MainLayout>
    <HeaderBlog>
    </HeaderBlog>
    <BlogContent/>
    <BlogPostSection>
    </BlogPostSection>
  </MainLayout>
</template>

<script lang="ts">
import {
  defineComponent
} from 'vue'

export default defineComponent({
  name: 'BlogLayout'
})

</script>

<style scoped>

</style>
