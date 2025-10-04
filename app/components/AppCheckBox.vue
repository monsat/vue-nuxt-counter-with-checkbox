<script setup lang="ts">
const checked = defineModel<boolean>({
  default: false,
})
</script>

<template>
  <input
    v-model="checked"
    type="checkbox"
    @click="checked = !checked"
  />
</template>
