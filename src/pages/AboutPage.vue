<script setup>

import TeamCard from '../components/TeamCard.vue'
</script>
<template>
  <main>
    <div class="container">
      <h1>Tentang Kami</h1>
    </div>
    <TeamCard />
  </main>
</template>
<style scoped>
/* <section>
<section class="tim kami">
  <h1>tim kami</h1>
  <div class="tim-grid">
    <TeamCard
    v-for="anggota in daftarTim"
    :key="anggota.id"
    :nama="anggota.nama"
    :jabatan="anggota.jabatan"
    />
    </div>
    </section> */
.container {
  background-color: rgb(58, 58, 232);
  color: white;
  width: 100%;
  height: 100px;
  display: flex;
  box-shadow:inset 0 0 10px #000000;
  overflow: hidden;
  margin: 10px;
  text-align: center;
}
</style>