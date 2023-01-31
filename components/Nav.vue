<template>
  <nav class="bg-woodsmoke p-6">
    <div class="container flex items-center justify-between flex-wrap mx-auto">
      <a href="" class="flex items-center flex-shrink-0 text-white mr-6">
        <img src="~/assets/images/getbrand_logo.svg" alt="GetBrand" />
      </a>
      <div class="block md:hidden flex-grow">
        <button
          @click="toggleNav"
          class="
            flex
            items-center
            px-3
            py-2
            border
            rounded
            text-pastelblue
            border-pastelblue
            hover:text-primary hover:border-primary
            transition
            duration-300
            ease-in-out
          "
        >
          <svg
            class="fill-current h-3 w-3"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>
      <div
        class="
          w-full
          md:w-auto md:flex md:items-center
          text-base
          transition
          duration-500
          ease-in-out
        "
        :class="[showNav ? 'block' : 'hidden']"
      >
        <a
          href="#responsive-header"
          class="block mt-4 md:inline-block md:mt-0 nav__link mr-8"
        >
          Why GetBrand?
        </a>
        <a
          href="#responsive-header"
          class="block mt-4 md:inline-block md:mt-0 nav__link mr-8"
        >
          Brand
        </a>
        <a
          href="#responsive-header"
          class="block mt-4 md:inline-block md:mt-0 nav__link mr-8"
        >
          Developers
        </a>
        <a
          href="#responsive-header"
          class="block mt-4 md:inline-block md:mt-0 nav__link mr-8"
        >
          Blog
        </a>
        <a
          href="#responsive-header"
          class="block mt-4 md:inline-block md:mt-0 nav__link mr-8"
        >
          Signin
        </a>
        <a
          href="#"
          class="
            inline-block
            bg-primary
            text-sm
            px-3
            py-2
            rounded
            text-white
            mt-4
            md:mt-0
            hover:shadow-lg hover:shadow-primary/20
          "
          >Get API Key</a
        >
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      showNav: false,
    };
  },
  methods: {
    toggleNav() {
      this.showNav = !this.showNav;
    },
  },
};
</script>

<style>
</style>