<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <div class="hero-bg striping-bg">
    <main class="max-w-screen-xl mx-auto grid lg:grid-cols-1 place-items-center pt-48 pb-12">
      <div>
        <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
          Parking Lot Striping
        </h1>
      </div>
    </main>
  </div>
  <LandingContainer>
    <div class="mx-auto grid lg:grid-cols-2 place-items-center">
      <div class="mt-16">
        <p class="text-lg mt-4 text-slate-600">
          A well-striped parking lot not only looks professional but also enhances safety and efficiency. Our expert team ensures clear, durable markings that help manage traffic flow and provide safe, designated parking spaces.
        </p>
        <p class="text-lg mt-4 text-slate-600">
          Clear, precise striping is essential in a warehouse setting to maintain safety and efficiency. We offer comprehensive striping solutions that include walkways, loading zones, and storage areas, helping to streamline operations and reduce the risk of accidents.
        </p>
        <p class="text-lg mt-4 text-slate-600">
          Our sports court striping services are designed to meet the specific needs of each sport. We ensure accurate measurements and high-quality application for a professional finish that enhances the playing experience. Whether for recreational use or competitive play, our striping services deliver outstanding results.
        </p>
      </div>
      <div class="mt-16 px-24 md:order-1">
        <img
          class="transition-transform transform hover:scale-125"
          src="~/assets/img/striping.jpg"
          alt=""
          loading="eager"
        />
      </div>
    </div>
    <LandingCta></LandingCta>
  </LandingContainer>
</template>
