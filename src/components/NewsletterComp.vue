<template>
    <div id="newsletter-section">
        <div class="container">
            <div class="row align-items-start">
                <div class="col-lg-6">
                    <img src="../assets/img-newsletter.png" alt="new-letter" width="25%">
                    <h1 class="my-3">Dapetin info terbaru <br> dari <span>Onmy.</span></h1>
                    <p class="my-2">Gabung newsletter agar nggak ketinggalan info terbaru!</p>
                </div>
                <div class="col-lg-6">
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label fw-bold">Nama Lengkap</label>
                            <input type="text" class="form-control" id="name" placeholder="Masukkan Nama lengkap">
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label fw-bold">Alamat Email</label>
                            <input type="email" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Masukkan Alamat Email">
                        </div>
                    </form>
                    <button type="submit" class="btn btn-orange my-3">Gabung Newsletter</button>
                </div>
            </div>
        </div>
    </div>
  </template>
  
  <script>
  export default {
      name: 'NewsletterComp'
  }
  </script>
  
  <style>
  </style>