<script setup>
defineProps(['gambar', 'h1', 'h2'])
</script>
<template>
    <div class="kolom">
    <div class="text">
        <h1 style="color:">Cerita kami</h1>
        <p>Selamat datang di Alvaro Company! Kami menghadirkan berbagai produk pilihan terbaik dengan kualitas 
            terjamin dan harga bersahabat. Temukan kebutuhanmu di sini dan nikmati pengalaman berbelanja online 
            yang mudah, aman, dan menyenangkan.</p>
        <p>semoga semoga</p>
    </div>
    <div class="gambar">
        <img src="/gambar/alvaroCompany.jpg">
    </div>
</div>
</template>

<style scoped>
.kolom{
    display:flex;
    align-items:flex-start;
    margin:50px;
    flex:1;
    flex-direction:row;
    overflow:hidden;
}
.gambar img{
    width:300px;
    height:auto;
    border-radius:10px;
}
.text{
    flex:1;
}
text h1{
    font-size:2rem;
    margin-bottom:10px;
}
text p{
    font-size:1rem;
    margin-bottom:5px;
}
</style>