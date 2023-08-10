<template>
  <main>
    <div class="container py-5">
      <div class="container text-center">
        <div class="row justify-content-center">
          <div class="col col-lg-2 border border-primary">Column</div>
          <div class="col col-lg-8 border border-secondary">
            <div>
              <oval-dot fill="#AAA"></oval-dot>
              <roadmap></roadmap>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
<script setup>
import Roadmap from '@/components/Roadmap.vue'
import OvalDot from '@/components/OvalDot.vue'
</script>
