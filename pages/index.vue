
   <template>
    <div class="bg-gray-100 min-h-screen">
      <!-- Hero Section -->
      <section class="bg-blue-500 text-white py-20">
        <div class="container mx-auto px-6 text-center">
          <h2 class="text-3xl font-semibold">Start Learning Today!</h2>
      <p class="mt-4 text-lg">Explore our wide range of tech courses to enhance your skills.</p>
          <!-- <NuxtLink to="/dashboard" class="bg-white text-blue-500 mt-24 py-2 px-4 rounded-full font-bold hover:bg-gray-200">Get Started</NuxtLink> -->
        </div>
      </section>
    
      <!-- Features Section -->
      <section class="container mx-auto px-6 py-20">
        <h2 class="text-4xl font-bold text-center mb-12">Features</h2>
        <div class="flex flex-wrap -mx-3">
          <div class="w-full md:w-1/3 px-3 mb-6">
            <div class="bg-white rounded-lg shadow-lg p-6">
              <h3 class="text-2xl font-bold mb-4">Easy to Use</h3>
              <p>Our intuitive interface makes tracking your expenses a breeze.</p>
            </div>
          </div>
          <div class="w-full md:w-1/3 px-3 mb-6">
            <div class="bg-white rounded-lg shadow-lg p-6">
              <h3 class="text-2xl font-bold mb-4">Secure</h3>
              <p>Your data is safe with us, protected by industry-leading security measures.</p>
            </div>
          </div>
          <div class="w-full md:w-1/3 px-3 mb-6">
            <div class="bg-white rounded-lg shadow-lg p-6">
              <h3 class="text-2xl font-bold mb-4">Detailed Reports</h3>
              <p>Generate detailed reports to analyze your spending habits and manage your finances better.</p>
            </div>
          </div>
        </div>
      </section>
  
      <!-- Call to Action Section -->
      <section class="bg-blue-500 text-white py-20">
        <div class="container mx-auto px-6 text-center">
          <h2 class="text-4xl font-bold mb-6">Ready to start tracking your expenses?</h2>
          <NuxtLink to="/dashboard" class="bg-white text-blue-500 py-2 px-4 rounded-full font-bold hover:bg-gray-200">Get Started Now</NuxtLink>
        </div>
      </section>

      <div>
    <section class="bg-blue-800 text-white text-center py-16">
      <h2 class="text-3xl font-semibold">Start Learning Today!</h2>
      <p class="mt-2 text-lg">Explore our wide range of tech courses to enhance your skills.</p>
    </section>
  </div>

    <section class="container mx-auto p-4">
      <h2 class="text-2xl font-bold mb-4">Featured Courses</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
        <CourseCard id="1" title="Course 1" description="Brief description of Course 1" />
        <CourseCard id="2" title="Course 2" description="Brief description of Course 2" />
        <CourseCard id="3" title="Course 3" description="Brief description of Course 3" />
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
  