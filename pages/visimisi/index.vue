<template> 
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <header class="header mt-3"> <!-- Menambahkan margin-top pada header -->
          <img src="/assets/image/ultah.jpeg" alt="Header Background" class="header-image mb-3" />
          <div class="header-overlay"></div>
        </header>

        <h4 style="background-color: black;" class="text-white text-center rounded-1 p-2 m-4">
          <b>VISI - MISI - TUJUAN </b>
        </h4>
      </div>
    </div>

    <p style="background-color: honeydew;" class="text-black text-left rounded-1 p-2 m-3">
      <NuxtLink to="/profil/" class="text-decoration-none">Profil </NuxtLink>
      <span>/</span>
      <span class="breadcrumb-current">Visi Misi </span>
    </p>
  
    <div class="content text-center">
      <section class="box">
        <h3>Visi & Misi SMK Negeri 4 Tasikmalaya</h3>
        <div class="vision">
          <h3>Visi:</h3>
          <p class="vision-text">"TERWUJUDNYA LULUSAN YANG CERDAS, AKTIF, KOMPETITIF, ADAPTIF, DAN PRODUKTIF BERLANDASKAN IMAN DAN TAKWA"</p>
          <p class="vision-text">"CAKAP BERIMTAK"</p>
        </div>
        <div class="mission">
          <h3>Misi:</h3>
          <ol class="mission-text">
            <li>Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.</li>
            <li>Meningkatkan dan mengembangkan aktivitas serta kreativitas seluruh warga sekolah dalam berbagai kegiatan positif.</li>
            <li>Mewujudkan manajemen pendidikan yang efektif, efisien, transparan, akuntabel, dan layanan prima.</li>
            <li>Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non-akademik.</li>
            <li>Menyelenggarakan berbagai program keunggulan dalam upaya meningkatkan Sumber Daya Manusia yang berkualitas dengan mengacu pada perkembangan zaman.</li>
            <li>Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah aktivitas dan kreativitas warga sekolah.</li>
            <li>Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri.</li>
            <li>Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.</li>
            <li>Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.</li>
          </ol>
        </div>
      </section>

      <section class="box">
        <h2>Tujuan SMK Negeri 4 Tasikmalaya</h2>
        <ol class="goal-text">
          <li>Sekolah meraih prestasi pencapaian nilai rata-rata UN dan indeks integritas di atas rata-rata Nasional pada tahun 2026.</li>
          <li>Sekolah menghasilkan Tamatan yang siap bekerja minimal 50% di Tanah Air bekerja pada tahun 2024.</li>
          <li>Terciptanya aktivitas dan kreativitas yang positif oleh seluruh warga sekolah.</li>
          <li>Sekolah meraih prestasi akademik dan non-akademik minimal di tingkat provinsi Jawa Barat dan Nasional.</li>
          <li>Sekolah memiliki tenaga pendidik dan kependidikan yang berkualifikasi minimal S1 di bidang pendidikan dan telah mengikuti diklat implementasi kurikulum merdeka pada tahun 2024.</li>
          <li>Sekolah mencapai kriteria sekolah berwawasan lingkungan (adwiyata) pada tahun 2026.</li>
          <li>Sekolah terakreditasi dengan nilai A pada tahun 2024.</li>
          <li>Sekolah memiliki Lembaga Sertifikasi Profesi (LSP) yang tersertifikasi, Tempat Uji Kompetensi (TUK) yang terverifikasi dan Bursa Kerja Khusus (BKK) yang terakreditasi pada tahun 2025.</li>
          <li>Sekolah memiliki Perpustakaan yang terakreditasi A pada tahun 2024.</li>
          <li>Sekolah menjadi Badan Layanan Umum Daerah (BLUD) pada tahun 2025.</li>
          <li>Sekolah memiliki Dokumen Kurikulum Merdeka untuk seluruh tingkat pada tahun 2024.</li>
          <li>Sekolah memiliki Implementasi Kurikulum Merdeka dengan Pembelajaran Berdiferensiasi dan Pembelajaran Sosial-Emosional di seluruh kelas pada tahun 2024.</li>
          <li>Sekolah memiliki sarana prasarana sesuai dengan standar pelayanan minimal pendidikan dan standar IDUKA pada tahun 2024.</li>
          <li>Sekolah menjalin kerjasama dengan IDUKA dan Institusi terkait untuk program Teaching Factory dan Kelas Industri.</li>
          <li>Sekolah melaksanakan program menumbuhkan kebanggaan terhadap lulusan dengan peningkatan integritas, etika kurikuler dan non-kurikuler.</li>
        </ol>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "SchoolVisionMission",
};
</script>

<style scoped>
.content {
  font-family: Arial, sans-serif;
  margin: 20px;
}
h1, h2 {
  color: #2c3e50;
  text-align: center;
}
.box {
  border: 2px solid #2c3e50;
  padding: 20px;
  border-radius: 10px;
  background-color: #f9f9f9;
  margin: 20px auto;
  max-width: 1200px; /* Lebar maksimum diperbesar */
}
ol {
  margin-left: 20px;
  text-align: left;
}
.vision-text {
  font-size: 14px; /* Ukuran huruf lebih kecil */
}
.mission-text li, .goal-text li {
  font-size: 14px; /* Ukuran huruf lebih kecil untuk Misi dan Tujuan */
}
</style>
