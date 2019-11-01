<template>
  <a-layout-content
    :style="{ padding: '25px' }"
  >
    <div class="content-header typo-text-500">
      Nuxt + Firebase + Ant Design Vue
    </div>
  </a-layout-content>
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
  .content-header {
    text-align: center;
  }
</style>