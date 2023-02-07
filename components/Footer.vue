<template>
  <footer class="bg-woodsmoke py-16 text-pastelblue">
    <div class="container flex flex-col items-center mx-auto gap-6">
      <img
        class="w-24"
        src="~/assets/images/getbrand_logo.svg"
        alt="GetBrand"
      />
      <div class="flex gap-6">
        <div class="flex flex-col md:flex-row gap-6">
          <a href="#potential" class="nav__link">Potential</a>
          <a href="#personalization" class="nav__link">Personalization</a>
          <a href="user-experience" class="nav__link">User Experience</a>
          <a href="#engagement" class="nav__link">Engagement</a>
        </div>
      </div>
      <p class="text-sm opacity-70">
        © 2023
        <a
          target="_black"
          href="https://acornglobus.com/"
          class="nav__link"
        >
          Acorn Globus
        </a>
        from the makers of
        <a
          target="_black"
          href="https://formester.com/"
          class="nav__link text-indigo-400"
          >Formester</a
        >
      </p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>
