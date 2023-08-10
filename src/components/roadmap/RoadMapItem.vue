<script setup>
import OvalDot from '@/components/OvalDot.vue'

defineProps({
  dot: {
    type: String,
    required: true
  },
  text: {
    type: String,
    required: true
  },
  value: {
    type: Number,
    required: true
  }
})
</script>

<template>
  <div>
    <oval-dot :fill="dot"></oval-dot>
    <div>{{ text }}</div>
    <span>{{ value }}</span>
  </div>
</template>

<style scoped></style>
