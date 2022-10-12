<template>
  <div id="ClassRec">
    <div class="container">
      <div class="row">
        <div class="col-lg-3 course-card">
          <div class="card">
            <img
              src="../assets/img-class1.png"
              class="card-img-top course-img"
              alt="alts"
            />
            <div class="card-body">
              <p class="course-type">Bootcamp, Sesi Live</p>
              <p class="card-title course-title">Fullstack Web Programming</p>
              <p class="card-price course-price">Rp 1.500.000</p>
              <div class="card-bottom d-flex justify-content-center">
                <router-link to="/DetailHotel" class="btn btn-orange"
                  >Belajar Sekarang!</router-link
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 course-card">
          <div class="card">
            <img
              src="../assets/img-class2.png"
              class="card-img-top course-img"
              alt="alts"
            />
            <div class="card-body">
              <p class="course-type">Bootcamp, Sesi Live</p>
              <p class="card-title course-title">UI & UX Design Fundamental</p>
              <p class="card-price course-price">Rp 1.500.000</p>
              <div class="card-bottom d-flex justify-content-center">
                <router-link to="/DetailHotel" class="btn btn-orange"
                  >Belajar Sekarang!</router-link
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 course-card">
          <div class="card">
            <img
              src="../assets/img-class3.png"
              class="card-img-top course-img"
              alt="alts"
            />
            <div class="card-body">
              <p class="course-type">Bootcamp, Sesi Live</p>
              <p class="card-title course-title">Graphic Design Fundamental</p>
              <p class="card-price course-price">Rp 1.500.000</p>
              <div class="card-bottom d-flex justify-content-center">
                <router-link to="/DetailHotel" class="btn btn-orange"
                  >Belajar Sekarang!</router-link
                >
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3 course-card">
          <div class="card">
            <img
              src="../assets/img-class4.png"
              class="card-img-top course-img"
              alt="alts"
            />
            <div class="card-body">
              <p class="course-type">Bootcamp, Sesi Live</p>
              <p class="card-title course-title">Digital <br> Marketing</p>
              <p class="card-price course-price">Rp 1.500.000</p>
              <div class="card-bottom d-flex justify-content-center">
                <router-link to="/DetailHotel" class="btn btn-orange"
                  >Belajar Sekarang!</router-link
                >
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
  name: "ClassRec",
};
</script>

<style></style>
