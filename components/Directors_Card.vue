<script setup lang="ts">
const props = defineProps<{
  title?: string;
  body?: string;
}>();
</script>

<template>
  <article class="mb-4 border-1">
    <h3>{{ props?.title }}</h3>
    <p>{{ props?.body }}</p>
  </article>
</template>
