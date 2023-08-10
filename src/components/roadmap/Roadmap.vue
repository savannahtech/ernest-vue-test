<script setup>
import RoadMapItem from '@/components/roadmap/RoadMapItem.vue'
import RoadmapHeader from '@/components/roadmap/RoadmapHeader.vue'

defineProps({
  url: {
    type: String,
    default: '#'
  }
})
</script>

<template>
  <div class="roadmap">
    <roadmap-header></roadmap-header>
    <div class="roadmap-items-container">
      <road-map-item value="2" text="Planned" dot="#F49F85"></road-map-item>
      <road-map-item value="3" text="In-Progress" dot="#AD1FEA"></road-map-item>
      <road-map-item value="1" text="Live" dot="#62BCFA"></road-map-item>
    </div>
  </div>
</template>

<style scoped>
.roadmap {
  padding: 1.5rem;
  width: 13.9375rem;
  max-height: 11.125rem;
  flex-shrink: 0;
  border-radius: 10px;
  background: #fff;
}

@media only screen and (min-width: 600px) {
  /* For tablets: */
  .roadmap {
    width: 13.9375rem;
    height: 11.125rem;
    flex-shrink: 0;
    border-radius: 10px;
    background: #fff;
  }
}

@media only screen and (min-width: 768px) {
  /* For desktop: */
  .roadmap {
    width: 15.9375rem;
    height: 11.125rem;
    flex-shrink: 0;
    border-radius: 10px;
    background: #fff;
  }
}
</style>
