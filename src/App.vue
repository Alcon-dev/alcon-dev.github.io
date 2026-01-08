<template>
  <div :class="$style.app">
    <Resume />
  </div>
</template>

<script>
import Resume from './components/Resume.vue'

export default {
  name: 'App',
  components: {
    Resume
  }
}
</script>

<style module lang="scss">
.app {
  min-height: 100vh;
  padding: 2.125rem 1rem;
  background: #f5f5f5;
}
</style>

