<script setup>
</script>

<template>
  <div class="bg-gray-200">
    <div class="flex">
      <div class="w-1/4 bg-gray-300">
        <!-- Left panel for settings -->
        <div class="p-4">
          <h2 class="text-xl font-bold">Settings</h2>
          <!-- Add your settings components here -->
        </div>
      </div>
      <div class="w-2/4">
        <!-- Central panel for app output -->
        <div class="p-4">
          <h2 class="text-xl font-bold">App Output</h2>
          <!-- Add your app output components here -->
        </div>
      </div>
      <div class="w-1/4 bg-gray-300">
        <!-- Foot panel for prompting -->
        <div class="p-4">
          <h2 class="text-xl font-bold">Prompting</h2>
          <!-- Add your prompting components here -->
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
