<script setup lang="ts">
defineProps<{
  logo: string
}>()
</script>

<template>
  <div class="bg-gray-600 rounded-xl max-w-[1440px] mx-auto px-10 py-7">
    <span class="text-2xl text-white">{{ logo }}</span>

  </div>
</template>
