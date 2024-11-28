<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <div class="hero-bg repair-bg">
    <main class="max-w-screen-xl mx-auto grid lg:grid-cols-1 place-items-center pt-48 pb-12">
      <div>
        <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
          Structural Concrete Repair
        </h1>
      </div>
    </main>
  </div>
  <LandingContainer>
    <div class="mx-auto grid lg:grid-cols-2 place-items-center">
      <div class="mt-16">
        <p class="text-lg mt-4 text-slate-600">
          For over a decade, JCR has been a trusted leader in structural concrete repair across the San Antonio area. Our team specializes in innovative, cost-effective solutions to restore and reinforce distressed structural concrete. As pioneers in introducing carbon fiber strengthening, we've provided a cutting-edge approach to repairing and enhancing concrete structures.
        </p>
        <p class="text-lg mt-4 text-slate-600">
          Our expertise spans a wide range of projects, including reinforcing concrete beams in parking garages, wrapping columns to increase load capacity, and repairing double tees that have been overloaded or damaged. We've also excelled at repairing double tee flanges while keeping parking structures fully operational and strengthening aging buildings to handle heavier loads.
        </p>
        <p class="text-lg mt-4 text-slate-600">
          Additionally, we address cracks and spalling in slabs and walls with precision techniques like epoxy injection, spall repairs, and the installation of carbon fiber stitches. At JCR, we combine advanced technology with unparalleled craftsmanship to ensure the durability and reliability of every structure we work on.
        </p>
      </div>
      <div class="mt-16 px-24 md:order-1">
        <img
          class="transition-transform transform hover:scale-125"
          src="~/assets/img/AdobeStock_198555567.jpg"
          alt=""
          loading="eager"
        />
      </div>
    </div>
    <LandingCta></LandingCta>
  </LandingContainer>
</template>
