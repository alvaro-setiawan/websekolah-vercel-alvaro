<script setup>
import ProductCard from '../components/ProductCard.vue'
 
const daftarProduk = [
  { id: 1, nama: 'Fitted Tee', harga: 75000, gambar: 
'https://th.bing.com/th/id/OIP.huUVoH6WY8knjbwZXe62RQHaHa?w=194&h=194&c=7&r=0&o=7&pid=1.7&rm=3'},
  { id: 2, nama: 'Aerostreet Boxy', harga: 99000, gambar: 
'https://th.bing.com/th/id/OIP.E6hlZVrLe5FhcP9991HReAHaHa?w=192&h=192&c=7&r=0&o=7&pid=1.7&rm=3' },
  { id: 3, nama: 'Screamous Regular fit', harga: 120000, gambar: 
'https://th.bing.com/th/id/OIP.B6c1SCc99FxBHrEKK1YdVgHaHa?w=177&h=180&c=7&r=0&o=7&pid=1.7&rm=3' },
]
</script>
 
<template>
  <main>
    <h1>Produk Kami</h1>
    <div class="grid">
      <ProductCard
        v-for="produk in daftarProduk"
        :key="produk.id"
        :nama="produk.nama"
        :harga="produk.harga"
        :gambar="produk.gambar"
      />
    </div>
  </main>
</template>
 
<style scoped>
.grid {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}
</style>
