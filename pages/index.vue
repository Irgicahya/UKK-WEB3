<template>
  <div class="layout-container">
    <!-- Carousel Section -->
    <div class="carousel">
      <div class="carousel-header">
        <h3>Selamat Datang di Website SMKN 4 Tasikmalaya</h3>
        <p>Posted by SMKN 4 Tasikmalaya</p>
      </div>
      <div class="carousel-content">
        <img src="/assets/image/guru.jpg" alt="Pengumuman" />
      </div>
      <div class="carousel-footer">
        <p>Sabtu, 04 Januari 2024</p>
      </div>
    </div>

    <!-- Sidebar Section -->
    <div class="sidebar">
      <div class="sidebar-header">
        <h4>Sambutan Kepala Sekolah</h4>
      </div>
      <div class="sidebar-content">
        <img
          src="/assets/image/pak.jpg"
          alt="Kepala Sekolah"
          class="profile-picture"
        />
        <p>
          Assalamu'alaikum Wr, Wb<br />
          Selamat datang di website SMKN 4 Tasikmalaya, tempat di mana kami bersama-sama berkomitmen untuk menciptakan lingkungan belajar yang inspiratif, aman, dan penuh semangat. Sebagai kepala sekolah, saya merasa sangat bangga dapat menyambut Anda di platform digital ini, yang menjadi jendela bagi kami untuk berkomunikasi, berbagi informasi,
Di SMKN 4 Tasikmalaya, kami percaya bahwa pendidikan adalah pondasi utama dalam membentuk generasi penerus bangsa yang berkualitas. .<br>
Wassalamualaikum warahmatullahi wabarakatuh.
        </p>
      </div>
    </div>
  </div>

  <!-- Berita -->

  <div class="card shadow-lg rounded-lg border-light d-flex justify-content-center">
      <div class="card-body">
        <h3 class="text-center mb-4">Berita Sekolah</h3>
        <!-- Row untuk Membagi Berita Lama (kiri) dan Berita Terbaru (kanan) -->
        <div class="row">
          <!-- Berita Lama (kiri) -->
          <div class="col-md-6 mb-4">
            <h4 class="text-center text-danger">Berita Lama</h4>
            <div class="list-group">
              <!-- Berita Lama Pertama -->
              <div class="list-group-item">
                <h5 class="mb-1">Lomba Futsal Antar Kelas</h5>
                <p class="mb-1">2023-10-25</p>
                <p class="mb-1">Lomba futsal antar kelas yang diadakan bulan lalu berlangsung meriah...</p>
              </div>

              <!-- Berita Lama Kedua -->
              <div class="list-group-item">
                <h5 class="mb-1">Workshop Kepemimpinan Siswa</h5>
                <p class="mb-1">2023-09-30</p>
                <p class="mb-1">Workshop kepemimpinan untuk siswa diadakan bulan lalu di sekolah...</p>
              </div>

              <!-- Berita Lama Ketiga -->
              <div class="list-group-item">
                <h5 class="mb-1">Peringatan Hari Kemerdekaan</h5>
                <p class="mb-1">2023-08-17</p>
                <p class="mb-1">Peringatan Hari Kemerdekaan Republik Indonesia di sekolah...</p>
              </div>
            </div>
          </div>

          <!-- Berita Terbaru (kanan) -->
          <div class="col-md-6 mb-4">
            <h4 class="text-center text-success">Berita Terbaru</h4>
            <div class="list-group">
              <!-- Berita Pertama -->
              <div class="list-group-item">
                <h5 class="mb-1">Penerimaan Siswa Baru 2024</h5>
                <p class="mb-1">2024-12-20</p>
                <p class="mb-1">Pendaftaran untuk siswa baru tahun ajaran 2024 telah dibuka...</p>
              </div>

              <!-- Berita Kedua -->
              <div class="list-group-item">
                <h5 class="mb-1">Ujian Tengah Semester 2024</h5>
                <p class="mb-1">2024-12-15</p>
                <p class="mb-1">Ujian Tengah Semester 2024 akan dilaksanakan pada minggu depan...</p>
              </div>

              <!-- Berita Ketiga -->
              <div class="list-group-item">
                <h5 class="mb-1">Kegiatan Ekstrakurikuler 2024</h5>
                <p class="mb-1">2024-12-10</p>
                <p class="mb-1">Berbagai kegiatan ekstrakurikuler untuk siswa akan dimulai pada bulan Januari...</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- keahlian -->

  <div class="expertise-container">
    <div class="card-wrapper">
      <div class="card">
        <div class="card-inner">
          <!-- Move "Kompetensi Keahlian" inside the card -->
          <h2 class="title">Program Keahlian</h2>
          <div class="cards-wrapper">
            <div class="card-item">
              <div class="card-inner-item">
                <img src="/assets/image/ruang/tkjt.png" alt="icon" class="card-image" />
                <div class="card-content">
                  <h3 class="card-title">Teknik Jaringan Komputer dan Telekomunikasi </h3>
                  <h3 class="card-title" style="font-size: 14px;"><b> Sarana Pendukung Pembelajaran : </b> </h3>
                  <p class="card-description">Bengkel TKJ<br>
                    Network Simulator<br> 
                    Techno Park</p>
                </div>
              </div>
            </div>
            <div class="card-item">
              <div class="card-inner-item">
                <img src="/assets/image/ruang/pplg.png" alt="icon" class="card-image" />
                <div class="card-content">
                  <h3 class="card-title">Pengembangan Perangkat Lunak dan Gim </h3>
                  <h3 class="card-title" style="font-size: 14px;"><b> Sarana Pendukung Pembelajaran : </b> </h3>
                  <p class="card-description">Laboratorium Komputer
                    Computer Server <br>
                    Techno park
                  </p>
                </div>
              </div>
            </div>
            <div class="card-item">
              <div class="card-inner-item">
                <img src="/assets/image/ruang/tbsm.png" alt="icon" class="card-image" />
                <div class="card-content">
                  <h3 class="card-title">Teknik Otomasi </h3>
                  <h3 class="card-title" style="font-size: 14px;"><b> Sarana Pendukung Pembelajaran : </b> </h3>
                  <p class="card-description">Bengkel TBSM <br> 
                    Unit Produksi<br> 
                    Techno Park
                  </p>
                </div>
              </div>
            </div>
            <div class="card-item">
              <div class="card-inner-item">
                <img src="/assets/image/ruang/dkv.png" alt="icon" class="card-image" />
                <div class="card-content">
                  <h3 class="card-title">Desain Komunikasi Visual</h3>
                  <h3 class="card-title" style="font-size: 14px;"><b> Sarana Pendukung Pembelajaran : </b> </h3>
                  <p class="card-description">Techno Park 

                  </p>
                </div>
              </div>
            </div>
            <div class="card-item">
              <div class="card-inner-item">
                <img src="/assets/image/ruang/toi.png" alt="icon" class="card-image" />
                <div class="card-content">
                  <h3 class="card-title">Teknik Elektronika </h3>
                  <h3 class="card-title" style="font-size: 14px;"><b> Sarana Pendukung Pembelajaran : </b> </h3>
                  <p class="card-description">Laboratorium Mekatronik
                  Terminal Input/Output(i/O)
                  Sumber Daya Listrik</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="text-center">
            <nuxt-link to="/keahlian/" class="dropdown-item">
            <button class="btn btn-primary me-1">Selengkapnya</button>
          </nuxt-link>
          </div>
      </div>
    </div>
  </div>
  <div class="col-lg-12 mb-3 d-flex justify-content-center">
        <div class="card">
          <div class="card-header bg-light">
            <h5 class="text-center">Statistik Data</h5>
          </div>
          <div class="card-body">
            <div class="row">
              <!-- Jumlah Siswa -->
              <div class="col-md-6 mb-3">
                <div class="card bg-success text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Siswa</h6>
                    <h3>1610</h3>
                  </div>
                </div>
              </div>
              <!-- Jumlah Rombel -->
              <div class="col-md-6 mb-3">
                <div class="card bg-danger text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Rombel</h6>
                    <h3>45</h3>
                  </div>
                </div>
              </div>
              <!-- Jumlah Guru -->
              <div class="col-md-6 mb-3">
                <div class="card bg-warning text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Guru</h6>
                    <h3>82</h3>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi -->
              <div class="col-md-6 mb-3">
                <div class="card bg-info text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Tenaga Administrasi</h6>
                    <h3>12</h3>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
</template>

<script>
export default {
  name: "AnnouncementAndWelcome",
};
</script>

<style scoped>
/* Layout Styles */
.layout-container {
  display: flex;
  gap: 16px;
  margin: 50px;
}

/* Carousel Styles */
.carousel {
  flex: 3;
  background-color: #fff;
  border: 1px solid #e0e0e0;
  border-radius: 50px;
  overflow: hidden;
}

.carousel-header {
  background-color: rgba(0, 0, 0, 0.7);
  color: #fff;
  padding: 10px;
  text-align: center;
}

.carousel-header h3 {
  margin: 0;
  font-size: 18px;
}

.carousel-header p {
  margin: 5px 0 0;
  font-size: 12px;
  font-style: italic;
}

.carousel-content {
  position: relative;
  width: 650px;
  height: 720px;
}

.carousel-content img {
  width: 1400px;
  height: 720px;
}

.carousel-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}

/* .berita-button {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 5px 10px;
  font-size: 14px;
  border-radius: 4px;
  cursor: pointer;
} */

.berita-button:hover {
  background-color: #0056b3;
}

.carousel-footer p {
  font-size: 12px;
  color: #333;
}

/* Sidebar Styles */
.sidebar {
  flex: 1;
  background-color: #f8f9fa;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  padding: 10px;
}

.sidebar-header {
  background-color: #343a40;
  color: #fff;
  padding: 10px;
  text-align: center;
  border-radius: 8px 8px 0 0;
}

.sidebar-header h4 {
  margin: 0;
  font-size: 16px;
}

.sidebar-content {
  text-align: center;
  padding: 10px;
}

.profile-picture {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-bottom: 10px;
  border: 2px solid #ddd;
}

.sidebar-content p {
  font-size: 14px;
  line-height: 1.5;
  color: #333;
}

.expertise-container {
  text-align: center;
  padding: 25px;
  background-color: #f4f7fa;
  margin-top: 0;
}

.title {
  font-size: 2.5em;
  color: #333;
  margin-bottom: 20px;
}

.card-wrapper {
  display: flex;
  justify-content: center;
}

.card {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  width: 100%;
  max-width: 1200px;
  overflow: hidden;
  padding: 20px;
}

.card-inner {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.cards-wrapper {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 20px;
}

.card-item {
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  width: 18%;
  overflow: hidden;
  transition: transform 0.3s ease;
  cursor: pointer;
}

.card-item:hover {
  transform: translateY(-10px);
}

.card-inner-item {
  display: flex;
  flex-direction: column;
  height: 100%;
}

.card-image {
  width: 50px;            /* Mengatur lebar gambar menjadi 50px */
  height: 50px;           /* Mengatur tinggi gambar menjadi 50px */
  object-fit: cover;      /* Memastikan gambar tetap proporsional di dalam kontainer */
  border-radius: 50%;     /* Membuat gambar berbentuk bulat */
  display: block;         /* Memastikan gambar tampil sebagai blok */
  margin: 0 auto;         /* Menyusun gambar di tengah secara horizontal */
}

.card-content {
  padding: 15px;
}

.card-title {
  font-size: 1.2em;
  color: #333;
  margin-bottom: 10px;
}

.card-description {
  font-size: 0.9em;
  color: #666;
}

.text-center{
  margin-top: 20px;
}

/* berita */
.container {
  max-width: 1200px;
}

h1 {
  font-size: 3rem;
  color: #007bff;
  font-weight: bold;
}

h3 {
  font-size: 2rem;
  font-weight: bold;
}

.card {
  border-radius: 15px;
  margin: auto;
  transition: all 0.3s ease-in-out;
  background-color: #f8f9fa;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
}

.card-body {
  padding: 1.25rem;
}

.list-group-item {
  margin-bottom: 15px;
}

.list-group-item h5 {
  font-size: 1.2rem;
  color: #343a40;
}

.list-group-item p {
  font-size: 0.95rem;
  color: #6c757d;
}

.row {
  display: flex;
  justify-content: space-between;
}

.mb-4 {
  margin-bottom: 30px;
}

/* Optional: Background gradient for the page */
body {
  background: linear-gradient(135deg, #e0f7fa, #d1e7ff);
  padding: 30px 0;
}
</style>
