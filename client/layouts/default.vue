<template>
  <a-layout hasSider>
    <default-sider />
    <a-layout>
      <default-header />
      <nuxt />
    </a-layout>
  </a-layout>
</template>

<script>
import DefaultHeader from '@/components/layout/DefaultHeader.vue'
import DefaultSider from '@/components/layout/DefaultSider.vue'

export default {
  components: {
    DefaultHeader,
    DefaultSider
  }
}
</script>