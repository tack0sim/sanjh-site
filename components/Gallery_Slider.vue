<script setup lang="ts">
defineProps<{
  prevIcon?: string;
  nextIcon?: string;
}>();

const items = [
  "kainat.jpeg",
  "salik.jpeg",
  "motiye.jpeg",
  "postcolonial-series.jpeg",
  "an-mnea-bahar.jpg",
  "military-intervention.jpeg",
  "shiv-kumar.jpg",
  "chan-di-matti.jpg",
  "afghanistan.jpeg",
  "colonial-lahore.jpg",
  "pak-the-reckoning.jpg",
];

onMounted(() => {
  console.log("element mounted!");
});
</script>

<template>
  <UCarousel
    v-slot="{ item }"
    arrows
    loop
    :items="items"
    class="w-full max-w-2xl mx-auto"
  >
    <img
      :src="`/${item}`"
      width="250px"
      height="250px"
      class="w-sm rounded-lg object-cover mx-auto"
    />
  </UCarousel>
</template>
