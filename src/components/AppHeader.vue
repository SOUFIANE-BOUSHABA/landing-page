<template>
  <header class="bg-blue-500 p-4">
    <nav class="flex items-center justify-between">
      <div class="text-white text-2xl font-bold">
        <a href="#">Travel</a>
      </div>
      <ul class="flex space-x-4">
        <li><a class="text-white hover:text-gray-300" href="#">Home</a></li>
        <li><a class="text-white hover:text-gray-300" href="#">About</a></li>
        <li><a class="text-white hover:text-gray-300" href="#">Gallery</a></li>
        <li><a class="text-white hover:text-gray-300" href="#">Blog</a></li>
        <li><a class="text-white hover:text-gray-300" href="#">Contact</a></li>
      </ul>
      <div>
        <a href="#" class="text-white hover:text-gray-300">
          <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          </svg>
        </a>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
};
</script>

<style scoped lang="css">

</style>
