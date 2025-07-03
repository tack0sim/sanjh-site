<script setup lang="ts"></script>

<template>
  <div>
    <!-- Hero Section -->
    <section class="prose max-w-[1440px] mx-auto">
      <h2 class="max-w-[1440px] text-center">Our Bestsellers</h2>
      <HeroMain />
    </section>

    <!-- References Section -->
    <section class="prose max-w-[1440px] mx-auto mb-4">
      <h2 class="text-center">References</h2>
      <div
        class="grid grid-cols-[repeat(auto-fit,minmax(250px,1fr))] mx-6 gap-4 gap-y-6"
      >
        <TransitionComponent>
          <LazyReferencesCard
            hydrate-on-visible
            title="Placeholder title"
            body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
    Sed mattis turpis at erat bibendum viverra. 
    Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. 
    Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. 
    Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. 
    Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
          />
        </TransitionComponent>
        <TransitionComponent>
          <LazyReferencesCard
            hydrate-on-visible
            title="Placeholder title"
            body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis turpis at erat bibendum viverra. Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
          />
        </TransitionComponent>
        <TransitionComponent>
          <LazyReferencesCard
            hydrate-on-visible
            title="Placeholder title"
            body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis turpis at erat bibendum viverra. Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
          />
        </TransitionComponent>
        <TransitionComponent>
          <LazyReferencesCard
            hydrate-on-visible
            title="Placeholder title"
            body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis turpis at erat bibendum viverra. Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
          />
        </TransitionComponent>
      </div>
    </section>

    <!-- Directors Note Section -->
    <section class="prose max-w-[1440px] mx-auto mb-8">
      <h2 class="max-w-[1440px] text-center">Directors Note</h2>
      <div
        class="flex max-sm:flex-col max-sm:justify-center justify-evenly items-center gap-x-6 mx-8"
      >
        <TransitionComponent>
          <LazyDirectorsCard
            hydrate-on-visible
            src="farkhanda.jpeg"
            title="Farkhanda Amjad"
            body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
        Sed mattis turpis at erat bibendum viverra. 
        Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. 
        Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. 
        Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. 
        Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
            class="md:basis-1/2"
          />
        </TransitionComponent>
        <TransitionComponent>
          <LazyDirectorsCard
            hydrate-on-visible
            title="Amjad Saleem Minhas"
            body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
        Sed mattis turpis at erat bibendum viverra. 
        Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. 
        Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. 
        Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. 
        Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
            class="md:basis-1/2"
          />
        </TransitionComponent>
      </div>
    </section>
  </div>
</template>
