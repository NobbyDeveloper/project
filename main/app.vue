<script setup lang="ts">
import '@fontsource/barlow';

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
    <p>Hola mundo</p>
  </div>
</template>

<style>
* {
  font-family: 'Barlow';
  padding: 0;
  margin: 0;
  --fontsource-display: optional;
}
</style>
