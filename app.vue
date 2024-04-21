<script setup lang="ts">
const { isDarkMode } = useDarkMode();
</script>

<template>
  <div :style="isDarkMode ? { backgroundColor: '#2a3857' } : null">
    <Nav />
    <Heading />
    <Cards />
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  font-family: Georgia;
}
</style>
