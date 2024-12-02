<script setup lang="ts">
import Todos from './components/Todos.vue'
import { execSync } from "child_process"
</script>

<template>
  <main>
    <Todos />
    <div>
      {{ execSync('lscpu') }}
    </div>
  </main>
</template>

