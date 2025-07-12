<script setup lang="ts">
const props = defineProps<{
  src?: string;
  title: string;
  body?: string;
}>();
</script>

<template>
  <article
    class="flex flex-col justify-evenly items-center h-max gap-y-1 pb-2 px-8 bg-[#888888]/50 rounded-xl"
  >
    <NuxtImg
      :src="props?.src"
      format="webp"
      class="max-sm:w-[100vw] max-sm:h-[250px] max-sm:object-contain max-md:w-[50vw] md:w-[25vw] md:h-[33vh] md:object-contain rounded-xl"
    />
    <div class="prose">
      <h3 class="text-xl">{{ props?.title }}</h3>
      <p v-if="props?.body" class="text-justify text-sm">{{ props?.body }}</p>
    </div>
  </article>
</template>
