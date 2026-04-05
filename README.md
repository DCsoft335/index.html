<!DOCTYPE html>

<html lang="en">
<head>

  <meta charset="UTF-8">
  <title>ZenithX</title>

  <!-- Favicon -->
      
  <link rel="icon" type="image/png" href="hlogo.png">


  <!-- Bootstrap CSS -->

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">


  <!--IntroCSS-->

  <style>
.carousel-img {
  height: 500px;
  object-fit: cover;
}

body {
  background-color: black;
}


</style>

</head>

<body>


<!-- NAVBAR -->

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">


<!-- Logo -->

<a class="navbar-brand" href="index.html">
  <img src="logo.png" alt="ZenithX Logo" width="90" height="89">
</a>


<!-- TOGGLER (IMPORTANT for mobile) -->

<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent">
  <span class="navbar-toggler-icon"></span>
</button>


<!-- NAV ITEMS -->

<div class="collapse navbar-collapse" id="navbarSupportedContent">
  <ul class="navbar-nav me-auto mb-2 mb-lg-0">


    <!-- Home -->
    
  <li class="nav-item">
      <a class="nav-link active" href="index.html">Home</a>
    </li>


    <!-- About -->
    
  <li class="nav-item">
      <a class="nav-link" href="#">About Us</a>
    </li>


    <!-- Launching Vehicles -->
    
  <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">
        Launching Vehicles
      </a>
      <ul class="dropdown-menu">
        <li><a class="dropdown-item" href="#">Falcon</a></li>
        <li><a class="dropdown-item" href="#">EVORA</a></li>
        <li><a class="dropdown-item" href="#">Shuttler</a></li>
      </ul>
    </li>


    <!-- Brand -->
    
  <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">
        Brand
      </a>
      <ul class="dropdown-menu">
        <li><a class="dropdown-item" href="#">Updates</a></li>
        <li><a class="dropdown-item" href="#">Missions Done</a></li>
        <li><hr class="dropdown-divider"></li>
        <li><a class="dropdown-item" href="#">Career</a></li>
      </ul>
    </li>


    <!-- Shop -->
    
  <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">
        Shop
      </a>
      <ul class="dropdown-menu text-center">
        <li><p>Buy mockups of:</p></li>
        <li><hr class="dropdown-divider"></li>
        <li><a class="dropdown-item" href="#">Gyan AI</a></li>
        <li><a class="dropdown-item" href="#">ZenithX</a></li>
      </ul>
    </li>


    <!--Gyan Ai-->

  <li class="nav-item">
      <a class="nav-link" href="">Gyan AI</a>
    </li>


    <!-- Login -->
    
  <li class="nav-item">
      <a class="nav-link" href="#">Login</a>
    </li>


    <!-- Register -->
    
  <li class="nav-item">
      <a class="nav-link" href="#">Register</a>
    </li>

  </ul>


<!-- RIGHT SIDE NAV -->

<ul class="navbar-nav ms-auto">

  <li class="nav-item dropdown">
    <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">
      Upcoming Missions
    </a>

  <ul class="dropdown-menu dropdown-menu-end">

    
      <!-- Mars -->
  <li>
    <a class="dropdown-item d-flex align-items-center" href="mars.html">
          <img src="Mars.jpg" width="30" height="30" class="me-2 rounded">
          Mars Mission
        </a>
      </li>


      <!-- Moon -->
      
  <li>
        <a class="dropdown-item d-flex align-items-center" href="moon.html">
          <img src="moon.jpg" width="30" height="30" class="me-2 rounded">
          Moon Mission
        </a>
      </li>

  </ul>
  </li>

</ul>

  </div>
</nav>


<!-- HERO SECTION -->

<section class="text-center text-white"
  style="background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('space-bg.jpg') no-repeat center center/cover;
        height: 100vh;
        display: flex;
        align-items: center;
      justify-content: center;">


  <!-- Content -->
  
  <div class="container position-relative">
    <div class="row align-items-center">


  <!-- LEFT TEXT -->
  
  <div class="col-md-6 text-center text-md-start mb-4 mb-md-0">
    <h1 class="display-3 fw-bold">ZenithX</h1>
    <p class="lead">The future is more exciting when we explore beyond Horizon</p>

  <a href="#" class="btn btn-light me-2">Explore</a>
  <a href="#" class="btn btn-outline-light">Join</a>
  </div>


  <!-- RIGHT EARTH -->
  
  <div class="col-md-6 text-center">
    <img src="earth.gif" class="img-fluid" style="max-width: 400px;">
  </div>

</div>

  </div>
  </div>


</section>


<!--To differentiate section-->

<div class="my-5"></div>


<h2 class="text-center text-white mt-5">Our Rockets</h2>


<!--Carrousel-->

<div id="rocketCarousel" class="carousel slide" data-bs-ride="carousel">


  <!-- Indicators -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#rocketCarousel" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#rocketCarousel" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#rocketCarousel" data-bs-slide-to="2"></button>
  </div>


  <!-- Images -->
  <div class="carousel-inner">

  <div class="carousel-item active">
      <img src="rocket1.jpg" class="d-block w-100 h-10 carousel-img" alt="Falcon rocket">
      <div class="carousel-caption">
    <h3>Falcon</h3>
  <p class="small">Reusable heavy-lift rocket designed for Mars missions</p>

  </div>
    </div>

  <div class="carousel-item">
      <img src="rocket2.jpg" class="d-block w-100 carousel-img" alt="EVORA rocket">

  <div class="carousel-caption">
    <h3>EVORA</h3>
  <p class="small">Reusable light-lift rocket designed for Moon missions</p>
  </div>

  </div>

  <div class="carousel-item">
      <img src="rocket3.jpg" class="d-block w-100 carousel-img" alt="Shuttler rocket">

  <div class="carousel-caption">
    <h3>Shuttler</h3>
    <p class="small">Reusable light-lift rocket designed for satellite missions</p>

  </div>
    </div>

  </div>


  <!-- Controls -->
  
  <button class="carousel-control-prev" type="button" data-bs-target="#rocketCarousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>

  <button class="carousel-control-next" type="button" data-bs-target="#rocketCarousel" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>

</div>


<!--To differentiate section-->

<div class="my-5"></div>
<br><br><br>

  <!--Call to action-->

  <div class="container col-md-6 text-center">
    <h2>Join the Future of Space Exploration</h2>
    <p class="mt-3">Be part of the next generation of innovators.</p>
    <a href="#" class="btn btn-light mt-3">Get Started</a>
  </div>


<!--To differentiate section-->

<div class="my-5"></div>


<!--Footer-->

<footer class="text-center text-white py-3 bg-dark">
  <p>© 2026 ZenithX | All Rights Reserved</p>
</footer>


<!-- Bootstrap JS -->

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
-</html>
