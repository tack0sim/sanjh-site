<script setup lang="ts"></script>

<template>
  <section
    class="grid grid-cols-[repeat(auto-fit,minmax(250px,1fr))] gap-4 gap-y-2 px-8"
  >
    <LazyCardHeroUrdu
      hydrate-on-visible
      src="an-mnea-bahar.jpg"
      title="ان منیا بھار"
    />
    <LazyCardHeroUrdu
      hydrate-on-visible
      src="military-intervention.jpeg"
      title="پاکستان: جمہوریت اور فوجی مداخلتیں"
    />
    <LazyCardHeroUrdu hydrate-on-visible src="shiv-kumar.jpg" title="کلام شو" />
    <LazyCardHeroUrdu
      hydrate-on-visible
      src="chan-di-matti.jpg"
      title="چن دى مٹی"
    />
    <LazyCardHeroUrdu
      hydrate-on-visible
      src="afghanistan.jpeg"
      title="افغانستان"
    />
    <LazyCardHeroEng
      hydrate-on-visible
      src="colonial lahore.jpg"
      title="Colonial Lahore"
    />
    <LazyCardHeroEng
      hydrate-on-visible
      src="pak-the-reckoning.jpg"
      title="Pakistan: The Reckoning Begins"
    />
  </section>
</template>
