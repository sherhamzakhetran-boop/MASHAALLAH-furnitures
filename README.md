<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MASHAALLAH FURNITURES</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f8f8f8;
      color: #333;
    }
    header {
      background-color: #2c2c2c;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 26px;
      letter-spacing: 1px;
    }
    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-size: 16px;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1615874959474-d609969a20ed') center/cover no-repeat;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }
    .hero h2 {
      font-size: 42px;
      background: rgba(0,0,0,0.6);
      padding: 20px;
      border-radius: 8px;
    }
    section {
      padding: 60px 40px;
      max-width: 1200px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card h3 {
      margin-bottom: 10px;
    }
    footer {
      background-color: #2c2c2c;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .contact {
      text-align: center;
    }
    .contact p {
      font-size: 18px;
    }
  </style>
</head>
<body>

<header>
  <h1>MASHAALLAH FURNITURES</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#services">Products</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero">
  <h2>Quality Furniture for Every Home</h2>
</div>

<section id="about">
  <h2>About Us</h2>
  <p>
    MASHAALLAH FURNITURES is dedicated to providing high-quality, durable, and stylish furniture for homes and offices. We combine craftsmanship with modern designs to bring comfort and beauty into your space.
  </p>
</section>

<section id="services">
  <h2>Our Products</h2>
  <div class="services">
    <div class="card">
      <h3>Sofas & Chairs</h3>
      <p>Comfortable and stylish seating for living rooms and offices.</p>
    </div>
    <div class="card">
      <h3>Beds & Wardrobes</h3>
      <p>Strong, elegant bedroom furniture built to last.</p>
    </div>
    <div class="card">
      <h3>Tables & Storage</h3>
      <p>Dining tables, coffee tables, and smart storage solutions.</p>
    </div>
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>📞 Phone: <a href="tel:+923337083673">+92 333 7083673</a> / <a href="tel:+923335248133">+92 333 5248133</a></p>
  <p>💬 WhatsApp: <a href="https://wa.me/923337083673">Chat on WhatsApp</a></p>
  <p>📍 Address: Kohlu Road, Barkhan, Balochistan</p>
  <p>📧 Email: <a href="mailto:sherhamzakhetran@gmail.com">sherhamzakhetran@gmail.com</a></p>
</section>

<footer>
  <p>© 2026 MASHAALLAH FURNITURES. All Rights Reserved.</p>
</footer>

</body>
</html>
