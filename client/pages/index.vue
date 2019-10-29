<template>
  <a-layout>
    <a-layout-content>
      <a-breadcrumb :style="{ margin: '16px 25px' }">
        <a-breadcrumb-item>Home</a-breadcrumb-item>
        <a-breadcrumb-item>List</a-breadcrumb-item>
        <a-breadcrumb-item>App</a-breadcrumb-item>
      </a-breadcrumb>
      <a-layout :style="{ margin: '10px 30px', backgroundColor: '#fff' }" hasSider="true">
        <default-sider></default-sider>
        <a-layout-content :style="{ padding: '24px 24px', minHeight: '280px' }">
          Content
        </a-layout-content>
      </a-layout>
    </a-layout-content>
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