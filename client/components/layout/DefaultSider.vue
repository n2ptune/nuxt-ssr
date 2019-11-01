<template>
  <a-layout-sider>
    <a-menu
      mode="inline"
      :style="{ height: '100vh', width: '200px' }"
    >
      <a-sub-menu key="title1">
        <span slot="title">
          <a-icon type="user"></a-icon>
          title
        </span>
        <a-menu-item key="1">ascf</a-menu-item>
        <a-menu-item key="2">ascd</a-menu-item>
        <a-menu-item key="3">ascb</a-menu-item>
      </a-sub-menu>
      <a-sub-menu key="title2">
        <span slot="title">
          <a-icon type="man"></a-icon>
          title
        </span>
        <a-menu-item key="1">ascf</a-menu-item>
        <a-menu-item key="2">ascd</a-menu-item>
        <a-menu-item key="3">ascb</a-menu-item>
      </a-sub-menu>
    </a-menu>
  </a-layout-sider>
</template>

<script>
export default {
  data () {
    return {
      collapse: false
    }
  }
}
</script>