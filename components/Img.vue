<script setup>
// Resolves public/ assets correctly under GitHub Pages --base subpath.
defineProps({ src: { type: String, required: true }, alt: { type: String, default: '' } })
const base = import.meta.env.BASE_URL
</script>
<template>
  <img :src="base + src" :alt="alt" />
</template>
