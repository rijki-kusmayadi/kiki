<script setup>
const daftarTeam = [
  {
    nama: 'Budiono siregar',
    kelas: 'XI RPL 1',
    jurusan: 'Rekayasa Perangkat Lunak',
  },
  {
    nama: 'Ujang karbu',
    kelas: 'XI RPL 2',
    jurusan: 'Rekayasa Perangkat Lunak',
  },
  {
    nama: 'Asep knalpot',
    kelas: 'XI RPL 3',
    jurusan: 'Rekayasa Perangkat Lunak',
  }
]
</script>
<template>
  <main>
    <div class="marvel">
      <h1>Tentang Kami</h1>
      <p>OnlineShop ini dibuat untuk memenuhi tugas akhir mata pelajaran PPLG.</p>
    </div>
    <div class="nyarita">
      <h2>Nyarita Dibalik OnlineShop</h2>
      <p>OnlineShop ini dibuat untuk memenuhi tugas akhir mata pelajaran PPLG.
        OnlineShop ini dibuat untuk menggunakan Vue.js</p>
    </div>
    <div class="foto">
      <img src="" alt="Foto Tim" />
    </div>
  <div class="tim">
    <TeamCard
      v-for="anggota in daftarTeam"
      :key="anggota.nama"
      :nama="anggota.nama"
      :kelas="anggota.kelas"
      :jurusan="anggota.jurusan"
    />
  </div>
  </main>
</template>

<style scoped>

</style>