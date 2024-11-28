<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <div class="hero-bg strengthening-bg">
    <main class="max-w-screen-xl mx-auto grid lg:grid-cols-1 place-items-center pt-48 pb-12">
      <div>
        <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
          Carbon Fiber Strengthening
        </h1>
      </div>
    </main>
  </div>
  <LandingContainer>
    <div class="mx-auto grid lg:grid-cols-2 place-items-center">
      <div class="mt-16">
        <p class="text-lg mt-4 text-slate-600">
          JCR is a leader in carbon fiber strengthening solutions, offering advanced techniques to reinforce and stabilize concrete structures. With unmatched strength-to-weight ratio and durability, carbon fiber provides a cost-effective alternative to traditional reinforcement methods.
        </p>
        <p class="text-lg mt-4 text-slate-600">
          Our services include wrapping columns to improve load capacity, strengthening beams to support heavier demands, and reinforcing slabs to prevent cracking and failure. We’ve worked on a variety of projects, from upgrading aging structures to meet modern load requirements to repairing damage without the need for extensive demolition.
        </p>
        <p class="text-lg mt-4 text-slate-600">
          By utilizing cutting-edge materials and precise installation methods, JCR ensures that your structures are stronger, safer, and built to last for years to come. Trust us to deliver high-performance solutions tailored to your unique needs.
        </p>
      </div>
      <div class="mt-16 px-24 md:order-1">
        <img
          class="transition-transform transform hover:scale-125"
          src="~/assets/img/workers.jpg"
          alt=""
          loading="eager"
        />
      </div>
    </div>
    <LandingCta></LandingCta>
  </LandingContainer>
</template>
