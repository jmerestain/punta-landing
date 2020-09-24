<template>
  <div id="app" class="flex flex-col h-full">
    <header>
      <Navbar />
    </header>
    <main>
      <div id="header-section" class="flex flex-col justify-center mt-10 lg:mt-20 pb-10 gap-5">
        <div class="px-4 flex flex-col max-w-3xl mx-auto gap-3">
          <h2 class="select-none text-left ml-4 text-4xl font-bold text-blue-900">Welcome to</h2>
          <img class="mx-auto select-none sm:max-w-md md:max-w-xl lg:max-w-2xl"
          :src="require('@/assets/svg/header-main.svg')" />
        </div>
        <div class="flex flex-row justify-center items-baseline
        lg:space-x-3 space-y-2 flex-wrap p-2 space-x-0">
          <a href="https://forms.gle/isVYj2RKhy3LVEQF9" target="_blank"
          class="px-3 py-2 border-2 border-blue-800
          text-blue-800 rounded-lg font-bold tracking-wider shadow-md">
            Become an Ambassador
          </a>
          <a href="https://forms.gle/AB8AEHY3CAfNMZ336" target="_blank"
          class="px-3 py-2 border-2 border-blue-800
          bg-blue-800 text-white rounded-lg font-bold tracking-wider shadow-md">
            Sign up for Beta
          </a>
        </div>
      </div>
      <div id="section-2" class="bg-gray-200 flex flex-col pt-10 pb-10">
        <div class="flex flex-row flex-wrap mx-auto justify-between
        space-y-4 p-4 items-center container max-w-screen-lg space-y-6 md:space-y-6 lg:space-y-0">
          <div class="bg-pink-200 rounded-md shadow-md mx-auto lg:mx-0">
            <iframe class="rounded-md shadow-md" height="200px" width="355px" src="https://www.youtube.com/embed/KFSfu66tlEQ?controls=0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
          <div class="max-w-xl mx-auto lg:mx-2">
            <h1 class="text-2xl font-bold text-blue-900">
              What is Punta?
            </h1>
            <p class="mt-3 text-justify text-blue-900">
              Punta is an online service platform that allows you to
              innovate, connect, and avail of services easily.
            </p>
            <p class="mt-3 text-justify text-blue-900">
              We aim to empower a customer-driven service community where
              people can avail of a variety of services to fulfill their needs, online or at-home.
            </p>
          </div>
        </div>
      </div>
      <div id="section-3" class="bg-white flex flex-col py-10 px-5">
        <div class="flex flex-row flex-wrap items-baseline justify-center
        lg:justify-between space-y-3 container mx-auto max-w-screen-lg">
          <div class="flex flex-col justify-center max-w-sm">
            <img :src="require('@/assets/svg/second-artifact-first.svg')" />
            <h3 class="text-xl text-gray-800 font-extrabold pb-4">
              Become a service provider
            </h3>
            <p class="font-light text-justify tracking-wide text-gray-800">
              Provide services of all kinds from graphic
              design and web development to home improvement and marketing.
            </p>
          </div>
          <div class="flex flex-col justify-center max-w-sm">
            <img :src="require('@/assets/svg/second-artifact-second.svg')" />
            <h3 class="text-xl text-gray-800 font-extrabold pb-4">
              Be a Punta ambassador
            </h3>
            <p class="font-light text-justify tracking-wide text-gray-800">
              Help our community grow by sharing Punta to
              every Filipino and by giving feedback on Punta’s latest technology!
            </p>
          </div>
        </div>
      </div>
      <div id="section-4" class="bg-punta text-white flex flex-col py-10">
        <div class="container lg:mx-auto max-w-screen-lg">
          <div class="flex flex-col text-center md:text-left mx-auto
          md:text-left pb-5 container justify-center inline-block">
              <h2 class="text-2xl tracking-wide text-center lg:text-left">
                What's in it for me?
              </h2>
              <p class="tracking-wide font-thin text-center lg:text-left">
                Here are some opportunities we’ll give to our service providers and ambassadors.
              </p>
          </div>
          <div class="flex flex-col justify-start">
            <div class="flex lg:flex-row flex-col flex-wrap sm:items-center md:items-baseline
              pb-6 space-y-5 md:space-x-0 md:justify-center lg:justify-between py-5 md:px-5 lg:px-0
              mx-auto lg:mx-0 space-y-4 lg:space-y-0">
              <div class="flex flex-col w-64">
                <img class="h-16 w-16 mb-4" :src="require('@/assets/svg/third-artifact-1.svg')" />
                <h3 class="font-semibold text-xl tracking-wide">
                  Grow your business
                </h3>
                <p class="font-light text-md text-justify">
                  Gain exposure, earn, and build your portfolio for free!
                </p>
              </div>
              <div class="flex flex-col w-64">
                <img class="h-16 w-16 mb-4" :src="require('@/assets/svg/third-artifact-2.svg')" />
                <h3 class="font-semibold text-xl tracking-wide">
                  Access our platform
                </h3>
                <p class="font-light text-md text-justify">
                  Sell your services and engage with customers easily.
                </p>
              </div>
              <div class="flex flex-col w-64">
                <img class="h-16 w-16 mb-4" :src="require('@/assets/svg/third-artifact-3.svg')" />
                <h3 class="font-semibold text-xl tracking-wide">
                  Get a discount from us <small>*</small>
                </h3>
                <p class="font-light text-md text-justify">
                  As a thank you from us, you have a 10% discount
                  or P50 off on your first purchase! **
                </p>
              </div>
            </div>
            <div class="flex flex-col text-asterisk
            font-light container mx-auto px-4 md:px-0 italic mt-5">
              <p class="text-sm text-center md:text-left">
                * Applicable for the first 50 service providers and first 50 ambassadors only!
              </p>
              <p class="text-sm text-center md:text-left">
                ** 10% discount for purchases below P500, and P50 off for services above P500.
              </p>
            </div>
          </div>
        </div>
      </div>
    </main>
    <Footerbar />
    <img id="blue-artifact" class="absolute hidden lg:block"
    :src="require('@/assets/svg/header-artifact-blue.svg')" />
    <img id="pink-artifact" class="absolute hidden lg:block"
    :src="require('@/assets/svg/header-artifact-pink.svg')" />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import Footerbar from '@/components/Footerbar.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Footerbar,
  },
  head: {
    title() {
      return {
        inner: 'Punta',
        separator: '|',
        complement: 'Beta Launching Soon',
      };
    },
    link: [
      {
        rel: 'icon',
        // eslint-disable-next-line global-require
        href: require('@/assets/img/punta-icon.png'),
        type: 'image/png',
      },
    ],
  },
};
</script>

<style>
@font-face {
font-family: "Gilroy";
src: url("./assets/fonts/gilroy-extrabold-webfont.woff") format("woff"),
url("./assets/fonts/gilroy-extrabold-webfont.woff2") format("woff2")
}
@font-face {
font-family: "Neufile";
src: url("./assets/fonts/neufilegrotesk-regular-webfont.woff") format("woff"),
url("./assets/fonts/neufilegrotesk-regular-webfont.woff2") format("woff2")
}
h1, h2, h4, h5 {
  font-family: "Gilroy";
}
html, body {
  min-height: 100vh;
  height: 100vh;
  font-family: "Neufile";
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
.text-asterisk {
  color: #EACBE0;
}
#blue-artifact {
  right: 1rem;
  bottom: 12rem;
}
#pink-artifact {
  left: 0.5rem;
  top: 8rem;
}
footer {
  background: #3F3D56;
}
.text-footer {
  color: #3F3D56;
}
</style>
