<template>
    <div id="title-class">
      <div class="container">
          <div class="row">
            <div class="col-lg-12">
              <h5>Rekomendasi Class</h5>
            </div>
            <div class="col-lg-12 all-list">
              <router-link to="/ListClass" style="color: #FFA800;">Lihat Semua</router-link>
            </div>
          </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
      name: 'TitleClass'
  }
  </script>
  
  <style>
  @media only screen and (max-width: 768px) {
    #title-class .all-list{
      text-align: center;
      font-weight: 400;
    }
  }
  
  @media only screen and (min-width: 768px) {
    #title-class .row{
      position: relative;
    }
  
    #title-class .all-list{
      text-align: right;
      font-weight: 400;
      position: absolute
    }
  }
  </style>