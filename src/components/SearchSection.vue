<template>
    <div class="main-div">
      <h3 class="search-heading">Explore Turf Nearby You</h3>
      <section class="search-section py-5 bg-light rounded-4">
        <div class="container mx-auto">
          <div class="row">
            <div class="col-md-3">
              <div class="input-wrapper">
                <input type="text" class="form-control inp-text" placeholder="Turf Name">
                <img class="inp-icon inp-name-img" src="../assets/images/search.png" alt="">
              </div>
            </div>
            <div class="col-md-3">
              <div class="input-wrapper">
                <input type="text" class="form-control inp-text" placeholder="Location">
                <img class="inp-icon inp-location-img" src="../assets/images/location.png" alt="">
              </div>
            </div>
            <div class="col-md-3">
              <div class="input-wrapper">
                <input type="text" class="form-control inp-text" placeholder="Sports">
                <img class="inp-icon inp-sports-img" src="../assets/images/sports.png" alt="">
              </div>
            </div>
            <div class="col-md-3">
              <button class="btn btn-danger btn-block btn-size rounded-5 accordion-header mx-auto">Search</button>
            </div>
          </div>
        </div>
      </section>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  * {
    font-family: "Poppins";
  }

  .main-div{
    margin-bottom: 95px;
  }
  
  .search-heading {
    font-size: 26px;
    font-weight: bold;
    margin-top: 64px;
    margin-bottom: 76px;
  }
  
  .search-section {
    background-color: rgba(217, 217, 217, 1);
  }
  
  .input-wrapper {
    position: relative;
  }
  
  .inp-text {
    width: 296px;
    height: 66px;
    padding-left: 60px;
    color: rgba(0, 0, 0, 1);
    background-color: rgba(240, 240, 240, 1);
  }
  
  .inp-icon {
    position: absolute;
    top: 50%;
    left: 15px; /* Adjust the position as needed */
    transform: translateY(-50%);
  }
  .inp-name-img{
    height: 26.25px;
    width: 26.25px;
  }
  .inp-location-img{
    height: 41.77px;
    width: 29px;
  }
  .inp-sports-img{
    height: 34px;
    width: 42.54px;
  }
  
  .btn-size {
    height: 66px;
    width: 190px;
  }
  </style>
  