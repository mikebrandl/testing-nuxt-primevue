<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    <h1>Nuxt Routing set up successfully!</h1>
    <p>Current route: {{ route.path }}</p>
    <a href="https://nuxt.com/docs/getting-started/routing" target="_blank">Learn more about Nuxt Routing</a>
<br />
    <Button as="router-link" label="Test Page" to="/test" class="mt-5" />
    <br />
    <Button as="router-link" label="Test Page" to="/test" class="mt-5" />
  </div>
</template>
