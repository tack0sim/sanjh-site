<script setup lang="ts">
const props = defineProps<{
  src?: string;
  title?: string;
  body?: string;
}>();
</script>

<template>
  <article
    class="flex flex-col justify-evenly items-center gap-y-1 pb-2 px-8 bg-[#888888]/50 rounded-xl"
  >
    <NuxtImg
      :src="props?.src"
      format="webp"
      class="max-sm:w-[100vw] max-sm:h-[250px] max-sm:object-contain max-md:w-[250px] md:w-[25vw] md:h-[33vh] md:object-contain rounded-xl"
    />
    <div class="prose">
      <h3 lang="ur" dir="rtl" class="text-lg">{{ props?.title }}</h3>
      <p v-if="props?.body" lang="ur" dir="rtl" class="text-sm">
        {{ props?.body }}
      </p>
    </div>
  </article>
</template>
