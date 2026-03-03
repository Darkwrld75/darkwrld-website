# darkwrld-website
Artist website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- SEO -->
  <title>Dark Wrld | Official Website</title>
  <meta name="description" content="Official website of Dark Wrld. Stream music, explore latest releases, join the movement and stay updated.">
  <meta name="keywords" content="Dark Wrld, Dark Wrld music, rapper, new music, Spotify artist">
  <meta name="author" content="Dark Wrld">

  <!-- Open Graph (for sharing on social media) -->
  <meta property="og:title" content="Dark Wrld | Official Website">
  <meta property="og:description" content="Stream the latest music from Dark Wrld.">
  <meta property="og:type" content="website">

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0c0c0c;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: black;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 999;
    }

    header a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
    }

    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(to bottom, #000000, #111111);
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 70px;
      margin: 0;
      letter-spacing: 2px;
    }

    .hero p {
      margin-top: 15px;
      font-size: 18px;
      opacity: 0.8;
    }

    .button {
      margin-top: 25px;
      padding: 14px 35px;
      background: #1db954;
      border-radius: 50px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      transition: 0.3s ease;
    }

    .button:hover {
      opacity: 0.8;
    }

    .section {
      padding: 80px 40px;
      text-align: center;
    }

    iframe {
      width: 100%;
      max-width: 700px;
      height: 380px;
      border-radius: 12px;
      border: none;
      margin-top: 20px;
    }

    .newsletter input {
      padding: 12px;
      width: 250px;
      border-radius: 30px;
      border: none;
      margin-right: 10px;
    }

    .newsletter button {
      padding: 12px 25px;
      border-radius: 30px;
      border: none;
      background: #1db954;
      color: white;
      font-weight: bold;
    }

    footer {
      background: #111;
      padding: 30px;
      text-align: center;
      font-size: 14px;
      opacity: 0.7;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 45px;
      }
    }
  </style>
</head>

<body>

<header>
  <div><strong>Dark Wrld</strong></div>
  <nav>
    <a href="#music">Music</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Dark Wrld</h1>
  <p>Entering a new dimension of sound.</p>
  <a href="#music" class="button">Stream Now</a>
</section>

<section class="section" id="music">
  <h2>Latest Releases</h2>
  <iframe src="https://open.spotify.com/embed/artist/7iWv8ZvaBUkslCwhLUbQl2"
    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture">
  </iframe>
</section>

<section class="section" id="about">
  <h2>About Dark Wrld</h2>
  <p>
    Dark Wrld is an emerging artist pushing creative boundaries with atmospheric beats,
    emotional storytelling, and powerful energy. Each release reflects depth, ambition,
    and a new sonic experience.
  </p>
</section>

<section class="section newsletter" id="contact">
  <h2>Join The Wrld</h2>
  <p>Subscribe for updates on new music and releases.</p>
  <form action="https://formspree.io/f/YOUR_ID" method="POST">
    <input type="email" name="email" placeholder="Enter your email" required>
    <button type="submit">Subscribe</button>
  </form>
</section>

<footer>
  © 2026 Dark Wrld | All Rights Reserved
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Music | Dark Wrld</title>
  <meta name="description" content="Stream the latest music from Dark Wrld. Explore new releases and featured tracks.">
  <meta name="keywords" content="Dark Wrld music, Dark Wrld songs, new releases, Spotify artist">
  <meta name="author" content="Dark Wrld">

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0c0c0c;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: black;
      position: fixed;
      width: 100%;
      top: 0;
    }

    header a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
    }

    .hero {
      padding-top: 120px;
      text-align: center;
      padding-bottom: 60px;
      background: linear-gradient(to bottom, #000000, #111111);
    }

    .hero h1 {
      font-size: 55px;
      margin-bottom: 10px;
    }

    .section {
      padding: 60px 40px;
      text-align: center;
    }

    iframe {
      width: 100%;
      max-width: 750px;
      height: 380px;
      border-radius: 12px;
      border: none;
      margin-top: 20px;
    }

    .release-card {
      background: #151515;
      padding: 20px;
      margin: 20px auto;
      max-width: 600px;
      border-radius: 12px;
    }

    .button {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 30px;
      background: #1db954;
      border-radius: 40px;
      text-decoration: none;
      color: white;
      font-weight: bold;
    }

    footer {
      background: #111;
      padding: 30px;
      text-align: center;
      font-size: 14px;
      opacity: 0.7;
      margin-top: 60px;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 38px;
      }
    }
  </style>
</head>

<body>

<header>
  <div><strong>Dark Wrld</strong></div>
  <nav>
    <a href="index.html">Home</a>
    <a href="music.html">Music</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Music</h1>
  <p>Explore the sound of Dark Wrld</p>
</section>

<section class="section">
  <h2>Stream on Spotify</h2>

  <iframe src="https://open.spotify.com/embed/artist/7iWv8ZvaBUkslCwhLUbQl2"
    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture">
  </iframe>
</section>

<section class="section">
  <h2>Featured Releases</h2>

  <div class="release-card">
    <h3>Latest Single</h3>
    <p>Experience the newest sound from Dark Wrld.</p>
    <a href="https://open.spotify.com/artist/7iWv8ZvaBUkslCwhLUbQl2" class="button" target="_blank">
      Listen Now
    </a>
  </div>

  <div class="release-card">
    <h3>Previous Releases</h3>
    <p>Explore past tracks and creative evolution.</p>
    <a href="https://open.spotify.com/artist/7iWv8ZvaBUkslCwhLUbQl2" class="button" target="_blank">
      View Catalog
    </a>
  </div>

</section>

<footer>
  © 2026 Dark Wrld | All Rights Reserved
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Playlists | Dark Wrld</title>
  <meta name="description" content="Explore curated playlists featuring Dark Wrld and inspired sounds.">
  <meta name="keywords" content="Dark Wrld playlists, Spotify playlists, curated music">
  <meta name="author" content="Dark Wrld">

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0c0c0c;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: black;
      position: fixed;
      width: 100%;
      top: 0;
    }

    header a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
    }

    .hero {
      padding-top: 120px;
      padding-bottom: 60px;
      text-align: center;
      background: linear-gradient(to bottom, #000000, #111111);
    }

    .hero h1 {
      font-size: 50px;
      margin-bottom: 10px;
    }

    .section {
      padding: 60px 40px;
      text-align: center;
    }

    .playlist-card {
      background: #151515;
      padding: 25px;
      margin: 30px auto;
      max-width: 800px;
      border-radius: 15px;
    }

    iframe {
      width: 100%;
      height: 380px;
      border-radius: 12px;
      border: none;
      margin-top: 20px;
    }

    .button {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 30px;
      background: #1db954;
      border-radius: 40px;
      text-decoration: none;
      color: white;
      font-weight: bold;
    }

    footer {
      background: #111;
      padding: 30px;
      text-align: center;
      font-size: 14px;
      opacity: 0.7;
      margin-top: 60px;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }
    }
  </style>
</head>

<body>

<header>
  <div><strong>Dark Wrld</strong></div>
  <nav>
    <a href="index.html">Home</a>
    <a href="music.html">Music</a>
    <a href="playlists.html">Playlists</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Playlists</h1>
  <p>Curated sounds & featured vibes</p>
</section>

<section class="section">

  <div class="playlist-card">
    <h2>Official Dark Wrld Playlist</h2>
    <p>All releases and exclusive vibes in one place.</p>

    <!-- Replace PLAYLIST_ID with your actual playlist ID -->
    <iframe src="https://open.spotify.com/embed/playlist/PLAYLIST_ID"
      allow="autoplay; clipboard-write; encrypted-media; picture-in-picture">
    </iframe>

    <a href="https://open.spotify.com/artist/7iWv8ZvaBUkslCwhLUbQl2" 
       target="_blank" 
       class="button">
       Open on Spotify
    </a>
  </div>

  <div class="playlist-card">
    <h2>Inspired By Dark Wrld</h2>
    <p>Artists and tracks that inspire the sound.</p>

    <iframe src="https://open.spotify.com/embed/playlist/PLAYLIST_ID"
      allow="autoplay; clipboard-write; encrypted-media; picture-in-picture">
    </iframe>

    <a href="https://open.spotify.com/artist/7iWv8ZvaBUkslCwhLUbQl2" 
       target="_blank" 
       class="button">
       Discover More
    </a>
  </div>

</section>

<footer>
  © 2026 Dark Wrld | All Rights Reserved
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Merch | Dark Wrld</title>
  <meta name="description" content="Shop official Dark Wrld merchandise: hoodies, tees, and limited edition apparel.">
  <meta name="keywords" content="Dark Wrld merch, Dark Wrld hoodie, t-shirt, clothing, shop">
  <meta name="author" content="Dark Wrld">

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0c0c0c;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: black;
      position: fixed;
      width: 100%;
      top: 0;
    }

    header a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
    }

    .hero {
      padding-top: 120px;
      padding-bottom: 60px;
      text-align: center;
      background: linear-gradient(to bottom, #000000, #111111);
    }

    .hero h1 {
      font-size: 50px;
      margin-bottom: 10px;
    }

    .section {
      padding: 60px 40px;
      text-align: center;
    }

    .merch-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 40px;
    }

    .merch-card {
      background: #151515;
      padding: 20px;
      width: 250px;
      border-radius: 12px;
      text-align: center;
    }

    .merch-card img {
      width: 100%;
      border-radius: 12px;
    }

    .merch-card h3 {
      margin: 15px 0 5px 0;
    }

    .merch-card p {
      margin: 5px 0 15px 0;
      opacity: 0.8;
    }

    .button {
      display: inline-block;
      padding: 12px 25px;
      background: #1db954;
      border-radius: 40px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      transition: 0.3s ease;
    }

    .button:hover {
      opacity: 0.8;
    }

    footer {
      background: #111;
      padding: 30px;
      text-align: center;
      font-size: 14px;
      opacity: 0.7;
      margin-top: 60px;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }
      .merch-grid {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>

<body>

<header>
  <div><strong>Dark Wrld</strong></div>
  <nav>
    <a href="index.html">Home</a>
    <a href="music.html">Music</a>
    <a href="playlists.html">Playlists</a>
    <a href="merch.html">Merch</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Official Merch</h1>
  <p>Shop exclusive Dark Wrld apparel</p>
</section>

<section class="section">
  <h2>Featured Items</h2>

  <div class="merch-grid">

    <div class="merch-card">
      <img src="images/hoodie.jpg" alt="Dark Wrld Hoodie">
      <h3>Dark Wrld Hoodie</h3>
      <p>Cozy black hoodie with signature Dark Wrld logo.</p>
      <a href="#" class="button">Buy Now</a>
    </div>

    <div class="merch-card">
      <img src="images/tshirt.jpg" alt="Dark Wrld Tee">
      <h3>Dark Wrld Tee</h3>
      <p>Limited edition t-shirt with custom design.</p>
      <a href="#" class="button">Buy Now</a>
    </div>

    <div class="merch-card">
      <img src="images/cap.jpg" alt="Dark Wrld Cap">
      <h3>Dark Wrld Cap</h3>
      <p>Stylish cap to complete your Dark Wrld look.</p>
      <a href="#" class="button">Buy Now</a>
    </div>

  </div>

</section>

<footer>
  © 2026 Dark Wrld | All Rights Reserved
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Blog | Dark Wrld</title>
  <meta name="description" content="Read the latest news, updates, and behind-the-scenes stories from Dark Wrld.">
  <meta name="keywords" content="Dark Wrld blog, news, updates, music, behind the scenes">
  <meta name="author" content="Dark Wrld">

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0c0c0c;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: black;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 999;
    }

    header a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
    }

    .hero {
      padding-top: 120px;
      padding-bottom: 60px;
      text-align: center;
      background: linear-gradient(to bottom, #000000, #111111);
    }

    .hero h1 {
      font-size: 50px;
      margin-bottom: 10px;
    }

    .section {
      padding: 60px 40px;
      text-align: center;
    }

    .blog-post {
      background: #151515;
      padding: 25px;
      margin: 25px auto;
      max-width: 800px;
      border-radius: 12px;
      text-align: left;
    }

    .blog-post h2 {
      margin-bottom: 10px;
    }

    .blog-post p {
      opacity: 0.85;
    }

    .button {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 30px;
      background: #1db954;
      border-radius: 40px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      transition: 0.3s ease;
    }

    .button:hover {
      opacity: 0.8;
    }

    footer {
      background: #111;
      padding: 30px;
      text-align: center;
      font-size: 14px;
      opacity: 0.7;
      margin-top: 60px;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }
    }
  </style>
</head>

<body>

<header>
  <div><strong>Dark Wrld</strong></div>
  <nav>
    <a href="index.html">Home</a>
    <a href="music.html">Music</a>
    <a href="playlists.html">Playlists</a>
    <a href="merch.html">Merch</a>
    <a href="blog.html">Blog</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Blog</h1>
  <p>News, updates & behind-the-scenes stories from Dark Wrld</p>
</section>

<section class="section">

  <div class="blog-post">
    <h2>New Single Dropping Soon</h2>
    <p>Dark Wrld announces a brand new single releasing this month. Fans can expect unique beats and powerful lyrics. Stay tuned!</p>
    <a href="https://open.spotify.com/artist/7iWv8ZvaBUkslCwhLUbQl2" target="_blank" class="button">Listen on Spotify</a>
  </div>

  <div class="blog-post">
    <h2>Behind The Scenes: Studio Sessions</h2>
    <p>Step into the creative process with Dark Wrld as he experiments with new sounds and collaborates with producers. A sneak peek into the next era of music.</p>
    <a href="https://www.instagram.com/darkwrldmusic/" target="_blank" class="button">Follow on Instagram</a>
  </div>

  <div class="blog-post">
    <h2>Upcoming Tour Dates</h2>
    <p>Dark Wrld is hitting the stage across East Africa. Check out tour dates and venues for live experiences you won’t forget!</p>
    <a href="contact.html" class="button">Book or Contact</a>
  </div>

</section>

<footer>
  © 2026 Dark Wrld | All Rights Reserved
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Contact | Dark Wrld</title>
  <meta name="description" content="Get in touch with Dark Wrld for bookings, collaborations, or newsletter updates.">
  <meta name="keywords" content="Dark Wrld contact, booking, collaboration, newsletter">
  <meta name="author" content="Dark Wrld">

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #0c0c0c;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background: black;
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 999;
    }

    header a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
    }

    .hero {
      padding-top: 120px;
      padding-bottom: 60px;
      text-align: center;
      background: linear-gradient(to bottom, #000000, #111111);
    }

    .hero h1 {
      font-size: 50px;
      margin-bottom: 10px;
    }

    .section {
      padding: 60px 40px;
      text-align: center;
    }

    .newsletter input {
      padding: 12px;
      width: 250px;
      border-radius: 30px;
      border: none;
      margin-right: 10px;
    }

    .newsletter button {
      padding: 12px 25px;
      border-radius: 30px;
      border: none;
      background: #1db954;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }

    .contact-info {
      margin-top: 40px;
    }

    .contact-info p {
      margin: 10px 0;
      font-size: 16px;
      opacity: 0.85;
    }

    footer {
      background: #111;
      padding: 30px;
      text-align: center;
      font-size: 14px;
      opacity: 0.7;
      margin-top: 60px;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }
      .newsletter input {
        width: 70%;
        margin-bottom: 10px;
      }
      .newsletter button {
        width: 50%;
      }
    }
  </style>
</head>

<body>

<header>
  <div><strong>Dark Wrld</strong></div>
  <nav>
    <a href="index.html">Home</a>
    <a href="music.html">Music</a>
    <a href="playlists.html">Playlists</a>
    <a href="merch.html">Merch</a>
    <a href="blog.html">Blog</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Contact</h1>
  <p>Get in touch with Dark Wrld</p>
</section>

<section class="section newsletter">
  <h2>Join The Wrld</h2>
  <p>Subscribe for updates on new music and releases.</p>
  <form action="https://formspree.io/f/YOUR_ID" method="POST">
    <input type="email" name="email" placeholder="Enter your email" required>
    <button type="submit">Subscribe</button>
  </form>
</section>

<section class="section contact-info">
  <h2>Booking & Collaborations</h2>
  <p>Email: <a href="mailto:darkwrldmusic@email.com" style="color:#1db954;">darkwrldmusic@email.com</a></p>
  <p>For business inquiries, collaborations, or media requests, please reach out via email above.</p>
</section>

<footer>
  © 2026 Dark Wrld | All Rights Reserved
</footer>

</body>
</html>
/* =========================
   Global Reset & Fonts
========================= */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Poppins', sans-serif;
  background: #0c0c0c;
  color: white;
  line-height: 1.6;
}

/* =========================
   Header & Navigation
========================= */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
  background: black;
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 999;
}

header a {
  color: white;
  text-decoration: none;
  margin-left: 20px;
  font-weight: 500;
  transition: 0.3s ease;
}

header a:hover {
  color: #1db954;
}

/* =========================
   Hero Section
========================= */
.hero {
  padding-top: 120px;
  padding-bottom: 60px;
  text-align: center;
  background: linear-gradient(to bottom, #000000, #111111);
}

.hero h1 {
  font-size: 50px;
  margin-bottom: 10px;
  letter-spacing: 2px;
}

.hero p {
  margin-top: 10px;
  opacity: 0.8;
}

/* =========================
   Sections
========================= */
.section {
  padding: 60px 40px;
  text-align: center;
}

/* =========================
   Buttons
========================= */
.button {
  display: inline-block;
  margin-top: 15px;
  padding: 12px 30px;
  background: #1db954;
  border-radius: 40px;
  text-decoration: none;
  color: white;
  font-weight: bold;
  transition: 0.3s ease;
}

.button:hover {
  opacity: 0.8;
}

/* =========================
   Spotify & Iframes
========================= */
iframe {
  width: 100%;
  max-width: 750px;
  height: 380px;
  border-radius: 12px;
  border: none;
  margin-top: 20px;
}

/* =========================
   Merch Grid
========================= */
.merch-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 40px;
}

.merch-card {
  background: #151515;
  padding: 20px;
  width: 250px;
  border-radius: 12px;
  text-align: center;
}

.merch-card img {
  width: 100%;
  border-radius: 12px;
}

.merch-card h3 {
  margin: 15px 0 5px 0;
}

.merch-card p {
  margin: 5px 0 15px 0;
  opacity: 0.8;
}

/* =========================
   Blog / News Posts
========================= */
.blog-post {
  background: #151515;
  padding: 25px;
  margin: 25px auto;
  max-width: 800px;
  border-radius: 12px;
  text-align: left;
}

.blog-post h2 {
  margin-bottom: 10px;
}

.blog-post p {
  opacity: 0.85;
}

/* =========================
   Newsletter Form
========================= */
.newsletter input {
  padding: 12px;
  width: 250px;
  border-radius: 30px;
  border: none;
  margin-right: 10px;
}

.newsletter button {
  padding: 12px 25px;
  border-radius: 30px;
  border: none;
  background: #1db954;
  color: white;
  font-weight: bold;
  cursor: pointer;
}

.newsletter button:hover {
  opacity: 0.8;
}

/* =========================
   Contact Info
========================= */
.contact-info {
  margin-top: 40px;
}

.contact-info p {
  margin: 10px 0;
  font-size: 16px;
  opacity: 0.85;
}

/* =========================
   Footer
========================= */
footer {
  background: #111;
  padding: 30px;
  text-align: center;
  font-size: 14px;
  opacity: 0.7;
  margin-top: 60px;
}

/* =========================
   Responsive Design
========================= */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 36px;
  }

  .merch-grid {
    flex-direction: column;
    align-items: center;
  }

  .newsletter input {
    width: 70%;
    margin-bottom: 10px;
  }

  .newsletter button {
    width: 50%;
  }
}
