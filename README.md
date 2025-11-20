<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>She Narrates – Women’s Cognitive & Storytelling Platform</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Navigation Enhanced -->
<nav class="navbar">
  <div class="logo">She Narrates</div>
  <ul class="nav-links">
    <li><a href="#hero">Home</a></li>
    <li><a href="#vision">Vision</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#challenge">Challenges</a></li>
    <li><a href="#stories">Stories</a></li>
    <li><a href="#cognitive">Cognitive Games</a></li>
    <li><a href="#video">Intro Video</a></li>
  </ul>
</nav>

<!-- Hero Section with Static Banner -->
<header id="hero" class="hero">
  <img src="assets/banner-static.png" class="hero-banner" alt="She Narrates Static Banner">
  <h1>She Narrates</h1>
  <p>A space combining cognitive exercises, storytelling, and women empowerment.</p>
</header>

<!-- Vision Section -->
<section id="vision" class="section">
  <h2>Our Vision</h2>
  <p>Creating a global platform that amplifies women’s voices, integrates cognitive insights with creativity, and fosters personal growth.</p>
</section>

<!-- Features Section -->
<section id="features" class="section">
  <h2>Platform Features</h2>
  <ul class="feature-list">
    <li>Daily challenges for awareness and creativity</li>
    <li>Secure community for storytelling and sharing</li>
    <li>Cognitive mini-games for memory and focus</li>
    <li>AI-assisted writing and emotional organization</li>
  </ul>
</section>

<!-- Animated Banner Section -->
<section class="section">
  <h2>Animated Banner</h2>
  <img src="assets/banner-animated.gif" class="animated-banner" alt="Animated Banner">
</section>

<!-- Challenge Section -->
<section id="challenge" class="section card">
  <h2>Creative Challenges (1–3 minutes)</h2>
  <button onclick="generateIdea()">Generate Challenge</button>
  <div id="ideaBox" class="idea-box"></div>
  <div id="score" class="score">Score: 0</div>
</section>

<!-- Stories Section -->
<section id="stories" class="section">
  <h2>Share Your Story</h2>
  <textarea id="storyText" rows="4" placeholder="Write your experience..."></textarea>
  <button onclick="publishStory()">Publish Story</button>
  <div id="storyFeed"></div>
</section>

<!-- Cognitive Game Section -->
<section id="cognitive" class="section card">
  <h2>Cognitive Mini-Game</h2>
  <button onclick="startCognitiveGame()">Start Game</button>
  <div id="cognitiveBox"></div>
</section>

<!-- Intro Video Section -->
<section id="video" class="section">
  <h2>Intro Video</h2>
  <video src="assets/intro-video.mp4" controls class="intro-video"></video>
</section>

<script src="script.js"></script>
</body>
</html>