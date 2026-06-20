<template>
  <div class="bg-slate-950 min-h-screen text-white">

    <Navbar />

    <section class="pt-32 text-center pb-16">
      <h1 class="text-6xl font-bold mb-4">
        Travel Stories
      </h1>

      <p class="text-slate-400 text-xl">
        Explore destinations across India
      </p>
    </section>

    <div class="max-w-7xl mx-auto px-6 pb-20">

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
            <h2 class="text-2xl font-bold">
              Goa Travel Guide
            </h2>
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
            <h2 class="text-2xl font-bold">
              Jaipur Hidden Gems
            </h2>
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
            <h2 class="text-2xl font-bold">
              Kerala Backwaters
            </h2>
          </div>
        </NuxtLink>

      </div>

    </div>

  </div>
</template>