# matsue.gl
website trial
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matsue Holdings</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="container">
      <div class="logo">Matsue Holdings</div>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#contact">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="container">
      <h1>Empowering Your Business Through Expert Solutions</h1>
      <p>From tendering and construction to IT support and bulk buying, we’ve got you covered.</p>
      <div class="cta-buttons">
        <a href="#services" class="btn">Explore Our Services</a>
        <a href="#contact" class="btn secondary">Contact Us Today</a>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <div class="container">
      <h2>Our Services</h2>
      <div class="service-grid">
        <div class="service-card">
          <i class="icon">🏗️</i>
          <h3>Tendering & Construction</h3>
          <p>We specialize in end-to-end construction solutions, from bidding and tendering to project execution.</p>
        </div>
        <div class="service-card">
          <i class="icon">💻</i>
          <h3>IT Support & Networking</h3>
          <p>From troubleshooting computer issues to setting up robust networks, our IT experts ensure your systems run smoothly.</p>
        </div>
        <div class="service-card">
          <i class="icon">🛒</i>
          <h3>Online Bulk Buying</h3>
          <p>Save time and money with our bulk purchasing platform. We source high-quality products at competitive prices.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="about">
    <div class="container">
      <h2>About Us</h2>
      <p>At Matsue Holdings, we are committed to delivering exceptional service across multiple industries. With years of experience and a customer-first approach, we strive to exceed expectations in every project we undertake.</p>
    </div>
  </section>

  <!-- Contact Us Section -->
  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <form id="contact-form">
        <input type="text" placeholder="Full Name" required>
        <input type="email" placeholder="Email Address" required>
        <input type="tel" placeholder="Phone Number" required>
        <select>
          <option value="tendering">Tendering & Construction</option>
          <option value="it-support">IT Support & Networking</option>
          <option value="bulk-buying">Online Bulk Buying</option>
          <option value="other">Other</option>
        </select>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Submit</button>
      </form>
      <div class="contact-info">
        <p><strong>Phone:</strong> +72968254</p>
        <p><strong>Email:</strong> info@matsueholdings.com</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2023 Matsue Holdings. All Rights Reserved.</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
