<script setup lang="ts">
import { Analytics } from "@vercel/analytics/nuxt";

useHead({
  title: "Sanjh Publications",
});
</script>

<template>
  <Analytics />
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
