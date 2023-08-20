<template>
  <div class="relative flex items-top justify-center min-h-screen bg-gray-800 text-blue-400 sm:items-center sm:pt-0">
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet">
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <div class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        siemanko
      </div>
    </div>

    <NuxtLink to="/test">
      TO THE TEST PAGE
    </NuxtLink>
  </div>
</template>

<script>

export default {
  name: 'MainContent'
}
</script>
