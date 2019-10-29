<template>
  <a-row>
    <a-col :span="12">
      <p>{{ id }}</p>
    </a-col>
  </a-row>
</template>

<script>
export default {
  asyncData({ route }) {
    return {
      id: route.params.id
    }
  }
}
</script>