<template>
    <div class="container mx-auto p-4 max-w-md">
      <h1 class="text-2xl font-bold mb-4">Register</h1>
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
          <label class="block text-gray-700">Password</label>
          <input type="password" class="w-full p-2 border rounded" />
        </div>
        <button type="submit" class="bg-blue-500 text-white py-2 px-4 rounded">Register</button>
      </form>
    </div>
  </template>
  