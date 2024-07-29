<script setup lang="ts">
import Logo from "@/assets/Logo.vue";
</script>

<template>
  <nav
    class="flex justify-between items-center px-[100px] py-10 border-b-2 border-gray-100"
  >
    <Logo />
    <ul
      class="menu text-xl flex items-center gap-16 transition-all duration-300"
    >
      <a href="#" class="menu-link cursor-pointer font-semibold">Home</a>
      <a href="#" class="menu-link cursor-pointer opacity-50 hover:opacity-100"
        >Search</a
      >
      <a href="#" class="menu-link cursor-pointer opacity-50 hover:opacity-100"
        >Blog</a
      >
      <a href="#" class="menu-link cursor-pointer opacity-50 hover:opacity-100"
        >About</a
      >
    </ul>
    <ul class="act-button flex items-center gap-5">
      <a
        href="#"
        class="button-outline text-lg font-semibold px-6 py-3 border-gray-100 border-2 rounded-full"
        >Sign In</a
      >

      <a
        href="#"
        class="button-filled bg-black text-white py-3 px-6 rounded-full text-lg"
        >Register</a
      >
    </ul>
  </nav>
</template>
