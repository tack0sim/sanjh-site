<script setup lang="ts">
const props = defineProps<{
  title?: string;
  author?: string;
  body?: string;
}>();
</script>
<template>
  <article class="bg-[#888888]/15 mx-auto h-min rounded-xl">
    <p class="px-2 mb-0 mt-0 pt-2">
      <Icon name="mdi:format-quote-open" />
      {{ props?.body }}
      <Icon name="mdi:format-quote-close" class="m-0" />
    </p>
    <p class="italic text-center mt-0 mb-0">{{ props?.author }}</p>
  </article>
</template>
