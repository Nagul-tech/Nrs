<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Music Studio Landing Page</title>
  <link rel="stylesheet" href="styles.css">
</head>

<style>


body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

.container {
  width: 80%;
  margin: 0 auto;
}

/* Navbar */
.navbar {
  background-color: #080101;
  padding: 10px 0;
  position: sticky;
  top: 0;
  z-index: 10;
}

.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
 
}

.navbar .logo {
  color: white;
  font-size: 24px;
  text-decoration: none;

}

.navbar .nav-links {
  list-style: none;
  display: flex;
}

.navbar .nav-links li {
  margin-left: 20px;
}

.navbar .nav-links a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

/* Hero Section */
.hero {
  background: url("https://cdn5.vectorstock.com/i/1000x1000/50/39/abstract-jazz-background-with-grand-piano-on-music-vector-4245039.jpg") no-repeat center center/cover;
  padding: 100px 0;
  text-align: center;
  color: white;
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero p {
  font-size: 24px;
  margin-bottom: 30px;
}

.hero .btn {
  background-color: #ff6347;
  color: white;
  padding: 12px 25px;
  text-decoration: none;
  font-size: 18px;
  border-radius: 5px;
}

/* About Us Section */
.about {
  padding: 50px 0;
  text-align: center;
  background-color: #f4f4f4;
  margin-top: 5px;
  
}

.about h2 {
  margin-bottom: 20px;
}

.about p {
  max-width: 800px;
  margin: 0 auto;
  font-size: 18px;
}

/* Services Section */
.services {
  padding: 50px 0;
  color:black;
  background-color: rgb(60, 127, 112);
}

.services h2 {
  text-align: center;
  margin-bottom: 40px;
  color: white;
}

.service-cards {
  display: flex;
  justify-content: space-between;
  gap: 25px;
}

.service-card {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  width: 30%;
  text-align: center;
}

.service-card h3 {
  margin-bottom: 15px;
  color: red;
}

.service-card p {
  font-size: 16px;
}

/* Contact Section */
.contact {
  padding: 50px 0;
  background-color: #072c82;
  color: white;
}

.contact h2 {
  text-align: center;
  margin-bottom: 30px;
}

form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

form label {
  margin-bottom: 10px;
  font-size: 16px;
}

form input, form textarea {
  width: 80%;
  padding: 10px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 16px;
}

form button {
  padding: 12px 20px;
  background-color: #ff6347;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 18px;
  cursor: pointer;
}

form button:hover {
  background-color: #e55347;
}

/* Footer */
.footer {
  background-color: #cadf9d;
  color: rgb(21, 15, 2);
  text-align: center;
  padding: 20px 0;
  font-size: medium;
  font-family:bold;
}


</style>

<body>

  <!-- Navigation -->
  <nav class="navbar">
    <div class="container">
      <img src="Prem logo.jpeg" width="100px, height:85px:" style="margin-right: 85px;"><br>
      <h2 style="color: white; margin-right:400px;">Prems Worth Music Studio</h2>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Welcome to Our Music Studio</h1>
      <p>Your Sound, Our Passion</p>
      <a href="#contact" class="btn">Book a Session</a>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about" class="about">
    <div class="container">
      <h2>About Us</h2>
      <p>We are a creative team of musicians and producers dedicated to bringing your sound to life. Whether you're a solo artist or a band, we offer personalized recording sessions and mixing services.</p>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <div class="container">
      <h2>Our Services</h2>
      <div class="service-cards">
        <div class="service-card">
          <img src="https://static.vecteezy.com/system/resources/thumbnails/038/964/482/small/ai-generated-modern-music-record-studio-control-desk-with-laptop-screen-showing-user-interface-of-digital-audio-workstation-software-equalizer-mixer-and-professional-equipment-photo.jpg">

          <h3>Recording</h3> 
          <p>Professional recording in a soundproof environment with high-end equipment.</p>
        </div>
        <div class="service-card">
          <img src="https://static.vecteezy.com/system/resources/thumbnails/038/964/482/small/ai-generated-modern-music-record-studio-control-desk-with-laptop-screen-showing-user-interface-of-digital-audio-workstation-software-equalizer-mixer-and-professional-equipment-photo.jpg">

          <h3>Mixing</h3> 
          <p>We bring balance and clarity to your tracks with expert mixing techniques.</p>
        </div>
        <div class="service-card">
          <img src="https://static.vecteezy.com/system/resources/thumbnails/038/964/482/small/ai-generated-modern-music-record-studio-control-desk-with-laptop-screen-showing-user-interface-of-digital-audio-workstation-software-equalizer-mixer-and-professional-equipment-photo.jpg">
          
          <h3>Mastering</h3> 
          <p>We ensure your music sounds polished and ready for release with our mastering services.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <form id="contact-form">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        
        <button type="submit" class="btn">Send Message</button>
      </form>
      <p id="form-status"></p>
    </div>
  </section>

  <footer class="footer">
    <div class="container">
      <p>Prem & Nagul</p>
      <p>Contact Num: 9347040413 & 9133748695</p>
    </div>

  </footer>

  <script>
        document.getElementById('contact-form').addEventListener('submit', function(event) {
  event.preventDefault(); // Prevent the default form submission

  let name = document.getElementById('name').value;
  let email = document.getElementById('email').value;
  let message = document.getElementById('message').value;

  if (name && email && message) {
    document.getElementById('form-status').textContent = "Thank you for reaching out! We will get back to you soon.";
    document.getElementById('form-status').style.color = "green";
    
    // Clear the form
    document.getElementById('contact-form').reset();
  } else {
    document.getElementById('form-status').textContent = "Please fill in all fields.";
    document.getElementById('form-status').style.color = "red";
  }
});
  </script>

</body>
</html>
