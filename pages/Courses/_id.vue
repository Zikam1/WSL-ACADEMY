<script setup>
const route = useRoute();
const courseId = route.params.id;
</script>

<template>
  <div class="container mx-auto p-4">
    <h1 class="text-2xl font-bold mb-4">Course Title {{ courseId }}</h1>
    <p class="text-lg mb-4">Detailed description of the course.</p>
    <button class="bg-blue-500 text-white py-2 px-4 rounded">Enroll Now</button>
  </div>
</template>
