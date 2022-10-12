<template>
    <div id="FooterComp">
      <!-- Footer -->
      <div class="footer" id="footer">
        <div class="container">
          <div class="row footer-row">
            <div class="col-lg-3">
              <img src="../assets/logo-orange.png" alt="logo-houtel" />
              <div class="text-footer">
                <p style="font-weight: 600">Platform Belajar <br> Online Indonesia!</p>
                <p style="color: #CDCDCD;">© Copyright Onmy 2022</p>
              </div>
            </div>
            <div class="col-lg-3">
                <p style="font-weight: 600">Company</p>
                <ul style="list-style-type: none;padding: 0;margin: 0;">
                  <li><router-link class="nav-link my-2" to="">Tentang Perusahaan</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Karir</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Support</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Testimonial</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Terms of Service</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Privacy Policy</router-link></li>
                </ul>
            </div>
            <div class="col-lg-3">
                <p style="font-weight: 600">For Student</p>
                <ul style="list-style-type: none;padding: 0;margin: 0;">
                  <li><router-link class="nav-link my-2" to="">Jadi Pro!</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Blog</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Kelas Anak</router-link></li>
                  <li><router-link class="nav-link my-2" to="">Materi Belajar</router-link></li>
                </ul>
            </div>
            <div class="col-lg-3">
              <div class="row gap-5">
                <div class="col-lg-12">
                  <h6>Kebijakan Privasi</h6>
                  <div class="icon-social-media">
                    <a href="#">
                      <img src="../assets/instagram.png" alt="instagram" />
                    </a>
                    <a href="#"><img src="../assets/facebook.png" alt="facebook" /></a>
                    <a href="#"><img src="../assets/twitter.png" alt="twitter" /></a>
                    <a href="#"><img src="../assets/youtube.png" alt="youtube" /></a>
                  </div>
                </div>
                <div class="col-lg-12">
                  <h6>Part of:</h6>
                  <div class="icon-synapse">
                    <a href="#">
                      <img src="../assets/logo_synapse.png" alt="syn-academy" />
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Footer End -->
    </div>
  </template>
  
  <script>
  export default {
      name: 'FooterComp'
  }
  </script>
  
  <style>
  </style>