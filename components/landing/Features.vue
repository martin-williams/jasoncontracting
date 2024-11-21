<script setup>
const features = [
  {
    title: "Structural Concrete Repair",
    description:
      "Restore and strengthen damaged concrete for long-lasting durability.",
    icon: "bx:bxs-wrench",
    url: "#",
  },
  {
    title: "Carbon Fiber Strengthening",
    description:
      "Reinforce structures with cutting-edge carbon fiber technology.",
    icon: "bx:bxs-wrench",
    url: "#",
  },
  {
    title: "Parking Lot Striping",
    description:
      "Enhance safety and organization with clear, professional parking lot striping.",
    icon: "bx:bxs-wrench",
    url: "#",
  },
];
</script>

<template>
  <div class="mt-16">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      About Jason Contracting &amp; Repair
    </h2>
    <p class="text-lg mt-4 text-slate-600">
      Established in September 2013 as a commercial specialty general contractor focusing on
      assisting facility owners and managers with building repairs  they were not able to find
      others to complete.  Our motto Give US your stress was aimed at taking the load of these busy
      folks as they have many responsibilities and duties. Our autonomous management of the
      building repairs and modifications  allowed them to focus on other responsibilities they
      normally deal with thus making life easier for them.
    </p>
    <p class="text-lg mt-4 text-slate-600">
      Along with these services we would also perform building renovations and additions, find and
      repair water and air leaks, assess building conditions and deficiencies, and perform building
      strengthening with carbon fiber and structural concrete repairs.
    </p>
  </div>

  <div id="services" class="grid sm:grid-cols-2 md:grid-cols-3 mt-16 gap-16">
    <div v-for="item of features" class="flex gap-4 items-start">
      <div class="mt-1 bg-black rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 mb-4 leading-relaxed">
          {{ item.description }}
        </p>
        <LandingLink :href="item.url">
          Learn More
        </LandingLink>
      </div>
    </div>
  </div>
</template>
