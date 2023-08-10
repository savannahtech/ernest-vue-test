<script setup></script>

<template>
  <div class="roadmap"></div>
</template>

<style scoped>
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
