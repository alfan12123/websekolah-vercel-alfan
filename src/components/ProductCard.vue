<script setup>
defineProps(['nama', 'harga', 'gambar'])
</script>
<template>
 <div class="card">
 <img :src="gambar" :alt="nama" />
 <h3>{{ nama }}</h3>
 <p>Rp {{ harga.toLocaleString('id-ID') }}</p>
 <button class="btn-grad">Beli Sekarang</button>
 </div>
</template>
<style scoped>
.btn-grad {
  background-image: linear-gradient(to right, #ff00ea 0%, #fc0707 51%, #00ff00 100%);
}

.btn-grad {
  margin: 10px;
  padding: 15px 45px;
  text-align: center;
  text-transform: uppercase;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  box-shadow: 0 0 20px #eee;
  border-radius: 10px;
  display: block;
  outline: none;
  border: none;
}

.btn-grad:hover {
  background-position: right center;
  color: #fff;
  text-decoration: none;
}

.card {
 border: 1px solid #ddd;
 border-radius: 10px;
 padding: 14px;
 width: 200px;
 text-align: center;
}
.card img {
 width: 100%;
 border-radius: 6px;
}
</style>