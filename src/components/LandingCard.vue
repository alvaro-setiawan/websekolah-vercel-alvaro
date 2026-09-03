<!-- <script setup>
import PropotitionCard from '../components/PropotitionCard.vue'
const daftarPropotition = [
  {
    gambar: '🐱‍🏍',
    h1: 'Kualitas Terjamin',
    h2: 'Bahan langsung dari swiss'
  },
  {
    gambar: '🐱‍💻',
    h1: 'Harga Ramah Di Kantong',
    h2: 'Harga yang kompetitif tanpa mengorbankan kualitas'
  },
  {
    gambar: '🐱‍🐉',
    h1: 'Pengiriman Cepat',
    h2: 'Pengiriman cepat dan aman ke seluruh Indonesia'
  }
] </script>
<template>
<main>
  <div class="container">
    <PropotitionCard
      v-for="propotition in daftarPropotition"
      :key="propotition.id"
      :gambar="propotition.gambar"
      :h1="propotition.h1"
      :h2="propotition.h2"
    />  
  </div>
</main>
</template>
<style scoped>
  .container {
    display: flex;
    gap: 20px;
    place-content: center;
    flex-wrap: wrap;
  }
</style> -->
<template>
  <div class="container">
    <div class="card">
      <h1>Selamat Datang di Toko Kami</h1>
      <p>Temukan produk berkualitas dengan harga terbaik di sini!</p>
      <RouterLink to="/product" class="button">Lihat Produk</RouterLink>
    </div>
  </div>
</template>
<style scoped>
.container {
  display: grid;
  place-content: center;
}
.card {
  background-color: rgb(58, 58, 232);
  height: 200px;
  width: 100%;
  padding: 50px;
  overflow: hidden;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
.button {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: white;
  color: black;
  text-decoration: none;
  border-radius: 5px;
}
</style>
