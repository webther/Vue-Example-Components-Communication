<template>
  <div class="app-header">
    Counter: {{ total }}
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  props: {
    'total': {
      type: Number,
      required: true
    }
  }
};
</script>

<style scoped>
.app-header {
  background: lightblue;
  padding: 5px;
  margin-bottom: 15px;
}
</style>
