<script setup lang="ts">
import '@fontsource/barlow/index.css';

useHead({
  title: 'Workspace',
  meta: [
    { name: 'description', content: 'No data.' }
  ],
  bodyAttrs: {
    class: 'test'
  },
})
</script>


<template>
  <div>
    <h1>Meoow!</h1>
  </div>
</template>

<style>
* {
  font-family: 'Barlow';
  padding: 0;
  margin: 0;
  --fontsource-display: optional;
}

h1 {
  font-weight: 700;
  padding: 2rem;
}
</style>
