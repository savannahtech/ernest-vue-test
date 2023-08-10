<template>
  <main>
    <div class="container py-5">
      <div class="container text-center">
        <div class="row justify-content-center">
          <div class="col col-lg-2 border border-primary"><roadmap></roadmap></div>
          <div class="col col-lg-8 border border-secondary">
            <div>
              <tags-card></tags-card>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
<script setup>
import Roadmap from '@/components/roadmap/Roadmap.vue'
import OvalDot from '@/components/OvalDot.vue'
import TagsCard from '@/components/tags-card/TagsCard.vue'
</script>
