<script setup lang="ts">
import MainSlider from "@/components/sliders/MainSlider.vue"
const route = useRoute()
</script>

<template>
<section>
  <a-row>
    <a-col :span="8">
      <MainSlider/>
    </a-col>
    <a-col :span="16">
      test
    </a-col>
  </a-row>
</section>
</template>