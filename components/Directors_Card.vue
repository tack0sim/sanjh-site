<script setup lang="ts">
const props = defineProps<{
  src?: string;
  title?: string;
  body?: string;
}>();
</script>

<template>
  <article
    class="flex flex-col justify-center items-center mb-4 bg-[#888888]/15 rounded-xl"
  >
    <NuxtImg :src="props?.src" class="md:w-[250px]" />
    <h3>{{ props?.title }}</h3>
    <p class="px-2">{{ props?.body }}</p>
  </article>
</template>
