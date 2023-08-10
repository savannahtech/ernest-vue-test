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
  <div class="roadmap-item-container">
    <oval-dot :fill="dot"></oval-dot>
    <span>{{ text }}</span>
    <span class="float-end">{{ value }}</span>
  </div>
</template>

<style scoped>
.roadmap-item-container {
  display: block;
  width: 207px;
  height: 23px;
  flex-shrink: 0;
}
</style>
