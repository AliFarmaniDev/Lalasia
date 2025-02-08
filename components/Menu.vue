<template>
  <nav class="hidden md:flex items-center gap-[2.5rem]">
    <NuxtLink to="/" class="text-black capitalize">product</NuxtLink>
    <NuxtLink to="/about" class="text-black capitalize">services</NuxtLink>
    <NuxtLink to="/contact" class="text-black capitalize">articel</NuxtLink>
    <NuxtLink to="/contact" class="text-black capitalize">about us</NuxtLink>
  </nav>
  <!--drop down button-->
 <div class="flex flex-col gap-1">
  <button @click="toggleMenu" class="md:hidden flex justify-center items-center">
    <img src="../assets/icons/menu.png" alt="dropdown menu">
  </button>
  <!--mobile menu-->
  <nav v-if="isMenuOpen" class="md:hidden mt-4 px-3 border rounded flex flex-col justify-end py-3">
    <NuxtLink to="/" class="block text-black capitalize">products</NuxtLink>
    <NuxtLink to="/about" class="block text-black capitalize">servicers</NuxtLink>
    <NuxtLink to="/contact" class="block text-black capitalize">article</NuxtLink>
    <NuxtLink to="/contact" class="block text-black capitalize">about us</NuxtLink>
  </nav>
 </div>
</template>

<script lang="ts" setup>
import { ref } from "vue";

const isMenuOpen = ref(false);

function toggleMenu() {
  isMenuOpen.value = !isMenuOpen.value;
}
</script>
