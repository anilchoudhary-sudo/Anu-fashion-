<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Anil Fashion</title>
  <link rel="stylesheet" href="style.css" />
  <script defer src="script.js"></script>
</head>
<body>
  <header>
    <h1>Anil Fashion</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#collections">Collections</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Wear Your Style</h2>
    <p>Modern. Minimal. You.</p>
    <button onclick="scrollToSection('collections')">View Collections</button>
  </section>

  <section id="collections" class="gallery">
    <h2>Featured Designs</h2>
    <div class="images">
      <img src="https://via.placeholder.com/300x400?text=Outfit+1" alt="Outfit 1">
      <img src="https://via.placeholder.com/300x400?text=Outfit+2" alt="Outfit 2">
      <img src="https://via.placeholder.com/300x400?text=Outfit+3" alt="Outfit 3">
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>I am Anil, a fashion designer creating modern and comfortable clothing inspired by elegance and simplicity.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <a href="https://wa.me/919999999999" target="_blank" class="btn">📲 WhatsApp Me</a>
    <a href="https://www.instagram.com/yourhandle" target="_blank" class="btn">📸 Instagram</a>
  </section>

  <footer>
    <p>© 2025 Anil Fashion. All rights reserved.</p>
  </footer>
</body>
</html>
/* Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Poppins', sans-serif;
  background-color: #fff;
  color: #111;
}
header {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  background-color: #000;
  color: white;
}
header h1 {
  font-weight: 600;
}
nav a {
  margin: 0 10px;
  text-decoration: none;
  color: white;
}
.hero {
  text-align: center;
  padding: 100px 20px;
  background-image: url('https://via.placeholder.com/1200x600?text=Fashion+Banner');
  background-size: cover;
  background-position: center;
  color: white;
}
.hero h2 {
  font-size: 3rem;
}
.hero p {
  font-size: 1.2rem;
}
.hero button {
  margin-top: 20px;
  padding: 12px 24px;
  background-color: #fff;
  color: #000;
  border: none;
  font-weight: bold;
  cursor: pointer;
}
.gallery {
  padding: 60px 20px;
  text-align: center;
}
.gallery .images {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}
.gallery img {
  border-radius: 10px;
  max-width: 100%;
  height: auto;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
}
.about, .contact {
  padding: 60px 20px;
  text-align: center;
}
.contact .btn {
  display: inline-block;
  margin: 10px;
  padding: 12px 20px;
  background-color: black;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}
