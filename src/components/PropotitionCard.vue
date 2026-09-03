<script setup>
defineProps(['gambar', 'h2', 'h3'])
</script>
<template>
  <div class="card">
    <div class="icon">
      <p>{{ gambar }}</p>
    </div>
    <h2>{{ h2 }}</h2>
    <h3>{{ h3 }}</h3>
  </div>
</template>
<style scoped>
.card {
  font-family: 'Segoe UI', sans-serif;
  background-color: white;
  color: black;
  width: 200px;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  border: 1px solid black;
  margin: 15px;
  padding: 24px;
  text-align: center;
  transition: transform 0.2s ease, box-shadow 0,2s ease;
}
.card-hover {
  transform: translateY(-5px);
}
.icon {
  font-size: 2rem;
  margin-bottom: 3px;
  height: auto;
}
</style>
