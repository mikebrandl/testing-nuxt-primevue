<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    <p>Current route: {{ route.path }}</p>
    <Button as="router-link" label="Home" icon="pi pi-check" to="/" />

  </div>
</template>
