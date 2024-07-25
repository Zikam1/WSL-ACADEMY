<template>
    <header class="bg-blue-600 text-white p-4">
      <nav class="container mx-auto flex justify-between items-center">
        <h1 class="text-2xl font-bold">WSL ACADEMY</h1>
        <ul class="flex space-x-4">
          <li><NuxtLink to="/" class="hover:text-gray-300">Home</NuxtLink></li>
          <li><NuxtLink to="/courses" class="hover:text-gray-300">Courses</NuxtLink></li>
          <li><NuxtLink to="/about" class="hover:text-gray-300">About</NuxtLink></li>
          <li><NuxtLink to="/contact" class="hover:text-gray-300">Contact</NuxtLink></li>
          <li><NuxtLink to="/login" class="hover:text-gray-300">Login</NuxtLink></li>
          <li><NuxtLink to="/register" class="hover:text-gray-300">Register</NuxtLink></li>
        </ul>
      </nav>
    </header>
  </template>
  