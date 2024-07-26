<template>
    <div class="bg-white p-6 rounded-lg shadow-md max-w-4xl mx-auto">
      <h1 class="text-2xl font-bold">{{ course.title }}</h1>
      <p class="mt-4">{{ course.description }}</p>
      <!-- Add more content here as needed -->
    </div>
  </template>
  
  <script setup>
  import { ref, onMounted } from 'vue'
  import { useRoute } from 'vue-router'
  
  const route = useRoute()
  const course = ref({ title: '', description: '' })
  
  // Fetch course data based on the ID from the route
  onMounted(async () => {
    const id = route.params.id
    // Fetch course details from an API or store
    // Here is a mock example
    const response = await fetch(`/api/courses/${id}`)
    course.value = await response.json()
  })
  </script>
  
  <style scoped>
  /* Add any additional styling here */
  </style>
  