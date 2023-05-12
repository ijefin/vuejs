<script setup>
defineProps({
  msg: String,
});
</script>

<template>
  <h1>{{ msg }}</h1>

  <button @click="msg = 'Olá mundo'">Clica ae</button>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
