<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Oxygen Gym | Premium Fitness Center</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins',sans-serif;
    }

    body{
      background:#0d0d0d;
      color:#fff;
    }

    header{
      min-height:100vh;
      background:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
      url('https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b');
      background-size:cover;
      background-position:center;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      padding:20px;
    }

    header h1{
      font-size:3rem;
      color:#00ffcc;
      letter-spacing:2px;
    }

    header p{
      margin:15px 0;
      font-size:1.1rem;
      color:#ddd;
    }

    .btns a{
      display:inline-block;
      margin:10px;
      padding:12px 28px;
      border-radius:30px;
      text-decoration:none;
      font-weight:600;
      transition:.3s;
    }

    .call{
      background:#00ffcc;
      color:#000;
    }

    .whatsapp{
      border:2px solid #00ffcc;
      color:#00ffcc;
    }

    .btns a:hover{
      transform:scale(1.05);
    }

    section{
      padding:70px 20px;
      max-width:1200px;
      margin:auto;
    }

    section h2{
      text-align:center;
      margin-bottom:50px;
      font-size:2.2rem;
      color:#00ffcc;
    }

    .services{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
    }

    .card{
      background:#151515;
      padding:30px;
      border-radius:15px;
      text-align:center;
      box-shadow:0 0 20px rgba(0,255,204,.15);
    }

    .card h3{
      margin-bottom:10px;
      color:#00ffcc;
    }

    .card p{
      color:#ccc;
      font-size:.95rem;
    }

    .about{
      text-align:center;
      color:#ccc;
      max-width:900px;
      margin:auto;
      font-size:1.05rem;
      line-height:1.8;
    }

    .map iframe{
      width:100%;
      height:350px;
      border:0;
      border-radius:15px;
    }

    footer{
      background:#000;
      text-align:center;
      padding:25px;
      color:#aaa;
      font-size:.9rem;
    }

    footer span{
      color:#00ffcc;
    }

    @media(max-width:600px){
      header h1{font-size:2.2rem;}
    }
  </style>
</head>
<body>

<!-- HERO -->
<header>
  <div>
    <h1>OXYGEN GYM</h1>
    <p>Build Your Body • Boost Your Strength • Transform Your Life</p>

    <div class="btns">
      <a href="tel:+919120540640" class="call">Call Now</a>
      <a href="https://wa.me/919120540640" target="_blank" class="whatsapp">WhatsApp</a>
    </div>
  </div>
</header>

<!-- SERVICES -->
<section>
  <h2>Our Programs</h2>

  <div class="services">
    <div class="card">
      <h3>Weight Training</h3>
      <p>Advanced equipment & expert guidance for muscle growth.</p>
    </div>

    <div class="card">
      <h3>Cardio Training</h3>
      <p>Modern machines to improve stamina & heart health.</p>
    </div>

    <div class="card">
      <h3>Personal Training</h3>
      <p>One-to-one training for faster and safer results.</p>
    </div>

    <div class="card">
      <h3>Fat Loss Program</h3>
      <p>Customized workouts & diet guidance for weight loss.</p>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section>
  <h2>Why Choose Oxygen Gym?</h2>
  <p class="about">
    Oxygen Gym is a premium fitness center focused on strength, stamina,
    and total body transformation. Our professional trainers, modern
    equipment, and disciplined environment help you achieve real results.
    Join us and become the best version of yourself.
  </p>
</section>

<!-- LOCATION -->
<section class="map">
  <h2>Visit Us</h2>
  <iframe 
    src="https://www.google.com/maps?q=Oxygen+Gym&output=embed">
  </iframe>
</section>

<!-- FOOTER -->
<footer>
  © 2026 <span>Oxygen Gym</span> | All Rights Reserved  
  <br> Contact: +91 91205 40640
</footer>

</body>
</html>