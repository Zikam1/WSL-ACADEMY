<template>
    <div class="bg-white p-4 rounded-lg shadow-md">
      <h3 class="text-xl font-semibold">{{ title }}</h3>
      <p class="mt-2">{{ description }}</p>
      <NuxtLink :to="`/courses/${id}`" class="text-blue-500 hover:underline mt-4 block">Learn More</NuxtLink>
    </div>
  </template>
  
  <script setup>
  defineProps(['id', 'title', 'description'])
  </script>
  