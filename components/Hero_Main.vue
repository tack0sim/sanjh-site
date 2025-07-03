<script setup lang="ts"></script>

<template>
  <section class="flex flex-col gap-y-4 px-8 mb-4">
    <TransitionComponent>
      <LazyCardHeroEng
        hydrate-on-visible
        src="military-intervention.jpeg"
        title="placeholder title"
        body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis turpis at erat bibendum viverra. Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
      />
    </TransitionComponent>
    <TransitionComponent>
      <LazyCardHeroUrdu
        hydrate-on-visible
        src="afghanistan.jpeg"
        title="مثالی ٹائٹل"
        body="مثالی لکھت"
      />
    </TransitionComponent>
  </section>
</template>
