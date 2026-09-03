<script setup>
defineProps(['gambar', 'h1', 'h2'])
</script>
<template>
  <div class="card">
    <div class="icon">
      <p>{{ gambar }}</p>
    </div>
    <h1>{{ h1 }}</h1>
    <h2>{{ h2 }}</h2>
  </div>
</template>
<style scoped>
.card {
  font-family: 'Segoe UI', sans-serif;
  color: black;
  width: 200px;
  height: 200px;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  border: 1px solid black;
  margin: 15px;
  padding: 24px;
}
.card-hover {
  transform: translateY(-3px);
}
.icon {
  font-size: 1rem;
  margin-bottom: 5px;
  height: auto;
}
</style>
