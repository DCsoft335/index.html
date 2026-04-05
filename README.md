<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ZenithX</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #111, #0a0f1c);
      color: white;
    }

    /* NAVBAR */
    .navbar {
      padding: 15px 40px;
    }

    .navbar a {
      color: white !important;
      margin-right: 15px;
    }

    /* HERO SECTION */
    .hero {
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 60px;
    }

    .left {
      max-width: 500px;
    }

    .left h1 {
      font-size: 48px;
      font-weight: 600;
    }

    .left p {
      color: #aaa;
      margin: 20px 0;
    }

    .btn-custom {
      margin-right: 10px;
      padding: 10px 20px;
      font-weight: bold;
    }

    /* RIGHT IMAGE */
    .right img {
      width: 350px;
      background: transparent;
    }

    /* RESPONSIVE */
    @media (max-width: 768px) {
      .hero {
        flex-direction: column;
        text-align: center;
      }

      .right img {
        margin-top: 20px;
        width: 250px;
      }
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg">
    <a class="navbar-brand text-white" href="#">ZenithX</a>

  <div class="ms-auto">
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Brand</a>
      <a href="#">Shop</a>
      <a href="#">Login</a>
    </div>
  </nav>

  <!-- HERO SECTION -->
  <div class="hero">
    
    <!-- LEFT SIDE -->
  <div class="left">
      <h1>ZenithX</h1>
      <p>The future is more exciting when we explore beyond the horizon.</p>
      <button class="btn btn-primary btn-custom">Explore</button>
      <button class="btn btn-outline-light btn-custom">Join</button>
    </div>

   <!-- RIGHT SIDE -->
   <div class="right">
      <img src="images/earth.png" alt="Earth">
    </div>

  </div>

</body>
</html>
