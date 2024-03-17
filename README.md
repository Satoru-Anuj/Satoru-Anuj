<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Educators</h1>
  </header>

  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <main>
    <section id="featuredSection">
      <h2>Welcome to Our Website!</h2>
      <p>Discover our amazing services and learn more about our organization.</p>
    </section>

    <section id="aboutSection">
      <h2>About Us</h2>
      <p>Welcome to Educators, where we are passionate about providing quality education. Our organization is dedicated to...</p>
      <!-- Add more content as needed -->

      <!-- Example: -->
      <p>Explore our website to discover the range of educational services we offer and the values that drive our commitment to excellence.</p>
    </section>

    <section id="servicesSection">
      <h2>Our Services</h2>
      <ul>
        <li>Education</li>
      </ul>
    </section>

    <section id="contactSection">
      <h2>Contact Us</h2>
      <form action="submit_form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    &copy; 2024 Educators
  </footer>

  <script src="script.js"></script>
</body>
</html>
