<script setup>
defineProps({
  title: {
    type: String,
    default: 'Roadmap'
  },
  url: {
    type: String,
    default: '#',

  },
  urlText: {
    type: String,
    default: 'View'
  }
})
</script>

<template>
  <div class="text-start roadmap-header">
    <p class="roadmap-title d-inline-block">{{ title }}</p>

    <a :href="url" class="roadmap-view">{{ urlText }}</a>
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
</style>