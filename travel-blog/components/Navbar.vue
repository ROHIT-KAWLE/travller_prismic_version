<template>
  <nav class="fixed top-0 w-full z-50 bg-slate-950/90 backdrop-blur-md">
    <div
      class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center"
    >
      <h1 class="text-3xl font-bold text-cyan-400">
        ✈ WanderNest
      </h1>

      <div class="flex gap-10 text-lg text-white">
        <NuxtLink to="/" class="hover:text-cyan-400">
          Home
        </NuxtLink>

        <NuxtLink to="/blogs" class="hover:text-cyan-400">
          Blogs
        </NuxtLink>

        <a href="#" class="hover:text-cyan-400">
          Contact
        </a>
      </div>
    </div>
  </nav>
</template>