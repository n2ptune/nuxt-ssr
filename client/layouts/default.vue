<template>
  <a-layout hasSider>
    <default-header />
    <a-layout>
      <nuxt />
    </a-layout>
  </a-layout>
</template>

<script>
import DefaultHeader from '@/components/layout/DefaultHeader.vue'

export default {
  components: {
    DefaultHeader,
  }
}
</script>