<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GEOPAD</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.1rem;
      opacity: 0.9;
      max-width: 700px;
      margin: 0 auto;
    }
    .container {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 0 1.5rem;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .service-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      width: 100%;
      max-width: 350px;
      overflow: hidden;
      transition: transform 0.3s;
    }
    .service-card:hover {
      transform: translateY(-5px);
    }
    .service-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .service-card-content {
      padding: 1.5rem;
    }
    .service-card h3 {
      margin-bottom: 0.75rem;
      color: #2c3e50;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #ecf0f1;
      color: #7f8c8d;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>GEOPAD</h1>
    <p>Innovative geospatial solutions for a smarter world.</p>
  </header>

  <div class="container">
    <div class="services">
      
      <div class="service-card">
        <img src="https://picsum.photos/400/250?random=1" alt="Geospatial Mapping">
        <div class="service-card-content">
          <h3>Geospatial Mapping</h3>
          <p>High-precision mapping using satellite and drone imagery to visualize terrain, infrastructure, and environmental changes.</p>
        </div>
      </div>

      <div class="service-card">
        <img src="https://picsum.photos/400/250?random=2" alt="Data Analytics">
        <div class="service-card-content">
          <h3>Geospatial Analytics</h3>
          <p>Turn location data into actionable insights with AI-powered analysis for urban planning, logistics, and risk assessment.</p>
        </div>
      </div>

      <div class="service-card">
        <img src="https://picsum.photos/400/250?random=3" alt="Custom Solutions">
        <div class="service-card-content">
          <h3>Custom GIS Solutions</h3>
          <p>Tailored geospatial software and dashboards designed to meet your organization’s unique operational needs.</p>
        </div>
      </div>

    </div>
  </div>

  <footer>
    <p>&copy; 2025 GEOPAD. All rights reserved.</p>
  </footer>

</body>
</html>
