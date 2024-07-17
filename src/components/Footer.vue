<template>
    <footer class="footer mt-5 py-5 bg-dark text-white w-100 position-relative">
      <div class="subscribe-container">
        <div class="w-100">
          <div class="form-group d-flex justify-content-between">
            <input type="email" class="form-control" placeholder="Your Mail" />
            <button type="submit" class="btn btn-danger">Subscribe</button>
          </div>
        </div>
      </div>
  
      <div class="container w-100">
        <div class="row">
          <div class="col-md-3 mb-3">
            <h5>Khelboo.com</h5>
            <p>
              Lorem ipsum dolor sit amet, consectetur etur adipiscing elit.
              Ullamcorper purus eleife
            </p>
            <div class="d-flex align-items-center">
              <img
                src="../assets/images/logo2.png"
                alt="Khelboo Logo"
                class="img-fluid"
              />
              <p class="footer-logo-txt">Khelboo.com</p>
            </div>
          </div>
          <div class="col-md-3 mb-3">
            <h5>Resources</h5>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">Services</a></li>
              <li><a href="#" class="text-white">Pricing</a></li>
              <li><a href="#" class="text-white">Testimonials</a></li>
              <li><a href="#" class="text-white">Blog</a></li>
            </ul>
          </div>
          <div class="col-md-3 mb-3">
            <h5>Important links</h5>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">Terms of Services</a></li>
              <li><a href="#" class="text-white">Privacy Policy</a></li>
              <li><a href="#" class="text-white">Cookie Policy</a></li>
              <li><a href="#" class="text-white">Contact us</a></li>
            </ul>
          </div>
          <div class="col-md-3 mb-3">
            <h5>Our Social Links</h5>
            <ul class="list-inline">
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-instagram text-white"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-linkedin text-white"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-facebook-f text-white"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-twitter text-white"></i></a>
              </li>
              <li class="list-inline-item">
                <a href="#"><i class="fab fa-youtube text-white"></i></a>
              </li>
            </ul>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col text-center">
            <p class="mb-0">&copy; 2024 Khelboo.com All Rights Reserved.</p>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <script setup></script>
  
  <style scoped>
  @import url("https://fonts.googleapis.com/css2?family=Racing+Sans+One&display=swap");
  .footer {
    background-color: #222;
    padding: 30px 0;
    color: #fff;
  }
  .h{
    width: 100!important;
  }
  .subscribe-container {
    position: absolute;
    top: -30px;
    left: 50%;
    transform: translateX(-50%);
    width: 708px;
    background: #f8f9fa;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 10px 20px;
  }
  .footer-logo-txt {
    font-family: "Racing Sans One";
    font-size: 30px !important;
    margin: 0px;
    margin-left: 11px;
  }
  
  .footer h5 {
    font-size: 16px;
    margin-bottom: 20px;
  }
  
  .footer p {
    font-size: 14px;
  }
  
  .footer a {
    color: #fff;
    text-decoration: none;
  }
  
  .footer a:hover {
    text-decoration: underline;
  }
  
  .footer .list-unstyled {
    padding-left: 0;
  }
  
  .footer .list-inline {
    padding-left: 0;
    margin-bottom: 0;
  }
  
  .footer .list-inline-item {
    margin-right: 10px;
  }
  
  .footer .form-inline .form-control {
    border-radius: 0;
  }
  
  .footer .form-inline .btn {
    border-radius: 0;
  }
  
  .footer .form-inline .btn-danger {
    background-color: #dc3545;
    border-color: #dc3545;
  }
  
  .footer .form-inline .btn-danger:hover {
    background-color: #c82333;
    border-color: #bd2130;
  }
  
  .footer .img-fluid {
    max-width: 50px;
    margin-top: 10px;
  }
  </style>
  