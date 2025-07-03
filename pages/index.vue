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
        <ReferencesCard
          title="Placeholder title"
          author="Full Name (City)"
          body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
    Sed mattis turpis at erat bibendum viverra. 
    Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. 
    Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. 
    Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. 
    Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
        />

        <ReferencesCard
          title="Placeholder title"
          author="Full Name (City)"
          body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis turpis at erat bibendum viverra. Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
        />

        <ReferencesCard
          title="Placeholder title"
          author="Full Name (City)"
          body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis turpis at erat bibendum viverra. Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
        />

        <ReferencesCard
          title="Placeholder title"
          author="Full Name (City)"
          body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed mattis turpis at erat bibendum viverra. Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
        />
      </div>
    </section>

    <!-- Directors Note Section -->
    <section class="prose max-w-[1440px] mx-auto mb-8">
      <h2 class="max-w-[1440px] text-center">Directors Note</h2>

      <div
        class="flex max-sm:flex-col max-sm:justify-center justify-evenly items-center gap-x-6 mx-8"
      >
        <DirectorsCard
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

        <DirectorsCard
          src="amjad.jpeg"
          title="Amjad Saleem Minhas"
          body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
        Sed mattis turpis at erat bibendum viverra. 
        Etiam accumsan, dui eget imperdiet maximus, felis felis varius ex, et cursus sem orci sed dui. 
        Nunc sed leo eget augue egestas pharetra. Aliquam tincidunt sagittis diam. 
        Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. 
        Aliquam sit amet accumsan orci, a consequat tortor. Ut non ante turpis."
          class="md:basis-1/2"
        />
      </div>
    </section>
  </div>
</template>
