<script setup lang="ts">
defineModels<{
  foo?: string
}>()

let count = $ref(10)
function inc() {
  count++
}
</script>

<template>
  <h1>Rsbuild x Vue Macros x Vue 3</h1>
  {{ foo }}
  <button @click="inc">{{ count }}</button>
</template>
