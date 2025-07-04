<script setup lang="ts">
const props = defineProps<{
  src?: string;
  title?: string;
  body?: string;
}>();
</script>

<template>
  <article
    class="flex flex-col justify-center items-center mb-4 bg-[#888888]/15 rounded-xl m-0"
  >
    <NuxtImg
      :src="props?.src"
      format="webp"
      class="max-sm:w-[250px] sm:w-[200px] md:w-[250px] rounded-full"
    />
    <h3 class="mt-0 mb-0">{{ props?.title }}</h3>
    <p class="px-2">{{ props?.body }}</p>
  </article>
</template>
