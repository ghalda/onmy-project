<template>
    <div id="HeaderComp">
      <!-- Navbar Sections -->
      <nav class="navbar navbar-expand-lg">
        <div class="container">
          <a class="navbar-brand" href="#">
            <img src="../assets/logo-white.png" alt="logo" />
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNavAltMarkup"
            aria-controls="navbarNavAltMarkup"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
              <router-link class="nav-link fw-normal" to="/">Beranda</router-link>
              <router-link class="nav-link fw-normal" to="">Kelas</router-link>
              <router-link class="nav-link fw-normal" to="">Karir</router-link>
              <router-link class="nav-link fw-normal" to="">Alumni</router-link>

              <!-- Trigger Button Modal -->
              <button type="button" class="btn btn-orange" data-bs-toggle="modal" data-bs-target="#loginModal">Masuk</button>

              <!-- Modal -->
              <div class="modal fade" id="loginModal" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
                <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
                  <div class="modal-content">
                    <div class="modal-header">
                      <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body">
                      <div class="row">
                        <div class="col-lg-10 mx-auto text-center">
                          <h5 style="color:#FFA800">Selamat Datang</h5>
                          <p style="color: #CDCDCD;">Isi form berikut untuk melanjutkan.</p>
                        </div>
                        <div class="col-lg-10 mx-auto">
                          <form>
                            <div class="mb-3">
                              <label for="Email" class="form-label">Email</label>
                              <input type="email" class="form-control" id="Email" aria-describedby="emailHelp">
                            </div>
                            <div class="mb-3">
                              <label for="Password" class="form-label">Kata Sandi</label>
                              <input type="password" class="form-control" id="Password">
                            </div>
                            <div class="mb-3 form-check">
                              <input type="checkbox" class="form-check-input" id="exampleCheck1">
                              <label class="form-check-label" for="exampleCheck1">Ingat Saya</label>
                            </div>
                          </form>
                          <div class="d-grid gap-4 col-12 mx-auto text-center mt-4">
                              <button type="submit" class="btn btn-orange login">Masuk</button>
                              <button type="submit" class="btn btn-google d-flex gap-2 align-items-center justify-content-center">
                                <img src="../assets/logo-google.png" alt="logo google" width="10%">
                                <span>Masuk dengan Google</span>
                              </button>
                              <p style="color: #CDCDCD;">Belum punya Akun? <b style="color: #FFA800;">Registrasi</b></p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </nav>
      <!-- Navbar Sections End -->
    </div>
  </template>
  
  <script>
  export default {
      name: 'HeaderComp'
  }
  </script>
  
  <style>
  </style>