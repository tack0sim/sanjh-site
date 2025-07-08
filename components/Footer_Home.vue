<script setup lang="ts"></script>

<template>
  <footer class="bottom-0 bg-[#000000] max-w-[1440px] mx-auto h-[150px]">
    <div
      class="max-w-[1440px] flex justify-between items-center max-sm:flex-col max-sm:justify-start mx-4 md:mx-8 py-4 md:py-8 text-white font-extralight"
    >
      <div class="flex justify-start items-center gap-x-1">
        <Icon name="mdi:copyright" />
        <p>2025 Sanjh Publications</p>
      </div>
      <NuxtLink
        to="https://www.facebook.com/SanjhPublications"
        target="_blank"
        class="flex justify-start items-center gap-x-1 text-white font-extralight"
      >
        <Icon name="mdi:facebook" />
        <p>Follow us on Facebook</p>
      </NuxtLink>
    </div>
    <div
      class="flex justify-end max-sm:flex-col max-sm:items-center max-w-[1440px] mx-4 pt-9 md:mx-8 md:pt-8 text-white font-extralight"
    >
      <p class="text-xs">Made with 💜 by Talha Minhas</p>
    </div>
  </footer>
</template>
