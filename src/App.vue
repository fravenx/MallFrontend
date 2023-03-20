<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import Layout from './layout/Layout.vue'

export default {
  name: 'app',
  components: {
    Layout
  },
  data() {
    return {
      filesUploadUrl: '127.0.0.1:8081'
    }
  }
}
</script>

<style>
</style>
