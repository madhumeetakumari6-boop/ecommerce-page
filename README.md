# ecommerce-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Store</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }

    /* NAVBAR */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #2c3e50;
      padding: 15px 30px;
      color: white;
    }

    .logo {
      font-size: 22px;
      font-weight: bold;
    }

    .nav-links a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
    }

    /* HERO SECTION */
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(to right, #3498db, #8e44ad);
      color: white;
    }

    .hero h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
    }

    /* BOOK GRID */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 30px;
    }

    .book-card {
      background: white;
      width: 220px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      transition: 0.3s;
    }

    .book-card:hover {
      transform: scale(1.05);
    }

    .book-card img {
      width: 100%;
      height: 280px;
      object-fit: cover;
    }

    .book-card h3 {
      margin: 10px 0 5px;
    }

    .book-card p {
      color: gray;
      margin: 0 0 10px;
    }

    .btn {
      display: inline-block;
      margin-bottom: 15px;
      padding: 8px 15px;
      background: #27ae60;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    .btn:hover {
      background: #219150;
    }

    /* FOOTER */
    .footer {
      text-align: center;
      padding: 20px;
      background: #2c3e50;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <div class="navbar">
    <div class="logo">📚 BookStore</div>
    <div class="nav-links">
      <a href="#">Home</a>
      <a href="#">Books</a>
      <a href="#">Offers</a>
      <a href="#">Contact</a>
    </div>
  </div>

  <!-- HERO -->
  <div class="hero">
    <h1>Welcome to Online Book Store</h1>
    <p>Find your favorite books at best prices</p>
  </div>

  <!-- BOOK LIST -->
  <div class="container">

    <div class="book-card">
      <img src="https://images.unsplash.com/photo-1544947950-fa07a98d237f" alt="Book">
      <h3>Rich Dad Poor Dad</h3>
      <p>Finance Book</p>
      <a class="btn" href="#">Buy Now</a>
    </div>
<div class="book-card">
      <img src="C:\Users\madhumeeta kumari\Desktop\download.jpg" alt="Book">
      <h3>Premchand</h3>
      <p> Hindi Story</p>
      <a class="btn" href="#">Buy Now</a>
    </div>


    <div class="book-card">
      <img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f" alt="Book">
      <h3>Atomic Habits</h3>
      <p>Self Improvement</p>
      <a class="btn" href="#">Buy Now</a>
    </div>

    <div class="book-card">
      <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794" alt="Book">
      <h3>Harry Potter</h3>
      <p>Fantasy Novel</p>
      <a class="btn" href="#">Buy Now</a>
    </div>
  <div class="book-card">
      <img src="C:\Users\madhumeeta kumari\Desktop\WhatsApp-Image-2026-02-07-at-6.37.24-PM.jpeg" alt="Book">
      <h3>English book</h3>
      <p>Iswaran the story teller </p>
      <a class="btn" href="#">Buy Now</a>
    </div>
  

    <div class="book-card">
      <img src="https://images.unsplash.com/photo-1532012197267-da84d127e765" alt="Book">
      <h3>The Alchemist</h3>
      <p>Inspirational</p>
      <a class="btn" href="#">Buy Now</a>
    </div>

  </div>

  <!-- FOOTER -->
  <div class="footer">
    © 2026 BookStore | Made with HTML & CSS
  </div>

</body>
</html>
