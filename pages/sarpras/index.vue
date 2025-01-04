<template>
  <div class="container-fluid">
    <div id="app">
      <header class="header">
        <img src="/assets/image/ruang/kurikulum.jpg" alt="Header Background" class="header-image" />
        <div class="header-overlay"></div>
      </header>
      <div class="row">
        <div class="col-lg-12 p-3"></div>
      </div>
      </div>

    <div class="row">
      <div class="col-lg-12">
        <h4 style="background-color: black;" class="text-white text-center rounded-1 p-2 m-4">
          Sarana dan Prasarana <b>SMKN 4 TASIKMALAYA</b>
        </h4>
      </div>
    </div>

    <p style="background-color: aliceblue;" class="text-black text-left rounded-1 p-2 m-3">
      <NuxtLink to="/sarpras/" class="text-decoration-none">Sarpras</NuxtLink>
    </p>

    <!-- Main Content Section -->
    <div class="container">
      <!-- Site Plan and Legend Section -->
      <div class="row align-items-start">
        <!-- Site Plan Image -->
        <div class="col-lg-4 col-md-5">
          <img src="/assets/image/denah.jpg" alt="Site Plan" class="site-plan-image" />
        </div>

        <!-- Legend -->
        <div class="col-lg-8 col-md-7">
          <p class="legend-title">Keterangan:</p>
          <ul class="legend">
            <li><span class="color-box blue"></span> A: Tool</li>
            <li><span class="color-box red"></span> B: R. Admin, Guru, UKS, Lab, Gudang</li>
            <li><span class="color-box green"></span> C: Masjid</li>
          </ul>
        </div>
      </div>
      <!-- List of Land Details -->
      <div class="tanah-list mt-4">
        <div
          v-for="tanah in [
            { id: 1, nama: 'Tanah 1', sertifikat: '10291002400014', luasLahan: 7861, luasBangunan: null, lahanKosong: null },
            { id: 2, nama: 'Tanah 2', sertifikat: '10291003400011', luasLahan: 2057, luasBangunan: null, lahanKosong: null },
            { id: 3, nama: 'Tanah 3', sertifikat: '10291003400012', luasLahan: 2920, luasBangunan: null, lahanKosong: null },
            { id: 4, nama: 'Tanah 4', sertifikat: '10291003400013', luasLahan: 400, luasBangunan: null, lahanKosong: null },
          ]"
          :key="tanah.id"
          class="tanah-card"
        >
          <h3 class="tanah-title">{{ tanah.nama }}</h3>
          <p>Sertifikat: <strong>{{ tanah.sertifikat }}</strong></p>
          <ul>
            <li>Luas Lahan: <strong>{{ tanah.luasLahan }}</strong> m²</li>
            <li>Luas Bangunan: <strong>{{ tanah.luasBangunan || '???' }}</strong></li>
            <li>Lahan Kosong: <strong>{{ tanah.lahanKosong || '???' }}</strong></li>
          </ul>
        </div>
      </div>
    

      <!-- Total Area Section -->
      <div class="total-luas mt-4 d-flex justify-content-center">
  <button class="btn btn-primary p-3 rounded">
    <strong>Total luas lahan:</strong>
    {{ [
      { luasLahan: 7861 },
      { luasLahan: 2057 },
      { luasLahan: 2920 },
      { luasLahan: 400 }
    ].reduce((total, tanah) => total + tanah.luasLahan, 0) }} m²
  </button>
</div>
</div>
</div>

    <!-- Accordion Section -->
    <div class="accordion" id="accordionExample">
      <div class="card">
        <div class="card-header" id="headingOne">
          <h2 class="mb-0">
            <button
              class="btn btn-link btn-block text-left"
              type="button"
              data-toggle="collapse"
              data-target="#collapseOne"
              aria-expanded="true"
              aria-controls="collapseOne"
            >
              Ruang Penunjang
            </button>
          </h2>
        </div>

        <div
          id="collapseOne"
          class="collapse show"
          aria-labelledby="headingOne"
          data-parent="#accordionExample"
        >
          <div class="card-body">
            <p style="background-color: aliceblue;" class="text-black text-left rounded-1 p-2 m-3">Techno Park / Tempat Praktek DKV</p>
            <div class="gallery-container">
              <!-- Menggunakan atribut title untuk menampilkan nama gambar -->
              <div class="gallery-item" title="Tampak Luar">
                <img src="/assets/image/tp1.jpeg" alt="Techno Park 1" class="gallery-image" />
              </div>
              <div class="gallery-item" title="Ruangan Dalam">
                <img src="/assets/image/tp2.jpg" alt="Techno Park 2" class="gallery-image" />
              </div>
              <div class="gallery-item" title="Tampak Depan">
                <img src="/assets/image/tp3.jpg" alt="Techno Park 3" class="gallery-image" />
              </div>
              <div class="gallery-item" title="Alat Praktek">
                <img src="/assets/image/tp4.jpg" alt="Techno Park 4" class="gallery-image" />
              </div>
            </div>
          </div>
          <div class="card-body">
            <p style="background-color: aliceblue;" class="text-black text-left rounded-1 p-2 m-3"> Tempat Praktek Tiap Jurusan </p>
            <div class="gallery-container">
              <!-- Menggunakan atribut title untuk menampilkan nama gambar -->
              <div class="gallery-item" title="Rekayasa Perangkat Lunak">
                <img src="/assets/image/ruang/rpl.jpeg" alt="Techno Park 1" class="gallery-image" />
              </div>
              <div class="gallery-item" title="Teknik Komputer Jaringan">
                <img src="/assets/image/ruang/tkj.jpeg" alt="Techno Park 2" class="gallery-image" />
              </div>
              <div class="gallery-item" title="Teknik Sepeda Motor">
                <img src="/assets/image/ruang/tsm.jpeg" alt="Techno Park 3" class="gallery-image" />
              </div>
            </div>
          </div>
          <div class="card-body">
            <p style="background-color: aliceblue;" class="text-black text-left rounded-1 p-2 m-3"> Tempat Ibadah ( Masjid) </p>
            <div class="gallery-container">
              <!-- Menggunakan atribut title untuk menampilkan nama gambar -->
              <div class="gallery-item" title="Masjid Al-Barokah">
                <img src="/assets/image/ruang/masjid.jpeg" alt="Techno Park 1" class="gallery-image" />
              </div>
              <div class="gallery-item" title="Masjid Al-Barokah">
                <img src="/assets/image/ruang/mesjid2.jpg" alt="Techno Park 2" class="gallery-image" />
              </div>
              <div class="gallery-item" title="Tempat Wudhu">
                <img src="/assets/image/ruang/wudhu.jpeg" alt="Techno Park 3" class="gallery-image" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<style>
/* Header Styling */
.header {
  position: relative;
}

.header-content {
  position: relative;
  text-align: center;
}

.header-image {
  width: 100%;
  max-height: 400px;
  object-fit: cover;
  border-radius: 10px;
}

.header-overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 10px;
}

.header-overlay h1 {
  font-size: 2.5rem;
  font-weight: bold;
}

/* Breadcrumb Styling */
.breadcrumb {
  background-color: #343a40;
  padding: 10px 20px;
  margin-bottom: 20px;
  color: white;
}

.breadcrumb-item {
  margin: 0;
}

/* Container and Section Title */
.container {
  font-family: 'Arial', sans-serif;
  margin: 20px auto;
}

.section-title {
  margin-bottom: 30px;
}

/* Site Plan and Legend */
.site-plan-image {
  width: 100%;
  max-width: 100%;  /* Memastikan gambar menggunakan seluruh lebar kontainer */
  max-height: 400px; /* Menyesuaikan gambar agar lebih besar */
  margin-bottom: 15px;
  display: block;
  border-radius: 10px;
}

.legend-title {
  font-weight: bold;
  margin-bottom: 10px;
}

.legend {
  list-style-type: none;
  padding: 0;
}

.legend li {
  margin-bottom: 5px;
}

.color-box {
  display: inline-block;
  width: 20px;
  height: 20px;
  margin-right: 10px;
  border-radius: 4px;
}

.color-box.blue {
  background-color: blue;
}

.color-box.red {
  background-color: red;
}

.color-box.green {
  background-color: green;
}

/* Tanah Card Styling */
.tanah-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.tanah-card {
  background-color: #f8f9fa;
  border: 1px solid #ddd;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  width: 250px;
  transition: transform 0.3s, box-shadow 0.3s;
}

.tanah-card:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

.tanah-title {
  font-size: 1.2rem;
  margin-bottom: 15px;
  color: #007bff;
}

/* Total Luas Button */
.total-luas {
  margin-top: 20px; /* Jarak antara ruang penunjang dan button */
  margin-bottom: 20px; /* Jarak di bawah button jika diperlukan */
}

.total-luas button {
  font-size: 1.2rem;
  width: auto;
}
/* Accordion Styling */
.card-header {
  background-color: #f8f9fa;
  border-bottom: 1px solid #ddd;
}

.card-header button {
  text-decoration: none;
  font-weight: bold;
  color: #333;
}

.card-body {
  padding: 20px;
}

/* Gallery Styling */
.gallery-container {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  justify-content: center;
}

.gallery-item {
  width: calc(25% - 15px); /* Empat item per baris dengan jarak */
  position: relative;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.gallery-image {
  width: 100%;
  height: 200px; /* Ukuran gambar lebih kecil */
  object-fit: cover;
}

.gallery-item:hover::after {
  content: attr(title); /* Menampilkan atribut title */
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.7);
  color: white;
  text-align: center;
  padding: 5px;
  font-size: 0.9rem;
}
</style>