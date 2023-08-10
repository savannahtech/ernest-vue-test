<script setup>
import RoadMapItem from '@/components/roadmap/RoadMapItem.vue'

defineProps({
  url: {
    type: String,
    default: '#'
  }
})
</script>

<template>
  <div class="roadmap">
    <div class="text-start roadmap-header">
      <p class="roadmap-title d-inline-block">Roadmap</p>

      <a :href="url" class="roadmap-view">View</a>
    </div>
    <div class="roadmap-items-container">
      <road-map-item value="2" text="Planned" dot="#F49F85"></road-map-item>
    </div>
  </div>
</template>

<style scoped>
.roadmap-title {
  color: #3a4374;
  width: 4.8rem;
  font-family: Jost, serif;
  font-size: 18px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
  letter-spacing: -0.25px;
}

.roadmap-view {
  color: #8397f8;
  margin-left: 4.19rem;
  font-family: Jost, serif;
  font-size: 13px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
  text-decoration-line: none;
}
.roadmap-view:hover {
  text-decoration-line: underline;
}

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
