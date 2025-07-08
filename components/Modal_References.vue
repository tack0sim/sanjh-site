<script setup lang="ts">
const props = defineProps({
  isOpen: Boolean,
});

const target = ref(null);
const emit = defineEmits(["close-modal"]);
onClickOutside(target, () => emit("close-modal"));
</script>

<template>
  <div
    v-if="props.isOpen"
    id="modal-mask"
    class="flex flex-col justify-center items-center fixed z-[1000] top-0 left-0 w-full h-full bg-[#000]/60"
  >
    <div
      id="modal-wrapper"
      class="relative flex justify-center items-start overflow-y-auto overscroll-none scrollbar-modal"
    >
      <div
        id="modal-container"
        ref="target"
        class="max-md:w-[90vw] lg:w-[70vw] h-fit my-[50px] mx-auto py-0 px-1 rounded-xl shadow-[0_2px_8px_rgba(0, 0, 0, 0.33)]"
      >
        <div
          id="header"
          class="w-6 max-sm:ml-[94%] ml-[96%] mb-2 h-6 pt-0.25 rounded-full bg-[#fff]/90"
        >
          <button class="m-0 p-0 h-6 w-6" @click.stop="emit('close-modal')">
            <Icon name="mdi:close" size="large" />
          </button>
        </div>
        <div id="content" class="px-2 pb-2 h-max bg-[#fff]/90 rounded-md">
          <slot name="content">Default content</slot>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.scrollbar-modal::-webkit-scrollbar {
  display: none;
}
</style>
