<script setup lang="ts">
const props = defineProps<{
  title?: string;
  body?: string;
}>();
</script>
<template>
  <article class="bg-[#888888]/15 mx-auto rounded-xl">
    <h3 class="text-center">{{ props?.title }}</h3>
    <p class="px-2">{{ props?.body }}</p>
  </article>
</template>
