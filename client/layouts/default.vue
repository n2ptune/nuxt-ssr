<template>
  <a-layout>
    <default-header />
    <nuxt />
  </a-layout>
</template>

<script>
import DefaultHeader from '@/components/layout/DefaultHeader.vue'

export default {
  components: {
    DefaultHeader
  }
}
</script>