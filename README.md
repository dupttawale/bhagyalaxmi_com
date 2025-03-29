<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Duppta - Online Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #333;
      color: white;
      padding: 10px 0;
    }

    header nav ul {
      list-style-type: none;
      text-align: center;
    }

    header nav ul li {
      display: inline;
      margin-right: 20px;
    }

    header nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 18px;
    }

    section {
      padding: 20px;
      margin: 20px 0;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }

    .product {
      background-color: white;
      padding: 10px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
    }

    .product img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to Duppta</h1>
<h1> bhagaya laxmi enterprisess</h1>
    <p>Your one-stop online store for beautiful dupattas.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <div class="product-grid">
      <div class="product">
        <img src="C:\Users\HELLO\Downloads\WhatsApp Image 2024-12-13 at 9.00.27 PM.jpeg"  alt="Duppta 1">
        <p>cotton</p>
        <p>price : 75</p>
      </div>
      <div class="product">
        <img src="C:\Users\HELLO\Downloads\skaf.jpg" alt="Duppta 2">
        <p>stole</p>
        <p>price : 50</p>
      </div>
      <!-- Add more products as needed -->
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>We offer a wide range of stylish and beautiful dupattas for every occasion.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <h2>9920977339</h2>
    <p>For inquiries, email us at <a href="bhagyalakshmien108@gmail.com">info : bhagyalakshmien108@gmail.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Duppta. All Rights Reserved.</p>
  </footer>

  <script>
    document.addEventListener("DOMContentLoaded", function() {
      // You can add interactivity here if needed (e.g., a product filter)
      console.log("Duppta website loaded.");
    });
  </script>
</body>
</html>
