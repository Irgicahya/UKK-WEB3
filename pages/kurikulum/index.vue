<template>
  <div class="container-fluid">
    <div id="app">
      <header class="header">
        <img src="/assets/image/ruang/r2.jpg" alt="Header Background" class="header-image" />
        <div class="header-overlay"></div>
      </header>
      <div class="row">
        <div class="col-lg-12 p-3"></div>
      </div>

      <div class="row">
        <div class="col-lg-12">
          <h4 style="background-color: black;" class="text-white text-center rounded-1 p-2 m-1">
            Kurikulum <b>SMKN 4 TASIKMALAYA</b>
          </h4>
        </div>
        <main class="content">
          <!-- Breadcrumb -->
          <p style="background-color: honeydew;" class="text-black text-left rounded-1 p-2 m-3">
            <a href="/kurikulum/" class="text-decoration-none">kurikulum</a>
          </p>
        </main>
      </div>
    </div>

    <!-- Kompetensi Keahlian -->
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
  margin: 20px;
}

/* Carousel Styles */
.carousel {
  flex: 3;
  background-color: #fff;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
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
}

.carousel-content img {
  width: 100%;
  height: auto;
}

.carousel-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}

.berita-button {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 5px 10px;
  font-size: 14px;
  border-radius: 4px;
  cursor: pointer;
}

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
</style>
