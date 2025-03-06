<script lang="ts" setup>
import { ref } from 'vue'

const value = ref('component')
</script>

<template>
  <div class="container">{{ value }}</div>
</template>

<style scoped></style>
