<script setup lang="ts">
const props = defineProps<{
  title?: string;
  author?: string;
  blurb?: string;
  blurbUrdu?: string;
  body?: string;
  bodyUrdu?: string;
}>();

const formattedBody = computed(() => props?.body?.replace(/\n/g, "<br />"));
const formattedBodyUrdu = computed(() =>
  props?.bodyUrdu?.replace(/\n/g, "<br />")
);

const isModalOpen = ref(false);

function openModal() {
  isModalOpen.value = true;
  document.body.classList.add("overflow-hidden");
}
function closeModal() {
  isModalOpen.value = false;
  document.body.classList.remove("overflow-hidden");
}
</script>
<template>
  <article class="bg-[#888888]/15 mx-auto h-min rounded-xl">
    <div class="flex flex-col justify-start items-start">
      <p class="px-2 mb-0 mt-0 pt-2 pb-0">
        <Icon v-if="props?.blurb" name="mdi:format-quote-open" />
        {{ props?.blurb }}
        <Icon v-if="props?.blurb" name="mdi:format-quote-close" class="m-0" />
      </p>
      <p dir="rtl" lang="ur" class="px-2 mb-0 mt-0 pt-0 pb-2">
        <Icon v-if="props?.blurbUrdu" name="mdi:format-quote-close" />
        {{ props?.blurbUrdu }}
        <Icon
          v-if="props?.blurbUrdu"
          name="mdi:format-quote-open"
          class="m-0"
        />
      </p>
      <button
        v-if="props?.body || props?.bodyUrdu"
        class="rounded-lg bg-[#888]/30 ml-2 hover:bg-[#888]/60"
        @click="openModal"
      >
        <p class="px-2 text-sm">Read more...</p>
      </button>
    </div>
    <p class="italic text-center mt-0 mb-0">{{ props?.author }}</p>
    <!-- Modal -->
    <ModalReferences :is-open="isModalOpen" @close-modal="closeModal">
      <template #content>
        <div>
          <p v-html="formattedBody" />
          <p dir="rtl" lang="ur" v-html="formattedBodyUrdu" />
        </div>
      </template>
    </ModalReferences>
  </article>
</template>
