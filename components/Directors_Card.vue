<script setup lang="ts">
const props = defineProps<{
  src?: string;
  title?: string;
  body?: string;
  bodyUrdu?: string;
}>();

const formattedBody = computed(() => props?.bodyUrdu?.replace(/\n/g, "<br />"));
</script>

<template>
  <article
    class="flex flex-col justify-start items-center h-[max] mb-4 pb-0 bg-[#888888]/15 rounded-xl m-0"
  >
    <NuxtImg
      :src="props?.src"
      format="webp"
      class="max-sm:w-[250px] sm:w-[200px] md:w-[250px] rounded-full"
    />
    <h3 class="mt-0 mb-0">{{ props?.title }}</h3>
    <p v-if="!props?.bodyUrdu" class="px-2">{{ props?.body }}</p>
    <p dir="rtl" lang="ur" class="px-2 md:text-lg" v-html="formattedBody" />
  </article>
</template>
