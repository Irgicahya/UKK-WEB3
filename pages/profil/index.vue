<template>
  <div class="container-fluid">
    <div id="app">
      <header class="header">
        <img src="/assets/image/ultah.jpeg" alt="Header Background" class="header-image" />
        <div class="header-overlay"></div>
      </header>
      <div class="row">
        <div class="col-lg-12 p-3"></div>
      </div>
      </div>

    <div class="row">
      <div class="col-lg-12">
        <h4 style="background-color: black;" class="text-white text-center rounded-1 p-2 m-4">
          Profil <b>SMKN 4 TASIKMALAYA</b>
        </h4>
      </div>
    </div>

    <p style="background-color: honeydew;" class="text-black text-left rounded-1 p-2 m-3">
      <NuxtLink to="/profil/" class="text-decoration-none">Profil</NuxtLink>
    </p>

    <!-- Sejarah -->
    <div class="col-lg-12 mb-3">
      <div class="card">
        <div class="card-header bg-light">
          <h5 class="text-center">Sejarah SMK Negeri 4 Tasikmalaya</h5>
        </div>
        <div class="card-body">
          <!-- Menggunakan d-flex untuk menyusun gambar dan teks secara horizontal -->
          <div class="d-flex align-items-start">
            <!-- Gambar -->
            <img src="/assets/image/pak.jpg" alt="Image" class="card-image me-3" />
            <!-- Paragraf -->
            <p style="font-size: 14px;">
              Sejalan dengan Program Pemerintah di bidang pendidikan Menengah Kejuruan pada saat itu yakni pemerataan
              akses, ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan
              adanya SMK Negeri di daerah Kecamatan Purbaratu Kota Tasikmalaya, terutama untuk menampung tamatan dari
              SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat,
              unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota
              Tasikmalaya dan Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota
              Tasikmalaya.
            </p>
          </div>
          <div class="text-center">
            <nuxt-link to="/sejarah/" class="dropdown-item">
            <button class="btn btn-primary me-1">Read More</button>
          </nuxt-link>
          </div>
        </div>
      </div>
    </div>

    <!-- Visi dan Misi -->
    <div class="col-lg-12 mb-3">
      <div class="card">
        <div class="card-header bg-light">
          <h5 class="text-center">Visi dan Misi SMK Negeri 4 Tasikmalaya</h5>
        </div>
        <div class="card-body text-center">
          <h5>Visi:</h5>
          <p style="font-size: 14px; margin-left: 20px;">
            " Dengan Berlandaskan Iman dan Taqwa Menghasilkan Tamatan yang Cerdas, Akhlak mulia, Kreatif, Aktif,
            Produktif (CAKAP) "
          </p>
          <h5>Misi:</h5>
          <p style="font-size: 14px; margin-left: 20px;">
            1. Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.<br />
            2. Meningkatkan dan mengembangkan aktivitas serta kreativitas seluruh warga sekolah dalam berbagai kegiatan
            positif.<br />
            3. Mewujudkan manajemen pengelolaan yang efektif, efisien, transparan, akuntabel, dan layanan prima.
          </p>
          <!-- Tombol Aksi -->
          <div class="text-center"><NuxtLink to="/visimisi/">
            <button class="btn btn-primary me-2">Read More</button>
          </NuxtLink>
          </div>
        </div>
      </div>
    </div>

    <!-- Identitas Sekolah -->
    <div class="col-lg-12 mb-3">
      <div class="card">
        <div class="card-header bg-light">
          <h5 class="text-center">Identitas Sekolah Menengah Kejuruan Negeri 4 Tasikmalaya</h5>
        </div>
        <div class="card-body">
          <table class="n4table tableidentitas">
            <tbody>
              <tr>
                <td>
                  <b>a.</b>
                </td>
                <td>
                  <b> Nama Sekolah</b>
                </td>
                <td>:</td>
                <td>SMK Negeri 4 Kota Tasikmalaya</td>
              </tr>
              <tr>
                <td>
                  <b>b.</b>
                </td>
                <td>
                  <b>NPSN</b>
                </td>
                <td>:</td>
                <td>20276063</td>
              </tr>
              <tr>
                <td>
                  <b>c.</b>
                </td>
                <td>
                  <b> Nomor Statistik Sekolah</b>
                </td>
                <td>:</td>
                <td> 401327810004 </td>
              </tr>
              <tr>
                <td>
                  <b>d.</b>
                </td>
                <td>
                  <b> Alamat </b>
                </td>
                <td> : </td>
                <td> </td>
              </tr>
              <tr>
                <td> </td>
                <td> Jalan </td>
                <td> : </td>
                <td> Jl Depok RT 02 RW 05 </td>
              </tr>
              <tr>
                <td> </td>
                <td> Kelurahan </td>
                <td> : </td>
                <td> Sukamenak </td>
              </tr>
              <tr>
                <td> </td>
                <td> Kecamatan </td>
                <td> : </td>
                <td> Purbaratu </td>
              </tr>
              <tr>
                <td> </td>
                <td> Kota </td>
                <td> : </td>
                <td> Tasikmalaya </td>
              </tr>
            </tbody>
          </table>
          <div class="text-center">
            <nuxt-link to="/datapokok/" class="dropdown-item">
            <button class="btn btn-primary me-1">Read More</button>
          </nuxt-link>
          </div>
        </div>
      </div>
    </div>
    <!-- Pendidik dan Tenaga Kependidikan -->
    <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5 class="text-center"> Pendidik dan Tenaga Kependidikan</h5>
          </div>
          <div class="card-body">
            <div class="row">
              <!-- Jumlah Guru PNS -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-primary text-white">
                    <h6 class="text-center mb-0">Jumlah Guru PNS</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 7 orang</p>
                    <p>Perempuan: 3 orang</p>
                    <p>Total: 10 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Guru Honorer -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-secondary text-white">
                    <h6 class="text-center mb-0">Jumlah Guru Honorer</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 20 orang</p>
                    <p>Perempuan: 10 orang</p>
                    <p>Total: 30 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi PNS -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-success text-white">
                    <h6 class="text-center mb-0">Jumlah Tenaga Administrasi PNS</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 2 orang</p>
                    <p>Perempuan: 1 orang</p>
                    <p>Total: 3 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi Honorer -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-warning text-white">
                    <h6 class="text-center mb-0">Jumlah Tenaga Administrasi Honorer</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 3 orang</p>
                    <p>Perempuan: 2 orang</p>
                    <p>Total: 5 orang</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-12 mb-3">
      <div class="card">
        <div class="card-header bg-light">
          <h5 class="text-center">Struktur Organisasi</h5>
        </div>
        <div class="card-body">
          <table class="n4table tableidentitas">
            <tbody>
              <tr>
                <td>
                  <b> 1. </b>
                </td>
                <td>
                  <b> Kepala Sekolah </b>
                </td>
                <td>:</td>
                <td> Kurniawan, S.Pd, M.Pd.</td>
              </tr>
              <tr>
                <td>
                  <b> 2. </b>
                </td>
                <td>
                  <b> Komite Sekolah </b>
                </td>
                <td> : </td>
                <td> H. Abun Sulaeman, S.Ag.</td>
              </tr>
              <tr>
                <td>
                  <b> 3. </b>
                </td>
                <td>
                  <b> PLT Kasubag TU </b>
                </td>
                <td> : </td>
                <td> Yaman Suryaman, S.Sos.</td>
              </tr>
            </tbody>
          </table>
          </div>
      </div>
      </div>
</div>
</template>
<script>
export default {
  name: "StatistikData",
};
</script>
<style scoped>
.card-image {
  width: 5%;
  height: auto;
  margin-bottom: 10px;
}
.header {
  text-align: center;
  margin-bottom: 16px;
}
.statistik-card h3 {
  margin: 0;
  font-size: 18px;
  color: #333;
}

.statistik-value {
  margin: 8px 0 0;
  font-size: 24px;
  font-weight: bold;
  color: #000;
}

.footer {
  text-align: center;
  margin-top: 16px;
}
</style>

