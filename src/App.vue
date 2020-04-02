<template>
    <div class="max-w-sm rounded overflow-hidden shadow-lg">
      <img class="w-full" src="./assets/profile.jpg" alt="Display" />
      <div class="px-6 py-4">
        <div class="font-bold text-purple-500 text-xl mb-2">
          Vue + Tailwind 템플릿
        </div>
        <p class="text-gray-700 text-base">
          Vue도 좋지만 tailwind까지 결합되니 정말 좋네요. <span></span>
        </p>
      </div>
      <div class="px-6 py-4">
        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#vue</span>
        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2">#@vue/cli</span>
        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mt-2 ml-20">#tailwind</span>
      </div>
    </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
