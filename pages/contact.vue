<template>
    <div class="container mx-auto p-4">
      <h1 class="text-2xl font-bold mb-4">Contact Us</h1>
      <form class="space-y-4">
        <div>
          <label class="block text-gray-700">Name</label>
          <input type="text" class="w-full p-2 border rounded" />
        </div>
        <div>
          <label class="block text-gray-700">Email</label>
          <input type="email" class="w-full p-2 border rounded" />
        </div>
        <div>
          <label class="block text-gray-700">Message</label>
          <textarea class="w-full p-2 border rounded" rows="4"></textarea>
        </div>
        <button type="submit" class="bg-blue-500 text-white py-2 px-4 rounded">Send</button>
      </form>
    </div>
  </template>
  