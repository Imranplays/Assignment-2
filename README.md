<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ImranplaysYT | Sports & Gaming</title>

  <!-- ✅ Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- ✅ Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- ✅ Custom Style -->
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      background: #f8fafc;
      color: #222;
    }
  </style>
</head>
<body>

<!-- 🌐 Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-gradient-to-r from-blue-600 to-green-500 shadow-md">
  <div class="container">
    <a class="navbar-brand fw-bold text-white hover:text-yellow-300 transition" 
       href="https://youtube.com/@imranplaysyt7243?si=vh2chNMQmZ8s8TOG" target="_blank">
       ImranplaysYT
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active hover:text-yellow-300" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link hover:text-yellow-300" href="#activities">Activities</a></li>
        <li class="nav-item"><a class="nav-link hover:text-yellow-300" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- 🏏 Hero Section -->
<section class="text-center py-5">
  <div class="container">
    <h1 class="display-5 fw-bold text-blue-600 animate-bounce">
      Welcome to <span class="text-green-500">ImranplaysYT!</span>
    </h1>
    <p class="lead mb-4 text-gray-600">Cricket • Football • PUBG Mobile — sharing my journey and highlights!</p>
    <img src="https://i.postimg.cc/dQHttpgq/imran.jpg" 
         alt="ImranplaysYT" 
         class="img-fluid rounded-xl shadow-lg hover:scale-105 transition-transform duration-300 mx-auto" 
         style="max-width: 400px;">
  </div>
</section>

<!-- 🎥 Featured Video -->
<section class="text-center my-5 bg-white py-5 shadow-inner">
  <div class="container">
    <h2 class="text-3xl font-bold text-blue-600 mb-3">🎥 Featured Video</h2>
    <p class="text-gray-700 mb-4">Check out one of my latest YouTube Shorts!</p>
    <div class="ratio ratio-16x9 max-w-2xl mx-auto">
      <iframe src="https://www.youtube.com/embed/B8UbK5H4gEQ"
              title="ImranplaysYT Short Video"
              allowfullscreen
              class="rounded-lg"></iframe>
    </div>
  </div>
</section>

<!-- ⚽ Activities -->
<section id="activities" class="my-5">
  <div class="container">
    <h2 class="text-center text-3xl font-bold text-green-600 mb-4">My Activities</h2>

    <ul class="list-group shadow-sm">
      <li class="list-group-item hover:bg-gray-100 transition">🏏 Cricket — Bowling, Batting & Match Highlights</li>
      <li class="list-group-item hover:bg-gray-100 transition">⚽ Football — Local Tournament Action</li>
      <li class="list-group-item hover:bg-gray-100 transition">🎮 PUBG Mobile — Squad Battles & Clutch Moments</li>
    </ul>

    <h3 class="mt-4 text-2xl text-blue-600 font-semibold">Upcoming Plans</h3>
    <ol class="ms-4 text-gray-700">
      <li>Practice cricket daily 🏏</li>
      <li>Join local football tournaments ⚽</li>
      <li>Upload gaming highlights weekly 🎮</li>
    </ol>

    <blockquote class="blockquote mt-4 border-l-4 border-blue-500 ps-3 text-gray-600 italic">
      "Sports do not build character. They reveal it." — Heywood Broun
    </blockquote>
  </div>
</section>

<!-- 📊 Recent Activity -->
<section class="my-5 bg-white py-5">
  <div class="container">
    <h2 class="text-center text-3xl font-bold text-blue-600 mb-4">Recent Activity Log</h2>
    <div class="table-responsive">
      <table class="table table-bordered table-hover shadow-sm">
        <thead class="table-primary">
          <tr><th>Activity</th><th>Recent Event</th><th>Result</th></tr>
        </thead>
        <tbody>
          <tr><td>Cricket</td><td>Friendly Match vs Team B</td><td>🏆 Won</td></tr>
          <tr><td>Football</td><td>5v5 Local Tournament</td><td>😅 Lost</td></tr>
          <tr><td>PUBG</td><td>Squad Battle (Erangel)</td><td>🎯 Top 3</td></tr>
        </tbody>
      </table>
    </div>

    <h3 class="text-green-600 text-2xl font-semibold mt-4">Skill Progress</h3>
    <label>Cricket Skill</label>
    <progress value="80" max="100" class="w-full h-2 rounded bg-gray-200"></progress>
    <label>Football Skill</label>
    <progress value="65" max="100" class="w-full h-2 rounded bg-gray-200"></progress>
    <label>PUBG Skill</label>
    <progress value="90" max="100" class="w-full h-2 rounded bg-gray-200"></progress>

    <h3 class="text-blue-600 text-2xl font-semibold mt-4">Fan Support</h3>
    <meter value="75" min="0" max="100" class="w-full h-2"></meter>
  </div>
</section>

<!-- 🌍 Popular Sports -->
<section class="my-5">
  <div class="container">
    <h2 class="text-center text-3xl font-bold text-green-600 mb-3">Popular Sports Around the World</h2>
    <div class="table-responsive">
      <table class="table table-bordered table-hover shadow-sm">
        <thead class="table-success">
          <tr><th>Sport</th><th>Origin</th><th>Rank</th></tr>
        </thead>
        <tbody>
          <tr><td>Soccer (Football)</td><td>England</td><td>1</td></tr>
          <tr><td>Cricket</td><td>England</td><td>2</td></tr>
          <tr><td>Basketball</td><td>USA</td><td>3</td></tr>
          <tr><td>Tennis</td><td>France</td><td>4</td></tr>
          <tr><td>Volleyball</td><td>USA</td><td>5</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<!-- 🎮 Popular Online Games -->
<section class="my-5 bg-white py-5">
  <div class="container">
    <h2 class="text-center text-3xl font-bold text-blue-600 mb-3">Popular Online Games</h2>
    <div class="table-responsive">
      <table class="table table-bordered table-hover shadow-sm">
        <thead class="table-info">
          <tr><th>Game</th><th>Platform</th><th>Players</th></tr>
        </thead>
        <tbody>
          <tr><td>PUBG Mobile</td><td>Mobile</td><td>800M+</td></tr>
          <tr><td>Fortnite</td><td>PC / Console / Mobile</td><td>400M+</td></tr>
          <tr><td>Call of Duty: Warzone</td><td>PC / Console</td><td>100M+</td></tr>
          <tr><td>Minecraft</td><td>PC / Mobile / Console</td><td>140M+</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<!-- 📩 Contact -->
<section id="contact" class="my-5">
  <div class="container">
    <h2 class="text-center text-3xl font-bold text-green-600 mb-4">Contact Me</h2>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <form class="bg-white p-4 rounded-lg shadow-lg space-y-3">
          <input type="text" class="form-control border border-gray-300 rounded focus:ring-2 focus:ring-blue-400" placeholder="Enter your name">
          <input type="email" class="form-control border border-gray-300 rounded focus:ring-2 focus:ring-blue-400" placeholder="Enter your email">
          <textarea rows="4" class="form-control border border-gray-300 rounded focus:ring-2 focus:ring-blue-400" placeholder="Write something..."></textarea>
          <button type="submit" class="btn bg-green-500 text-white w-100 hover:bg-green-600 transition">Send Message</button>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- ⚡ Footer -->
<footer class="text-center text-white py-3 bg-gradient-to-r from-green-500 to-blue-600">
  <p class="mb-0">© 2025 ImranplaysYT |
    <a href="https://youtube.com/@imranplaysyt7243?si=vh2chNMQmZ8s8TOG" target="_blank" class="text-yellow-300 hover:text-white">
      Visit My YouTube Channel
    </a>
  </p>
</footer>

<!-- ✅ Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
