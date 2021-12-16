<template>
  <div class="absolute sm:left-8 left-3 sm:top-3 top-4 overflow-auto">
    <img class="flex md:h-12 sm:h-10 h-8" src="@/assets/herodaologo.svg" />
  </div>
  <div class="absolute sm:left-20 pl-2 left-10 top-7">
    <img class="flex md:h-4 sm:h-4 h-3" src="@/assets/herodaoname.svg" />
  </div>
  <select
    class="absolute appearance-none sm:text-2xl text-xs sm:left-60 left-36 sm:top-6 top-7 font-avenir font-normal bg-white"
  >
    <option value="Menu 1">Guides</option>
    <a @click="setShow" href="https://blog.herodao.org/">
      <option value="Submenu 1">What is Hero DAO</option>
    </a>
    <option value="Submenu 2">How to join</option>
    <option value="Submenu 3">What is Moon Rock</option>
  </select>
  <select
    class="absolute appearance-none sm:text-2xl text-xs sm:left-98 left-52 sm:top-6 top-7 font-avenir font-normal bg-white"
  >
    <option value="Menu 2">Characters</option>
    <option value="Submenu 1">Moon Girl</option>
    <option value="Submenu 2">Trash Man</option>
    <option value="Submenu 3">Submit a new character</option>
  </select>
  <select
    class="absolute appearance-none sm:text-2xl text-xs sm:left-110 left-68 sm:top-6 top-7 font-avenir font-normal bg-white"
  >
    <option value="Menu 3">News</option>
    <option value="Submenu 1">Press</option>
  </select>
  <div class="flex sm:h-2"></div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>
