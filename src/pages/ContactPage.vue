<template>
    <div class="contact">
        <section class="hero">
        <h1><u>Hubungi Kami</u></h1>
  </section>

        <h3>Kirim Pesan</h3>
        
        <form @submit.prevent="submitForm">
            <div>
                <label for="name">👨‍💼Nama:</label>
                <input type="text" id="name" v-model="name" required />
            </div>
            <div>
                <label for="email">✉ Email:</label>
                <input type="email" id="email" v-model="email" required />
            </div>
            <div>
                <label for="password">🔐Password:</label>
                <input type="password" id="password" v-model="password" required />
            </div>
            <div>
                <label for="message">💬Pesan:</label>
                <textarea id="message" v-model="message" required></textarea>
            </div>
            <button type="submit">Kirim</button>
        </form>
    </div>
</template>

<style>
.contact {
    text-align: center;

}
.hero {
    margin-bottom: 2rem;
    background-color: #ffffff;
    padding: 2rem;
}
.hero h1 {
    color: #000000;
    font-size: 2rem;
} 
</style>
