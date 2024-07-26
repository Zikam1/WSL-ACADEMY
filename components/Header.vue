<template>
  <header class="bg-blue-600 text-white p-4">
    <nav class="container mx-auto flex justify-between items-center">
      <NuxtLink to="/" class="text-2xl font-bold hover:text-gray-300">
        WSL ACADEMY
      </NuxtLink>
      <button @click="toggleMenu" class="md:hidden focus:outline-none">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
        </svg>
      </button>
      <ul :class="{'hidden': !isMenuOpen, 'flex': isMenuOpen}" class="flex-col md:flex md:flex-row md:space-x-4 space-y-2 md:space-y-0">
        <li><NuxtLink to="/" class="hover:text-gray-300">Home</NuxtLink></li>
        <li><NuxtLink to="/courses" class="hover:text-gray-300">Courses</NuxtLink></li>
        <li><NuxtLink to="/about" class="hover:text-gray-300">About</NuxtLink></li>
        <li><NuxtLink to="/register" class="hover:text-gray-300">Register</NuxtLink></li>
        <li><NuxtLink to="/contact" class="hover:text-gray-300">Contact</NuxtLink></li>
      </ul>
    </nav>
  </header>
</template>

<script setup>
import { ref } from 'vue'

const isMenuOpen = ref(false)

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value
}
</script>

<style scoped>
/* Add any additional custom styles here */
</style>
