<template>
    <nav class="navbar navbar-expand-lg" :style="navbarStyle">
      <a class="navbar-brand text-white" href="#">
        <img src="../assets/images/Logo.png" class="navbar-logo" alt="Logo">
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="home-nav text-white" href="#">Home</a></li>
          <li class="nav-item"><a class="common-nav text-white" href="#">Book a Venue</a></li>
          <li class="nav-item"><a class="common-nav  text-white" href="#">Turfs</a></li>
          <li class="nav-item"><a class="common-nav  text-white" href="#">Tournaments</a></li>
          <li class="nav-item"><a class="common-nav  text-white" href="#">About Us</a></li>
          <li class="nav-item"><a class="common-nav  text-white" href="#">Contact Us</a></li>
        </ul>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item"><a class="nav-link text-white" href="#">Login</a></li>
          <li class="nav-item"><a class="nav-link btn btn-primary" href="#">Signup</a></li>
        </ul>
      </div>
    </nav>
  </template>
  
  <script setup>
  const navbarStyle = {
    background: 'linear-gradient(174.12deg, #DD0007 4.67%, #9F0C10 95.34%)',
    height: '88px'
  };
  </script>
  
  <style scoped>
 

  .navbar {
    color: white;
  }
  .nav-item{
    margin-left: 42px;
  }
  .home-nav{
    color: white;
    text-decoration: none;
    font-family: 'Poppins';
    font-size: 16px;
    font-weight: 600;
    line-height: 24px;
    text-align: center; 
  }
  .common-nav {
    color: white;
    text-decoration: none;
    font-family: 'Poppins';
    font-size: 16px;
    font-weight:100;
    line-height: 24px;
    text-align: center; 
  }
  
  .navbar-logo {
    width: 122px;
    height: 88px;
    margin-left: 117px;
  }
  
  .nav-link {
    color: white !important;
    font-family: 'Poppins', sans-serif;
    font-size: 16px;
    font-weight: 600;
    line-height: 24px;
    text-align: center; 
  }
  
  .nav-link.btn {
    background-color: white;
    color: rgba(194, 11, 17, 1) !important;
    font-family: 'Poppins', sans-serif;
    font-size: 16px;
    font-weight: 600;
    line-height: 24px;
    text-align: center; 
  }
  
  .navbar-nav {
    display: flex;
    align-items: center; 
    justify-content: center; 
    flex-grow: 1; 
  }

  </style>
  