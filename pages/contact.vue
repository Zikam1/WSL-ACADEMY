
<template>
  <div class="min-h-screen bg-gray-100 flex items-center justify-center py-12 px-4 sm:px-6 lg:px-8">
    <div class="max-w-2xl w-full space-y-8 bg-white shadow-xl rounded-lg p-8 ring-1 ring-gray-900/5">
      <h2 class="text-center text-4xl font-extrabold text-gray-900">Contact Us</h2>
      <p class="text-center text-md text-gray-600 mb-6">
        We'd love to hear from you! Reach out through any of the following contact details.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Contact Numbers Card -->
        <div class="bg-white shadow-lg rounded-lg p-6 ring-1 ring-gray-900/5">
          <h3 class="text-lg font-semibold text-gray-900">Contact Numbers</h3>
          <div class="mt-4 space-y-4">
            <div class="flex items-center justify-between">
              
              <a href="tel:08166442613" class="text-blue-600  hover:underline">08166442613</a>
            </div>
            <div class="flex items-center justify-between">
            
              <a href="tel:08104233630" class="text-blue-600 hover:underline">08104233630</a>
            </div>
            <div class="flex items-center justify-between">
            
              <a href="tel:08134004266" class="text-blue-600 hover:underline">08134004266</a>
            </div>
          </div>
        </div>
        <!-- Contact Form Card -->
        <div class="bg-white shadow-lg rounded-lg p-6 ring-1 ring-gray-900/5">
          <h3 class="text-lg font-semibold text-gray-900">Send Us a Message</h3>
          <form class="mt-4 space-y-4">
            <div>
              <label for="name" class="block text-sm font-medium text-gray-700">Name</label>
              <input type="text" id="name" name="name" required class="mt-1 px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm">
            </div>
            <div>
              <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
              <input type="email" id="email" name="email" required class="mt-1 px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm">
            </div>
            <div>
              <label for="message" class="block text-sm font-medium text-gray-700">Message</label>
              <textarea id="message" name="message" rows="4" required class="mt-1 px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm"></textarea>
            </div>
            <div>
              <button type="submit" class="w-full flex justify-center py-2 px-4 border border-transparent text-sm font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-500">
                Send Message
              </button>
            </div>
          </form>
        </div>
      </div>
      <div class="mt-8 flex justify-center space-x-6">
        <a href="#" class="text-gray-500 hover:text-gray-600">
          <span class="sr-only">Facebook</span>
          <!-- Add Facebook Icon -->
        </a>
        <a href="#" class="text-gray-500 hover:text-gray-600">
          <span class="sr-only">Twitter</span>
          <!-- Add Twitter Icon -->
        </a>
        <a href="#" class="text-gray-500 hover:text-gray-600">
          <span class="sr-only">Instagram</span>
          <!-- Add Instagram Icon -->
        </a>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>

<style>
/* Add any additional custom styles here */
</style>
