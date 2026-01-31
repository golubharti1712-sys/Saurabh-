<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Saurabh Enterprises - Mobile Repair & Showroom</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #f5f5f5;
      color: #222;
    }
    header {
      background-color: #111;
      color: gold;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    header p {
      margin: 5px 0 0;
      font-weight: 500;
    }
    .contact-btns {
      margin-top: 10px;
    }
    .contact-btns a {
      text-decoration: none;
      color: #fff;
      background-color: gold;
      padding: 10px 20px;
      margin: 5px;
      display: inline-block;
      border-radius: 5px;
      font-weight: 600;
      transition: 0.3s;
    }
    .contact-btns a:hover {
      background-color: #c39f00;
    }
    section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      color: #111;
      text-align: center;
      margin-bottom: 30px;
    }
    .services, .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .service-box, .gallery-box {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      text-align: center;
    }
    .service-box h3 {
      margin-bottom: 10px;
      color: #111;
    }
    .service-box p {
      font-size: 0.95em;
    }
    .gallery-box img {
      width: 100%;
      border-radius: 10px;
    }
    .location {
      text-align: center;
      margin-top: 30px;
    }
    .location iframe {
      width: 100%;
      height: 300px;
      border: 0;
      border-radius: 10px;
    }
    footer {
      background: #111;
      color: gold;
      text-align: center;
      padding: 20px;
    }
    @media(max-width:600px){
      header h1 { font-size: 1.5em; }
      .contact-btns a { padding: 8px 15px; font-size: 0.9em; }
    }
  </style>
</head>
<body>

<header>
  <h1>Saurabh Enterprises</h1>
  <p>Multi Brand Mobile Showroom & Repair Since 2005</p>
  <div class="contact-btns">
    <a href="tel:+919839485908">Call Now</a>
    <a href="https://wa.me/919839485908" target="_blank">WhatsApp</a>
  </div>
</header>

<section>
  <h2>Our Services</h2>
  <div class="services">
    <div class="service-box">
      <h3>Mobile Repair</h3>
      <p>Screen, battery, software, charging port, camera repair & more.</p>
    </div>
    <div class="service-box">
      <h3>Recharge & SIM Services</h3>
      <p>Mobile recharge, SIM activation, balance check & top-up services.</p>
    </div>
    <div class="service-box">
      <h3>Accessories</h3>
      <p>Phone cases, chargers, earphones, screen protectors & more.</p>
    </div>
    <div class="service-box">
      <h3>New Mobile Sale</h3>
      <p>All major brands with EMI & exchange options available.</p>
    </div>
  </div>
</section>

<section>
  <h2>Gallery</h2>
  <div class="gallery">
    <div class="gallery-box">
      <img src="https://via.placeholder.com/400x300?text=Mobile+1" alt="Mobile 1">
    </div>
    <div class="gallery-box">
      <img src="https://via.placeholder.com/400x300?text=Mobile+2" alt="Mobile 2">
    </div>
    <div class="gallery-box">
      <img src="https://via.placeholder.com/400x300?text=Mobile+3" alt="Mobile 3">
    </div>
    <div class="gallery-box">
      <img src="https://via.placeholder.com/400x300?text=Mobile+4" alt="Mobile 4">
    </div>
  </div>
</section>

<section class="location">
  <h2>Our Location</h2>
  <p>Jaycees Crossing, Opposite Hindustan Times, Jaunpur, Uttar Pradesh 222002, India</p>
  <iframe src="https://www.google.com/maps?q=Jaycees+Crossing,+Opposite+Hindustan+Times,+Jaunpur,+Uttar+Pradesh+222002,+India&output=embed"></iframe>
</section>

<footer>
  &copy; 2026 Saurabh Enterprises | All Rights Reserved
</footer>

</body>
</html>