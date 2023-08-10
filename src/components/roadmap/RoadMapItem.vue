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
  <div class="roadmap-item-container text-start">
    <span class='roadmap-item-dot d-inline-block'>
      <oval-dot :fill="dot"></oval-dot>
    </span>

    <span class='roadmap-item-text d-inline-block'>{{ text }}</span>
    <span class='d-inline-block roadmap-item-value'>{{ value }}</span>
  </div>
</template>

<style scoped>
.roadmap-item-container {
  display: block;
  width: 10.9375rem;
  height: 1.4375rem;
  flex-shrink: 0;
}

.roadmap-item-dot {
  width: 1rem;
}

.roadmap-item-text {
  color: #647196;
  font-family: 'Jost', sans-serif;
  font-size: 1rem;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  width: 9rem;
}

.roadmap-item-value {
  color: #647196;
  text-align: right;
  font-family: 'Jost', sans-serif;
  font-size: 1rem;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
}
</style>
