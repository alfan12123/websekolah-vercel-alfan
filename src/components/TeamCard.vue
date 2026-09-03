<template>
  <div class="team-card">
    <div class="avatar">
      {{ nama.charAt(0) }}
    </div>

    <h3>{{ nama }}</h3>
    <p>{{ jabatan }}</p>
  </div>
</template>

<script setup>
defineProps({
  nama: String,
  jabatan: String
})
</script>

<style scoped>
.team-card {
  padding: 25px;
  text-align: center;
  background: white;
  border-radius: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
}

.avatar {
  width: 70px;
  height: 70px;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: #2563eb;
  color: white;
  font-size: 28px;
  font-weight: bold;
}
</style>