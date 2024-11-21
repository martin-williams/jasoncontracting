<template>
  <div class="hero-bg">
    <main class="max-w-screen-xl mx-auto grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8">
      <div class="p-24 md:order-1 hidden md:block">
        <img
          class="rounded-full transition-transform transform hover:scale-125"
          src="~/assets/img/jason-hero.jpg"
          alt="Jason"
          loading="eager"
          format="avif"
          width="512"
          height="512"
        />
      </div>

      <div>
        <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
          Give <em>US</em><br />Your Stress
        </h1>
        <p class="text-lg mt-4 text-slate-600 max-w-xl">
          Established in September 2013 as a commercial specialty general contractor focusing on assiting
          facility owners and managers with building repairs.
        </p>
        <div class="mt-6 flex flex-col sm:flex-row gap-3">
          <LandingLink
            href="/contact"
            >Contact Us</LandingLink
          >
          <LandingLink
            size="lg"
            styleName="outline"
            href="#services"
            >Our Services</LandingLink
          >
        </div>
      </div>
    </main>
  </div>
</template>
