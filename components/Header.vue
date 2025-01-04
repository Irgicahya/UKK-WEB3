<template>
  <div>
      <!-- Navbar -->
      <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
        <div class="container-fluid">
          <a class="navbar-brand d-flex align-items-center" href="#">
            <img src="assets/image/logo.png" alt="Logo" width="55" class="me-2" height="55"/>
            <span class="fw-bold">SMK Negeri 4 Tasikmalaya</span>
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a class="nav-link active d-flex align-items-center" aria-current="page" href="/">
                  <i class="fas fa-home me-2"></i> Home
                </a>
              </li>
              <!-- Dropdown Profil -->
              <li class="nav-item dropdown">
                <nuxt-link to="/profil/" class="dropdown-item">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownProfil" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Profile
                </a>
              </nuxt-link>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownProfil">
                  <li>
                    <nuxt-link to="/sejarah/" class="dropdown-item">Sejarah</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/visimisi/" class="dropdown-item">Visi & Misi</nuxt-link>
                  </li>
                  <li>
                    <nuxt-link to="/datapokok/" class="dropdown-item">Data Pokok</nuxt-link>
                  </li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <li class="nav-item dropdown">
                <nuxt-link to="/kurikulum/" class="dropdown-item">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownProfil" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Kurikulum
                </a>
              </nuxt-link>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdownProfil">
                <li>
                    <nuxt-link to="/keahlian/" class="dropdown-item">Kompetensi Keahlian</nuxt-link>
                  </li>
              </ul>
              </li>
              </li>
              <li>
                <nuxt-link to="/sarpras">
                  <a class="nav-link active d-flex align-items-center" aria-current="page">
                  <i class="fas fa-home me-2"></i> Sarpras
                </a></nuxt-link>
              </li>
              <li>
                <nuxt-link to="/eskul">
                  <a class="nav-link active d-flex align-items-center" aria-current="page">
                  <i class="fas fa-home me-2"></i> Ekstrakurikuler
                </a></nuxt-link>
                
              </li>
              <li>
                <nuxt-link to="/galeri">
                  <a class="nav-link active d-flex align-items-center" aria-current="page">
                  <i class="fas fa-home me-2"></i> Galeri
                </a></nuxt-link>
                
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </template>

  <script>

  export default {}
  </script>

  <style scoped>
  marquee {
    font-size: 14px;
  }
  .navbar-brand img {
    border-radius: 50%;
  }
  .nav-link {
    transition: color 0.3s ease;
  }
  .nav-link:hover {
    color: #4caf50;
  }
  /* Navbar Styles */
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #ffffff;
    box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
    padding: 5px 15px;
  }

  .navbar .logo {
    font-size: 20px;
    font-weight: bold;
  }

  .navbar ul {
    list-style: none;
    gap: 15px;
    margin: 0;
    padding: 0;
    box-shadow: 1 4px 4px rgba(0, 0, 0, 0.1);
  }

  .navbar ul li {
    position: relative;
  }

  .navbar ul li a {
    text-decoration: none;
    color: #333;
    padding: 3px 7px;
    display: block;
    font-size: 13px;
  }

  /* Dropdown Menu */
  .dropdown-menu {
    display: none;
    position: absolute;
    top: 80%;
    left: 0;
    background-color: #ffffff;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    z-index: 100;
    min-width: 150px;
  }

  .dropdown-menu li {
    width: 100%;
  }

  .dropdown-menu li a {
    padding: 10px;
  }

  .dropdown:hover .dropdown-menu {
    display: block;
  }
  </style>