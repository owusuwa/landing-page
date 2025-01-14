<template>
    <section class="bg-gradient-to-r from-blue-500 to-indigo-600 text-white py-20 px-8">
      <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center">
        <div class="text-center md:text-left">
          <h1 class="text-4xl md:text-6xl font-bold leading-tight mb-6">
            Collosal.
          </h1>
          <p class="text-lg mb-6">
            A concise description about your landing page. Keep it impactful.
          </p>
          <div class="space-x-4">
            <button class="bg-white text-blue-600 px-6 py-3 rounded-lg shadow-lg hover:bg-gray-200">
              Get Started
            </button>
            <button class="border border-white px-6 py-3 rounded-lg hover:bg-white hover:text-blue-600">
              Learn More
            </button>
          </div>
        </div>
        <img
          src="/hero-image.png"
          alt="Hero"
          class="mt-10 md:mt-0 md:ml-10 w-full md:w-1/2"
        />
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: "HeroSection",
  };
  </script>
  