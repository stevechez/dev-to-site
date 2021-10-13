<template>
  <div>
    <nav class="flex px-8 bg-gray-100 justify-between">
  <!-- left side -->
  <div class="flex items-center space-x-3">
    <a class="block p-3"><a href="/" class="site-logo" aria-label="DEV Community Home">
    <img src="../assets/dev-logo.png" class="mt-5 mb-5 h-12" />
</a></a>
    <div class="shadow flex w-96">
    <input class="w-full rounded p-2" type="text" placeholder="Search...">
    <button class="bg-white w-auto flex justify-end items-center text-gray-500 p-2 hover:text-blue-400 p-3">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
</svg>
    </button>
</div>
  </div>

  <!-- right side -->
  <div class="flex items-center space-x-3">
    <button class="py-2 px-4 hover:bg-gray-200 rounded">Login</button>
    <button class="border-1 bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Create Account</button>
  </div>
</nav>
  </div>
</template>

<script>
export default {
  setup () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>