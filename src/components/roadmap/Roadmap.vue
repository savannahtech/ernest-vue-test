<script setup></script>

<template>
  <div class="roadmap">
    <div class="roadmap-header">
      <div class="roadmap-title">Roadmap</div>
      <a href="#" class="roadmap-view">View</a>
    </div>
  </div>
</template>

<style scoped>
.roadmap-title {
  color: #3a4374;
  font-family: Jost, serif;
  font-size: 18px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
  letter-spacing: -0.25px;
}

.roadmap-view {
  color: #8397f8;
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
  width: 223px;
  height: 178px;
  flex-shrink: 0;
  border-radius: 10px;
  background: #fff;
}

@media only screen and (min-width: 600px) {
  /* For tablets: */
  .roadmap {
    width: 223px;
    height: 178px;
    flex-shrink: 0;
    border-radius: 10px;
    background: #fff;
  }
}

@media only screen and (min-width: 768px) {
  /* For desktop: */
  .roadmap {
    width: 255px;
    height: 178px;
    flex-shrink: 0;
    border-radius: 10px;
    background: #fff;
  }
}
</style>
