<template>
    <section class="feature-section py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-7 mb-4">
            <div class="card h-100 custom-card">
              <img src="../assets/images/team1.png" class="card-img-top" alt="Be Part of the Team">
            </div>
          </div>
          <div class="col-md-5">
            <div class="row">
              <div class="col-md-12 mb-4">
                <div class="card h-100 custom-card">
                  <img src="../assets/images/team2.png" class="card-img-top shadow" alt="Create A Team">
                  <div class="card-body shadow">
                    <p class="position img-text">Create A <br> Team</p>
                  </div>
                </div>
              </div>
              <div class="col-md-12 mb-4">
                <div class="card h-100 custom-card">
                  <img src="../assets/images/team3.png" class="card-img-top shadow" alt="Challenge A Team">
                  <div class="card-body">
                    <p class=" position img-text">Challenge A <br> Team</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>

.img-text { 
    font-family: Poppins;
    font-size: 33px;
    font-style: italic;
    font-weight: 700;
    line-height: 38px;
    text-align: left; 
}
  .card {
    border: none;
    border-radius: 15px;
    overflow: hidden;
  }
  .position{
    position: absolute;
    top:55.69px;
    left: 87px;
  }
  
  .card-img-top {
    border-radius: 15px;
  }
  
  .card-img-overlay {
    background: rgba(0, 0, 0, 0.5);
    border-radius: 15px;
  }
  
  .card-title {
    font-family: 'Poppins', sans-serif;
    font-size: 24px;
    font-weight: 600;
    text-align: center;
    color: #fff;
  }
  
  .custom-card img {
    object-fit: cover;
    height: 100%;
  }
  
  .card-body {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .card-body .card-title {
    font-size: 20px;
    color: #000;
  }
  </style>
  