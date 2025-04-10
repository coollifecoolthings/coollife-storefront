<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cool Life Cool Things</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 1em;
      text-align: center;
    }
    main {
      padding: 2em;
    }
    .product {
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 1em;
      margin-bottom: 1em;
      background-color: #fff;
    }
    .product img {
      max-width: 100%;
      height: auto;
    }
    .product h2 {
      margin-top: 0;
    }
    .contact-form {
      margin-top: 2em;
      padding: 1em;
      background-color: #fff;
      border-radius: 5px;
    }
    .contact-form label {
      display: block;
      margin-top: 1em;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.5em;
      margin-top: 0.5em;
    }
    .contact-form button {
      margin-top: 1em;
      padding: 0.7em 1.5em;
      background-color: #333;
      color: #fff;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Cool Life Cool Things</h1>
    <p>Your destination for stylish couches and more!</p>
  </header>
  <main>
    <section class="product">
      <h2>Modern Sofa</h2>
      <img src="https://via.placeholder.com/600x400" alt="Modern Sofa">
      <p>Comfortable and stylish modern sofa perfect for any living room.</p>
      <p><strong>Price:</strong> $499</p>
      <!-- Placeholder for payment integration -->
      <button>Buy Now</button>
    </section>

    <section class="product">
      <h2>Vintage Couch</h2>
      <img src="https://via.placeholder.com/600x400" alt="Vintage Couch">
      <p>Elegant vintage couch to add a classic touch to your home.</p>
      <p><strong>Price:</strong> $399</p>
      <!-- Placeholder for payment integration -->
      <button>Buy Now</button>
    </section>

    <!-- Add more products as needed -->

    <section class="contact-form">
      <h2>Contact Us</h2>
      <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>
</body>
</html>
