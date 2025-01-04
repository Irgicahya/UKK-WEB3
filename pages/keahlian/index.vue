<template>
  <div id="app">
    <header class="header">
      <img src="/assets/image/ultah.jpeg" alt="Header Background" class="header-image" />
      <div class="header-overlay">
      </div>
    </header>
    <div class="row">
      <class class="col-lg-12 p-3">
      </class>
    </div>
    <div class="row">
      <class class="col-lg-12">
        <h4 style="background-color: black;" class="text-white text-center rounded-1 p-2 m-1">
          Kompetensi Keahlian <b> SMKN 4 TASIKMALAYA</b>
        </h4>
      </class>
    </div>
    <p style="background-color: honeydew;" class="text-black text-left rounded-1 p-2 m-3">
      <NuxtLink to="/kurikulum/" class="text-decoration-none">Kurikulum</NuxtLink>
    </p>
    
    <!-- Kompetensi Keahlian -->
    <div class="row mt-3">
      <!-- Teknik Komputer dan Jaringan -->
      <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5>Teknik Komputer dan Jaringan</h5>
          </div>
          <div class="card-body">
            <p>
              Teknik Komputer dan Jaringan merupakan ilmu berbasis Teknologi Informasi dan Komunikasi terkait kemampuan
              algoritma, dan pemrograman komputer,
              perakitan komputer, perakitan jaringan komputer, dan pengoperasian perangkat lunak, dan internet. Teknik
              komputer, dan jaringan juga
              membutuhkan pemahaman di bidang teknik listrik, dan ilmu komputer sehingga mampu mengembangkan, dan
              mengintegrasikan perangkat lunak, dan
              perangkat keras.
            </p>
          </div>
        </div>
      </div>

      <!-- Rekayasa Perangkat Lunak -->
      <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5> Rekayasa Perangkat Lunak</h5>
          </div>
          <div class="card-body">
            <p>
              Rekayasa Perangkat Lunak (RPL, atau dalam bahasa Inggris: Software Engineering atau SE) adalah satu bidang
              profesi yang mendalami cara-cara
              pengembangan perangkat lunak termasuk pembuatan, pemeliharaan, manajemen organisasi pengembangan perangkat
              lunak dan manajemen kualitas.
            </p>
            <p>
              Rekayasa perangkat lunak adalah pengubahan perangkat lunak itu sendiri guna mengembangkan, memelihara, dan
              membangun kembali dengan
              menggunakan prinsip rekayasa untuk menghasilkan perangkat lunak yang dapat bekerja lebih efisien dan
              efektif untuk pengguna.
            </p>
          </div>
        </div>
      </div>
      <!-- TBSM -->
      <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5>Teknik Bisnis Sepeda Motor</h5>
          </div>
          <div class="card-body">
            <p>
              Teknik dan Bisnis Sepeda Motor adalah kompetensi keahlian pada Bidang Studi Keahlian Teknologi dan
              Rekayasa Program
              Studi Keahlian Teknik Otomotif yang menekankan pada keterampilan pelayanan jasa mekanik kendaraan sepeda
              motor roda dua.
              Kompetensi Keahlian Teknik dan Bisnis Sepeda Motor menyiapkan peserta didik untuk bekerja pada bidang
              pekerjaan yang dikelola oleh badan,
              instansi atau perusahaan maupun pribadi (wirausaha).
            </p>
          </div>
        </div>
      </div>
      <!-- DKV -->
      <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5>Desain Komunikasi Visual</h5>
          </div>
          <div class="card-body">
            <p>
              Jurusan Desain Komunikasi Visual (DKV) adalah studi yang mempelajari ilmu tentang penyampaian pesan dengan
              menggunakan elemen desain grafis, seperti huruf, warna, gambar, dan lay out. Dalam keilmuan DKV,
              hal yang dipelajari adalah cara mengolah pesan visual yang efektif secara informatif, komunikatif,
              dan efektif, yang dikemas sekreatif mungkin sehingga pesan dapat tersampaikan dengan tepat sasaran
            </p>
          </div>
        </div>
      </div>

      <!-- TOI -->
      <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5>Teknik Otomasi Industri </h5>
          </div>
          <div class="card-body">
            <p>
              Teknik Otomasi Industri adalah sebuah bidang teknik yang mempelajari tentang perakitan sistem-sistem di
              dunia
              industri yang berbasis otomatis. Otomasi sendiri biasanya digunakan untuk mengendalikan mesin-mesin
              industri
              dan kontrol proses untuk menggantikan operator tenaga manusia
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
/* Reset CSS */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}

#app {
  display: flex;
  flex-direction: column;
  align-items: stretch;
}

/* Header Section */
.header {
  position: relative;
  width: 100%;
  height: 200px;
  overflow: hidden;
  margin-top: 15px;
}

.header-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.header-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  justify-content: center;
  align-items: center;
}

.header-overlay h1 {
  color: #fff;
  font-size: 24px;
  text-align: center;
  padding: 0 20px;
}

/* Main Content */
.content {
  padding: 20px;
}

/* Breadcrumb */
.breadcrumb {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
  font-size: 14px;
  color: #555;
}

.breadcrumb-link {
  text-decoration: none;
  color: #007bff;
  font-weight: bold;
}

.breadcrumb-link:hover {
  text-decoration: underline;
}

.breadcrumb span {
  margin: 0 5px;
}

.breadcrumb-current {
  color: #888;
}

/* Kompetensi Detail */
.kompetensi-detail {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
}

.kompetensi-detail h2 {
  font-size: 18px;
  margin-bottom: 10px;
  display: flex;
  align-items: center;
  color: #333;
}

.kompetensi-detail h2 i {
  margin-right: 10px;
  color: #007bff;
}

.kompetensi-detail p {
  font-size: 14px;
  color: #555;
  line-height: 1.6;
}
</style>