<script setup lang="ts">
const props = defineProps<{
  title?: string;
  author?: string;
  body?: string;
}>();
</script>
<template>
  <article class="bg-[#888888]/15 mx-auto rounded-xl">
    <h3 class="text-center mb-0">{{ props?.title }}</h3>
    <p class="italic text-center mt-0 mb-0">{{ props?.author }}</p>

    <p class="px-2">
      <Icon name="mdi:format-quote-open" />
      {{ props?.body }}
      <Icon name="mdi:format-quote-close" />
    </p>
  </article>
</template>
