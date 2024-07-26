
   <template>
    <div class="bg-gray-100 min-h-screen">
      <!-- Hero Section -->
      <section class="bg-yellow-400 text-white py-20">
        <div class="container mx-auto px-6 text-center">
          <h2 class="text-3xl font-semibold">Start Learning Today!</h2>
      <p class="mt-4 text-lg">Explore our wide range of tech courses to enhance your skills.</p>
          <!-- <NuxtLink to="/dashboard" class="bg-white text-blue-500 mt-24 py-2 px-4 rounded-full font-bold hover:bg-gray-200">Get Started</NuxtLink> -->
         
        </div>
      </section>
    
      <!-- Features Section -->
      <section class="container mx-auto px-6 py-20">
        <h2 class="text-4xl font-bold text-center mb-12">Courses</h2>
        <div class="flex flex-wrap -mx-4">
          <div class="w-full md:w-1/3 px-3 mb-4">
            <div class="bg-white rounded-lg shadow-lg p-6">
              <img src="/assets/wsl.jpg" alt="Hero Image" class="w-5/6 h-auto mx-auto mt-8 object-cover" />
            </div>
          </div>

          <div class="w-full md:w-1/3 px-3 mb-6">
            <div class="bg-white rounded-lg shadow-lg p-6">
              <!-- <h3 class="text-2xl font-bold mb-4">TECHNOLOGY</h3> -->
              <img src="/assets/es.jpg" alt="Hero Image" class="w-3/4 h-auto mx-auto mt-8 object-cover" />
            </div>
          </div>
          <div class="w-full md:w-1/3 px-3 mb-6">
            <div class="bg-white rounded-lg shadow-lg p-6">
              <!-- <h3 class="text-2xl font-bold mb-4">Detailed Reports</h3> -->
              <img src="/assets/er.jpg" alt="Hero Image" class="w-3/4 h-auto mx-auto mt-8 object-cover" />
            </div>
          </div>
        </div>
      </section>
  
      <!-- Call to Action Section -->
      <div>
    <section class="bg-blue-800 text-white text-center py-16">
      <h2 class="text-2xl font-semibold">Certainly! How about this:</h2>
      <p class=" mt-2 text-lg mb-8">"Discover our diverse selection of tech courses designed to elevate your skills and ignite your passion for technology.".</p>
      <NuxtLink to="/Courses" class="bg-white text-blue-500 py-2 px-4 rounded-full font-bold hover:bg-gray-200">Get Started</NuxtLink>
    </section>
  </div>

    <section class="container mt-8 mx-auto p-4">
      <h2 class="text-2xl font-bold mb-8 text-center ">Technology Impacts'</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
        <CourseCard id="1" title="Improved Communication" description="Faster and more efficient exchanges through advanced technology." />
        <CourseCard id="2" title="AI Changing The Way We Work" description="We work by automating tasks and enhancing productivity." />
        <CourseCard id="3" title="Better Information Access" description="Improved and easier ways to find, retrieve, and use information through technology." />
      </div>
    </section>
    </div>
  </template>
  
  <script setup>
  // No additional scripts needed here for now.
  </script>
  
  <style scoped>
  /* Add custom styles here if needed */
  </style>
  