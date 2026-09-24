<template>
 <main>
    <section class="hero">
      <h1>Selamat Datang di Onlineshop</h1>
      <p>Belanja gampang, sekolah senang.</p>
      <RouterLink to="/product" class="tombol">Lihat Produk</RouterLink>
    </section>
        <div class="card">
            <div class="box">
                <span class="emote">💰</span>
                <h2>Harga Ayaan</h2>
                <p>Aman da moal totos</p>
            </div>
            <div class="box">
                <span class="emote">🚚</span>
                <h2>Bisa di anterukeun</h2>
                <p>Aman da moal totos</p>
            </div>
            <div class="box">
                <span class="emote">✅</span>
                <h2>Kualitas di jamin edans</h2>
                <p>Aman da moal totos</p>
            </div>
        </div>
 </main>
</template>

<style scoped>
main {
    display: flex;
    flex-direction: column;
    gap: 5rem;
}

.hero {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 2rem;
    padding: 2rem 5rem 2rem 5rem;
    text-align: center;
    background: linear-gradient(rgb(0, 140, 255), rgb(255, 238, 0));
    border-radius: 20px;
}
.card {
    display: grid;
    grid-template-columns: repeat(3, minmax(200px, 1fr));
    gap: 2rem;
    align-items: stretch;
}

.box {
   margin-top: 2rem;
   padding: 2rem 3rem;
   border-radius: 99px;
   background-color:rgb(0, 47, 255);
   color: rgb(0, 0, 0);
   font-weight: 500;
   transition: background-color 0.3s;
}

.tombol:hover {
    background-color:rgb(0, 255, 76);
    transform: translateY(-5px);
}
.box {
    display: flex; gap: 1rem; flex-wrap: wrap;
    flex-direction: column;
    justify-content: center;
    gap: 1rem;
    padding: 1rem;
    background-color: rgb(0, 143, 199);
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.359);
    text-align: center;
    font-size: 1rem;
}
.emote {
    font-size: 2rem;
}

</style>