<script setup>
import ProductCard from '../components/ProductCard.vue'
const daftarProduk = [
 { id: 1, nama: 'Bola futsal specs', harga: 300000, gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYHY11AQwxU9ArumSSA_yz3OvI8yS7FFWMhhiI3P2Fsw&s' },
 { id: 2, nama: 'Bola futsal specs', harga: 450000, gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdI9Tjp8JSoNYWYkU5kTb2MSXRg9sNRKQsmRKYmoAETg&s=10' },
 { id: 3, nama: 'Bola futsal specs', harga: 550000, gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3I0TwgAxFS_PoT5MytBwf1m5E4LmE7_ukQE2ZZw-qmA&s=10' },
{ id: 4, nama: 'Bola futsal specs', harga: 650000, gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkiBOTCDHb3eT5DEQm2BAUvtWvx2y00E4kk_Utg1U-uA&s=10' },
{ id: 5, nama: 'Sepatu futsal specs', harga: 750000 , gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQa33rmcq7RbOFWwcabj-iecy7p9MDQk1jHYyqT6hePGQ&s=10' },
{ id: 6, nama: 'Sepatu futsal specs', harga: 850000, gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-fSTx-IQyLYaD22bVsxxhV34BYHdsbALaigDaYIAglQ&s=10' },
{ id: 7, nama: 'Sepatu futsal specs', harga: 950000, gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQvu-5bw0AuzW0yg9s8iyBKqDWbYKW1FyGeJjvat5SqBg&s=10' },
{ id: 8, nama: 'Sepatu futsal specs', harga: 1050000, gambar:
'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8w_oGrpDdFmyUow2gDElhC1gwtPLhqChTJE9Ab1H-ow&s=10' },
]
</script>
<template>
 <main>
 <h2>Lihat Produk</h2>
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
 
 h2 {
 background-color: #ff0a0a;
 color: #ffffff;
 text-align: center;
 
} 
</style>
