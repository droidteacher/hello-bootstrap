<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="container">
    <button type="button" class="btn btn-success">Success</button>
    <button type="button" class="btn btn-info">Info</button>
    <button type="button" class="btn btn-warning">Warning</button>
  </div>
</template>

<style scoped>

</style>
