<template>
    <footer>
      <div id="footer-wrapper" class="flex flex-col py-16 container lg:mx-auto max-w-screen-lg">
        <div class="w-full h-full flex flex-row justify-between flex-wrap items-center">
          <div class="justify-center flex flex-row items-baseline px-3 lg:p-0
          md:space-y-0 lg:space-x-3 space-x-0 space-y-3 flex-wrap mx-auto lg:mx-0">
            <a href="https://forms.gle/isVYj2RKhy3LVEQF9" target="_blank"
            class="px-3 py-2 border-2 border-white tracking-wider
            text-white rounded-lg font-bold shadow-md">
              Become an Ambassador
            </a>
            <a href="https://forms.gle/AB8AEHY3CAfNMZ336" target="_blank"
            class="px-3 py-2 border-2 border-white tracking-wider
            bg-white text-footer rounded-lg font-bold shadow-md">
              Sign up for Beta
            </a>
          </div>
          <div class="mx-auto md:mx-0 flex flex-row
          justify-center items-baseline space-x-3 md:space-y-0 space-y-3 flex-wrap p-2">
            <a href="https://www.facebook.com/puntahq" target="_blank"
            class="rounded-full border-2 border-white h-10 w-10">
              <img class="h-7 w-7 p-2"
              :src="require('@/assets/svg/social-fb.svg')" />
            </a>
            <a href="https://www.twitter.com/puntahq" target="_blank"
            class="rounded-full border-2 border-white h-10 w-10">
              <img class="h-7 w-7 p-2"
              :src="require('@/assets/svg/social-tw.svg')" />
            </a>
            <a href="https://www.instagram.com/puntahq" target="_blank"
            class="rounded-full border-2 border-white h-10 w-10">
              <img class="h-7 w-7 p-2"
              :src="require('@/assets/svg/social-ins.svg')" />
            </a>
          </div>
        </div>
        <div class="flex lg:flex-row mx-auto lg:mx-0 flex-col lg:space-y-0
        lg:justify-between text-gray-500 pt-5 flex-wrap space-y-2">
          <p class="text-xs max-w-sm text-center lg:text-left">
            &#169; Punta Online Solutions 2020
          </p>
          <div class="hidden flex flex-row space-x-2 mx-auto lg:mx-0 text-center lg:text-left">
            <a class="text-xs">
              Privacy Policy
            </a>
            <a class="text-xs">
              Terms and Conditions
            </a>
          </div>
        </div>
      </div>
    </footer>
</template>

<script>
export default {
  name: 'Footerbar',
};
</script>
