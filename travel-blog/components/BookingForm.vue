<template>
  <section class="max-w-7xl mx-auto -mt-16 relative z-20 px-6">

    <div class="bg-white rounded-3xl shadow-2xl p-8">

      <h2 class="text-5xl font-bold text-center mb-8 text-slate-900">
        Plan Your Journey
      </h2>

      <div class="grid md:grid-cols-5 gap-4">

        <input
          type="text"
          placeholder="Destination"
          class="border border-gray-300 p-4 rounded-xl text-slate-900 focus:outline-none focus:ring-2 focus:ring-green-600"
        />

        <input
          type="date"
          class="border border-gray-300 p-4 rounded-xl text-slate-900 focus:outline-none focus:ring-2 focus:ring-green-600"
        />

        <input
          type="date"
          class="border border-gray-300 p-4 rounded-xl text-slate-900 focus:outline-none focus:ring-2 focus:ring-green-600"
        />

        <input
          type="number"
          placeholder="Guests"
          class="border border-gray-300 p-4 rounded-xl text-slate-900 focus:outline-none focus:ring-2 focus:ring-green-600"
        />

        <button
          class="bg-green-700 text-white font-semibold rounded-xl hover:bg-green-800 transition-all duration-300"
        >
          Search
        </button>

      </div>

    </div>

  </section>
</template>