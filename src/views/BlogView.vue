<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import FeaturedPost from '@/components/Blog/FeaturedPost.vue'
import AllPost from '@/components/Blog/BlogPost.vue'
import CategorySection from '@/components/Blog/CategorySection.vue'

</script>

<template>
  <MainLayout>
    <FeaturedPost>
    </FeaturedPost>
    <AllPost category="News" title="Some title" description="Some description" />
    <CategorySection>
    </CategorySection>
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
