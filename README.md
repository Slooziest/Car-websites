<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Police Fleet</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f9;
      color: #333;
    }

    .header {
      padding: 30px;
      text-align: center;
      background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("https://images.pexels.com/photos/9016330/pexels-photo-9016330.jpeg");
      background-size: cover;
      color: white;
    }

    .header h1 {
      font-size: 3em;
      font-weight: bold;
    }

    /* Top Navigation */
    .topnav {
      overflow: hidden;
      background-color: #333;
      text-align: center;
    }

    .topnav a {
      color: #f2f2f2;
      padding: 14px 20px;
      display: inline-block;
      text-decoration: none;
      font-size: 1.1em;
    }

    .topnav a:hover {
      background-color: #ddd;
      color: black;
    }

    .topnav a.active {
      background-color: #4CAF50;
      color: white;
    }

    /* Column Layout */
    .row {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin: 20px;
    }

    .leftcolumn, .rightcolumn {
      padding: 20px;
      background: white;
      border-radius: 10px;
    }

    .leftcolumn {
      flex: 3;
    }

    .rightcolumn {
      flex: 1;
    }

    /* Cards */
    .card {
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.5)), url("https://images.pexels.com/photos/9016330/pexels-photo-9016330.jpeg");
      color: white;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
    }

    /* Footer */
    .footer, .subheader {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }

    /* Responsive Layout */
    @media screen and (max-width: 768px) {
      .topnav a {
        padding: 10px;
        font-size: 1em;
      }
      .row {
        flex-direction: column;
      }
    }

    /* Button Styles */
    .btn {
      background-color: #4CAF50;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-size: 1.2em;
    }

    .btn:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <div class="header">
    <h1>Police Fleet</h1>
    <p>Nishesh Basam</p>
  </div>

  <!-- Top Navigation Bar -->
  <div class="topnav">
    <a href="#" class="active">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
    <a href="#" style="float:right">Resources</a>
  </div>

  <!-- Main Content Row -->
  <div class="row">
    <!-- Left Column -->
    <div class="leftcolumn">
      <!-- Card for Dodge Charger -->
      <div class="card">
        <h2>2023 Dodge Charger Pursuit</h2>
        <img src="https://di-uploads-development.dealerinspire.com/miamilakesautomall/uploads/2023/02/2015-Dodge-Charger-Pursuit.jpg" alt="Dodge Charger Pursuit" style="height:400px;">
        <p>Overview: The 2024 Dodge Charger Police Car is a powerful and reliable vehicle designed for law enforcement needs...</p>
        <a href="#" class="btn">Learn More</a>
      </div>

      <!-- Card for Ford Explorer -->
      <div class="card">
        <h2>2024 Ford Explorer Interceptor</h2>
        <img src="https://www.motortrend.com/files/66b5114eec112e00081b4c42/2025fordexplorerpoliceinterceptor17.jpg" alt="Ford Explorer Interceptor" style="height:370px;">
        <p>Overview: The Ford Explorer Interceptor offers a powerful 3.0-liter EcoBoost V6, producing 400 horsepower...</p>
        <a href="#" class="btn">Learn More</a>
      </div>

      <!-- Card for Chevrolet Tahoe -->
      <div class="card">
        <h2>2024 Chevrolet Tahoe</h2>
        <img src="https://img.officer.com/files/base/cygnus/ofcr/image/2020/07/16x9/2021_Chevrolet_Tahoe_Police_Pursuit_Vehicle_101.5f0caf40bd484.png" alt="Chevrolet Tahoe" style="height:330px;">
        <p>Overview: The 2024 Chevrolet Tahoe Police Pursuit Vehicle is engineered for high-speed pursuits...</p>
        <a href="#" class="btn">Learn More</a>
      </div>
    </div>

    <!-- Right Column -->
    <div class="rightcolumn">
      <!-- About Us -->
      <div class="card">
        <h2>About Us</h2>
        <img src="https://ih0.redbubble.net/image.608620423.9873/raf,360x360,075,t,fafafa:ca443f4786.jpg" alt="About Us" style="height:180px;">
        <p>Our mission is to support law enforcement agencies across America by providing high-quality police vehicles tailored to their needs...</p>
      </div>

      <!-- Popular Manufacturers -->
      <div class="card">
        <h3>Popular Manufacturers</h3>
        <a href="https://www.chevrolet.com" target="_blank">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTk1WmbBPh4r6DmzSYmc0-860W1xgFJWWSQKg&s" alt="Chevrolet" style="height:150px;">
        </a>
        <a href="https://www.dodge.com" target="_blank">
          <img src="https://seekvectors.com/files/download/Dodge-01.png" alt="Dodge" style="height:180px;">
        </a>
        <a href="https://www.ford.com" target="_blank">
          <img src="https://cdn11.bigcommerce.com/s-fg272t4iw0/images/stencil/1280x1280/products/3026/3279/C-13033__00381.1557815310.jpg?c=2" alt="Ford" style="height:180px;">
        </a>
      </div>

      <!-- Sources -->
      <div class="card">
        <h3>Sources</h3>
        <p>Information gathered from official Dodge, Ford, and Chevrolet websites.</p>
        <h3>Contact Us</h3>
        <p>1234 Law Enforcement Way<br>Justice City, CA 90210<br>USA</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <h2>Exploring Computer Science</h2>
  </div>

  <!-- Subheader -->
  <div class="subheader">
    <p>Nishesh Basam</p>
  </div>

</body>
</html>
