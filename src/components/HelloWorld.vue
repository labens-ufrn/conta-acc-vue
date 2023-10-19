<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})
</script>

<template>
  <h1>{{ msg }}</h1>
  <p>Sistema de Gestão de Atividades Complementares</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
