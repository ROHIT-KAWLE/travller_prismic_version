<script setup>
const route = useRoute()

const blogs = {
  'goa-guide': {
    title: 'Ultimate Goa Travel Guide',
    image: '/images/goa.png',
    content:
      'Goa is famous for its beaches, nightlife, Portuguese architecture, water sports and delicious seafood. Whether you love adventure or relaxation, Goa has something for everyone.'
  },

  'jaipur-guide': {
    title: 'Hidden Gems Of Jaipur',
    image: '/images/jaipur.png',
    content:
      'Jaipur, the Pink City of India, offers magnificent forts, Hawa Mahal, bustling bazaars and rich Rajasthani culture.'
  },

  'kerala-guide': {
    title: 'Kerala Backwaters Experience',
    image: '/images/kerala.png',
    content:
      'Kerala offers peaceful backwaters, houseboats, lush greenery and breathtaking natural beauty.'
  }
}

const blog = blogs[route.params.slug]
</script>

<template>
  <div class="bg-slate-950 min-h-screen text-white">
    <Navbar />

    <section class="max-w-5xl mx-auto px-6 pt-32 pb-20">
      <img
        :src="blog.image"
        class="w-full h-[500px] object-cover rounded-3xl shadow-2xl"
      >

      <h1 class="text-5xl font-bold mt-8 mb-6">
        {{ blog.title }}
      </h1>

      <p class="text-xl text-slate-300 leading-9">
        {{ blog.content }}
      </p>
    </section>
  </div>
</template>