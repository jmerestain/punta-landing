<template>
  <div id="app" class="flex flex-col h-full">
    <header>
      <Navbar />
    </header>
    <main>
      <div id="header-section" class="flex flex-col justify-center mt-10 lg:mt-20 pb-10 gap-5">
        <div class="px-4 flex flex-col max-w-3xl mx-auto gap-3">
          <p class="select-none text-left ml-4 text-4xl font-bold text-blue-900">Welcome to</p>
          <img class="mx-auto select-none sm:max-w-md md:max-w-xl lg:max-w-2xl"
          :src="require('@/assets/svg/header-main.svg')" />
        </div>
        <div class="flex flex-row justify-center items-center gap-3 flex-wrap p-2">
          <a href="#"
          class="px-3 py-2 border-2 border-blue-800
          bg-blue-800 text-white rounded-lg font-medium shadow-md">
            Become an Ambassador
          </a>
          <a href="#"
          class="px-3 py-2 border-2 border-blue-800
          text-blue-800 rounded-lg font-medium shadow-md">
            Sign up for Beta
          </a>
        </div>
      </div>
      <div id="section-2" class="bg-gray-200 flex flex-col pt-10 pb-10">
        <div class="mx-auto flex flex-row flex-wrap justify-center gap-8 p-4 items-center">
          <div class="bg-pink-200">
            <iframe class="rounded-md shadow-md" width="372" height="210" src="https://www.youtube.com/embed/KFSfu66tlEQ?controls=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
          <div class="max-w-sm mx-2">
            <p class="text-2xl font-bold text-blue-900">
                What is Punta?
            </p>
            <p class="mt-3 text-justify">
              Punta is an online service platform that allows you to
              innovate, connect, and avail of services easily.
            </p>
            <p class="mt-3 text-justify">
              We aim to empower a customer-driven service community where
              people can avail of a variety of services to fulfill their needs, online or at-home.
            </p>
          </div>
        </div>
      </div>
    </main>
    <footer>
    </footer>
    <img id="blue-artifact" class="absolute hidden lg:block"
    :src="require('@/assets/svg/header-artifact-blue.svg')" />
    <img id="pink-artifact" class="absolute hidden lg:block"
    :src="require('@/assets/svg/header-artifact-pink.svg')" />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'App',
  components: {
    Navbar,
  },
};
</script>

<style>
html, body {
  min-height: 100vh;
  height: 100vh;
}

.bg-punta {
  background: #A34C9D;
}
.border-punta {
  border: 2px solid #A34C9D;
}
.text-punta {
  color: #A34C9D;
}
#blue-artifact {
  right: 1rem;
  bottom: 12rem;
}
#pink-artifact {
  left: 0.5rem;
  top: 8rem;
}
</style>
