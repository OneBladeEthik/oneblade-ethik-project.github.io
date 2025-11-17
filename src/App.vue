<template>
  <OneBlade />
</template>

<script>
import OneBlade from './views/OneBlade.vue'

export default {
  name: 'App',
  components: {
    OneBlade
  }
}
</script>

<style>
/* Optional: global styles if needed */
body {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  background-color: #1e1e2f;
}
</style>
