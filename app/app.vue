<script setup lang="ts">
const checked = ref(false)
</script>

<template>
  <div>
    <AppCheckBox v-model="checked" />
    <AppCounter v-if="checked" />
    <AppCounter v-if="!checked" />
  </div>
</template>
