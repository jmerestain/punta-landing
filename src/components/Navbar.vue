<template>
    <div id="navbar"
    class="pt-1 flex flex-row justify-between px-4 shadow items-center">
        <img class="my-auto p-3"
        :src="require('@/assets/svg/header-logo.svg')" />
        <div class="flex flex-row items-center gap-2 mb-1 md:mb-0 lg:mb-0 hidden md:flex lg:flex">
            <a href="https://forms.gle/isVYj2RKhy3LVEQF9" target="_blank"
            class="border-2 text-center border-punta
            text-punta font-medium rounded-lg px-3 py-1">
                Become an Ambassador
            </a>
            <a href="https://forms.gle/AB8AEHY3CAfNMZ336" target="_blank"
            class="border-2 text-center bg-punta
            border-punta font-medium text-white rounded-lg px-3 py-1">
                Sign up for Beta
            </a>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>
