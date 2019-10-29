<template>
  <a-layout>
    <a-row>
      <a-layout-content class="content">
        Content
      </a-layout-content>
    </a-row>
  </a-layout>
</template>

<script>
import DefaultSider from '@/components/layout/DefaultSider.vue'

export default {
  components: {
    DefaultSider
  }
}
</script>

<style scoped>
.content {
  margin: 25px;
  min-height: 100vh;
}
</style>