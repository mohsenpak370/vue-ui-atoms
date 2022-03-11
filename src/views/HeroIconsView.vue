<script setup lang="ts">
import { defineAsyncComponent } from 'vue'

const HeroIcons = defineAsyncComponent(() =>
  import('@/components/heroIcons/HeroIcons.vue')
)
</script>

<template>
  <HeroIcons />
</template>