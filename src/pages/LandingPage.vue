<script setup>
import LandingCard from '../components/LandingCard.vue'
import PropotitionCard from '../components/PropotitionCard.vue'
const daftarPropotition = [
  {
    gambar: '🐱‍🏍',
    h2: 'Kualitas Terjamin',
    h3: 'Bahan langsung dari swiss',
  },
  {
    gambar: '🐱‍💻',
    h2: 'Harga Ramah Di Kantong',
    h3: 'Harga yang kompetitif tanpa mengorbankan kualitas',
  },
  {
    gambar: '🐱‍🐉',
    h2: 'Pengiriman Cepat',
    h3: 'Pengiriman cepat dan aman ke seluruh Indonesia',
  },
]
</script>
<template>
  <main>
    <LandingCard />
    <div class="container">
      <PropotitionCard
        v-for="propotition in daftarPropotition"
        :key="propotition.id"
        :gambar="propotition.gambar"
        :h2="propotition.h2"
        :h3="propotition.h3"
      />
    </div>
  </main>
</template>
<style scoped>
.container {
  display: flex;
  gap: 15px;
  place-content: center;
}
</style>
<!-- <template>
    <main>
      <div class="hero bg-indigo-500 p-[100px] flex flex col items-center"></div>
    </main>
  </template> -->
