<script setup lang="ts">
const props = defineProps<{
  src?: string;
  title?: string;
  body?: string;
}>();
</script>

<template>
  <article
    class="flex justify-start items-center max-sm:flex-col gap-x-4 px-12 bg-[#888888]/15 rounded-xl"
  >
    <NuxtImg
      :src="props?.src"
      format="webp"
      class="max-sm:w-[100vw] max-sm:h-[250px] max-sm:object-cover max-md:basis-1/3 w-[400px] h-auto rounded-xl"
    />
    <div class="prose max-w-[1440px] max-md:basis-2/3">
      <h3>{{ props?.title }}</h3>
      <p class="text-justify">{{ props?.body }}</p>
    </div>
  </article>
</template>
