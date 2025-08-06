<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anjali Online Book Store</title>
  <style>
    /* CSS Styles */
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      color: #fff;
    }

    .background {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      background-size: 400% 400%;
      animation: gradientFlow 10s ease infinite;
      min-height: 100vh;
    }

    @keyframes gradientFlow {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    header {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 30px;
      text-align: center;
    }

    .intro-img, .about-img {
      width: 60%;
      border-radius: 12px;
      margin-top: 20px;
      box-shadow: 0 0 15px #000;
    }

    .book-grid {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .book-card {
      background-color: rgba(255, 255, 255, 0.1);
      padding: 15px;
      border-radius: 10px;
      width: 220px;
      transition: transform 0.3s;
    }

    .book-card:hover {
      transform: scale(1.05);
    }

    .book-card img {
      width: 100%;
      border-radius: 8px;
    }

    .contact-form form {
      background-color: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 10px;
      display: inline-block;
      text-align: left;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 8px;
      margin: 8px 0;
      border: none;
      border-radius: 6px;
    }

    .contact-form button {
      padding: 10px 20px;
      border: none;
      background-color: #28a745;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: rgba(0, 0, 0, 0.6);
    }
  </style>
</head>
<body class="background">
  <!-- Header -->
  <header>
    <h1>📚 Anjali Online Book Store</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#books">Books</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Home Section -->
  <main id="home">
    <section class="intro">
      <h2>Welcome to Anjali Online Book Store</h2>
      <p>Explore a wide range of books in various genres. Affordable prices, quality reads, and an easy-to-use platform just for you.</p>
      <img src="https://cdn.pixabay.com/photo/2015/09/05/21/51/reading-925589_960_720.jpg" alt="Bookshelf" class="intro-img">
    </section>
  </main>

  <!-- Books Section -->
  <main id="books">
    <h2>Our Book Collection</h2>
    <div class="book-grid">
      <div class="book-card">
        <img src="https://covers.openlibrary.org/b/id/10567809-L.jpg" alt="Wings of Fire">
        <h3>Wings of Fire</h3>
        <p>Price: ₹299</p>
      </div>
      <div class="book-card">
        <img src="https://covers.openlibrary.org/b/id/8369256-L.jpg" alt="The Alchemist">
        <h3>The Alchemist</h3>
        <p>Price: ₹399</p>
      </div>
      <div class="book-card">
        <img src="https://covers.openlibrary.org/b/id/10583465-L.jpg" alt="Think and Grow Rich">
        <h3>Think and Grow Rich</h3>
        <p>Price: ₹199</p>
      </div>
    </div>
  </main>

  <!-- About Section -->
  <main id="about">
    <h2>Who We Are</h2>
    <p>Anjali Online Book Store is dedicated to bringing you the best books from every genre. We believe in making knowledge accessible and enjoyable.</p>
    <img src="https://cdn.pixabay.com/photo/2016/11/29/09/08/adult-1867665_960_720.jpg" alt="Reading" class="about-img">
  </main>

  <!-- Contact Section -->
  <main id="contact" class="contact-form">
    <h2>Get in Touch</h2>
    <p><strong>📞 Contact Number:</strong> <a href="tel:6307775462" style="color: #00ffcc;">6307775462</a></p>
    <form onsubmit="alert('Thanks for contacting us!'); return false;">
      <label>Name:</label>
      <input type="text" required><br>
      <label>Email:</label>
      <input type="email" required><br>
      <label>Message:</label>
      <textarea required></textarea><br>
      <button type="submit">Send Message</button>
    </form>
  </main>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Anjali Online Book Store</p>
  </footer>

  <script>
    // JavaScript (for demonstration purposes, you can add more interactivity)
    console.log('Anjali Online Book Store Loaded!');
  </script>
</body>
</html>
