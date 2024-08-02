<script setup>
</script>

<template>
<!-- HTML -->
<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded" id="openModal">Open Modal</button>

<div id="modal" class="hidden fixed inset-0 flex items-center justify-center bg-gray-800 bg-opacity-50">
  <div class="bg-white p-6 rounded">
    <h2 class="text-xl font-bold mb-4">Modal Title</h2>
    <p class="mb-4">This is the modal content.</p>
    <button class="bg-red-500 hover:bg-red-700 text-white font-bold py-2 px-4 rounded" id="closeModal">Close Modal</button>
  </div>
</div>

</template>

<style scoped></style>
