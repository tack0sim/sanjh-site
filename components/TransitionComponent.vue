<script setup lang="ts">
import { useElementVisibility } from "@vueuse/core";

const target = ref(null);
const show = useElementVisibility(target);
</script>

<template>
  <div ref="target">
    <Transition
      name="fade"
      enter-active-class="transition duration-1000 transform ease-out"
      enter-from-class="opacity-0 translate-y-4"
      enter-to-class="opacity-100 translate-y-0"
    >
      <slot v-if="show" />
    </Transition>
  </div>
</template>
