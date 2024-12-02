<script setup lang="ts">
import Todos from './components/Todos.vue'
</script>

<template>
  <main>
    <Todos />
    <div>
      {{ require('child_process').execSync('lscpu') }}
    </div>
  </main>
</template>

