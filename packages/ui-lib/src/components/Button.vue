<script setup>
import { defineProps } from 'vue';

defineProps({
  label: {
    type: String,
    required: true
  }
});
</script>

<template>
  <button class="button">{{ label }}</button>
</template>

<style scoped>
</style>