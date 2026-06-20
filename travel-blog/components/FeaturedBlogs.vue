<template>
  <section class="max-w-7xl mx-auto py-24 px-6">

    <h2 class="text-5xl font-bold text-center mb-16 text-white">
      Latest Travel Stories
    </h2>

    <div class="grid md:grid-cols-3 gap-8">

      <NuxtLink
        to="/blogs/goa-guide"
        class="bg-slate-900 rounded-3xl overflow-hidden shadow-xl hover:scale-105 transition"
      >
        <img
          src="/images/goa.png"
          class="h-64 w-full object-cover"
        >

        <div class="p-6">
          <h3 class="text-2xl font-bold text-white">
            Goa Travel Guide
          </h3>
        </div>
      </NuxtLink>

      <NuxtLink
        to="/blogs/jaipur-guide"
        class="bg-slate-900 rounded-3xl overflow-hidden shadow-xl hover:scale-105 transition"
      >
        <img
          src="/images/jaipur.png"
          class="h-64 w-full object-cover"
        >

        <div class="p-6">
          <h3 class="text-2xl font-bold text-white">
            Jaipur Hidden Gems
          </h3>
        </div>
      </NuxtLink>

      <NuxtLink
        to="/blogs/kerala-guide"
        class="bg-slate-900 rounded-3xl overflow-hidden shadow-xl hover:scale-105 transition"
      >
        <img
          src="/images/kerala.png"
          class="h-64 w-full object-cover"
        >

        <div class="p-6">
          <h3 class="text-2xl font-bold text-white">
            Kerala Backwaters
          </h3>
        </div>
      </NuxtLink>

    </div>

  </section>
</template>