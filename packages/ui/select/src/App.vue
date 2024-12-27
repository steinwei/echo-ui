<template>
  <div>
    <button @click="onClick">Click me</button>
  </div>
</template>

<script setup lang="ts">
function onClick() {
  console.log('clicked');
}
</script>