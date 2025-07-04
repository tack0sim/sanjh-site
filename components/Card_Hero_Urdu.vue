<script setup lang="ts">
const props = defineProps<{
  src?: string;
  title?: string;
  body?: string;
}>();
</script>

<template>
  <article
    class="flex max-sm:flex-col flex-row-reverse justify-start items-center gap-x-4 px-12 bg-[#888888]/50 rounded-xl"
  >
    <NuxtImg
      :src="props?.src"
      format="webp"
      class="max-sm:w-[100vw] max-sm:h-[250px] max-sm:object-cover max-md:w-[250px] w-[400px] h-auto rounded-xl"
    />
    <div class="prose max-w-[1440px]">
      <h3 lang="ur" dir="rtl">{{ props?.title }}</h3>
      <p lang="ur" dir="rtl">{{ props?.body }}</p>
    </div>
  </article>
</template>
