# Ryani-Dewitri
Hallo ! Saya Ryani Dewitri Soumena
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alex Pratama - Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <h1>Alex Pratama</h1>
      <ul>
        <li><a href="#about">Tentang</a></li>
        <li><a href="#projects">Proyek</a></li>
        <li><a href="#contact">Kontak</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <img src="assets/profile.jpg" alt="Foto Alex" class="profile-img" />
    <h2>Front-End Developer</h2>
    <p>Membangun website modern yang responsif dan ramah pengguna.</p>
  </section>

  <section id="about" class="section">
    <h2>Tentang Saya</h2>
    <p>
      Saya adalah front-end developer yang berdedikasi, berpengalaman dalam HTML, CSS, JavaScript, dan React. Saya sangat tertarik pada UI/UX dan senang membangun antarmuka yang elegan dan fungsional.
    </p>
  </section>

  <section id="projects" class="section">
    <h2>Proyek</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>Website pribadi untuk menampilkan karya dan informasi profesional.</p>
    </div>
    <div class="project">
      <h3>Dashboard Admin</h3>
      <p>Dashboard interaktif dengan grafik dan manajemen data untuk klien retail.</p>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Kontak</h2>
    <p>Email: alex.pratama@example.com</p>
    <p>LinkedIn: linkedin.com/in/alexpratama</p>
    <p>GitHub: github.com/alexpratama</p>
  </section>

  <footer>
    <p>&copy; 2025 Alex Pratama</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  line-height: 1.6;
  background: #ffffff;
  color: #333;
}

header {
  background: #007acc;
  color: white;
  padding: 1em 0;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

nav h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 2em;
  background: #f4f4f4;
}

.profile-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
}

.section {
  padding: 2em;
  max-width: 800px;
  margin: auto;
}

.project {
  background: #eef;
  padding: 1em;
  margin-bottom: 1em;
  border-radius: 8px;
}

footer {
  text-align: center;
  padding: 1em;
  background: #007acc;
  color: white;
}
