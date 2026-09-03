<template>
  <main class="landing">
    <div class="content">
      <h1>Alfan Shop</h1>
      <p>
        Belanja Pakaian Keren dengan mudah
        cepat dan murah.
      </p>
      
      <RouterLink to="/product" class="btn-primary"><button>Meluncur🛫</button></RouterLink>
      
    </div>
  </main>
  <video controls width="1200" loop>
  <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
  Browser kamu tidak mendukung pemutaran video.
</video>
</template>

<style scoped>
.landing {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(149deg, #fdfdfd,#ff0909);
  border-radius: 10px;
}

.content {
  text-align: center;
}

h1 {
  font-size: 50px;
  color: #222;
  margin-bottom: 10px;
}

p {
  color: #000000;
  font-size: 18px;
  margin-bottom: 30px;
}

button {
  padding: 12px 30px;
  border: none;
  border-radius: 30px;
  background: #eb2525;
  color: rgb(255, 255, 255);
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: #1d4ed8;
  transform: translateY(-3px);
}
</style>