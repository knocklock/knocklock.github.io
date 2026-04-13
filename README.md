<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>GoldenKing Apps</title>

<style>
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, sans-serif;
  background: #0E0A08;
  color: #fff;
}

/* HERO */
.hero {
  text-align: center;
  padding: 80px 20px 40px;
}

.hero img {
  width: 120px;
  border-radius: 24px;
}

.hero h1 {
  font-size: 32px;
  margin-top: 20px;
}

.hero p {
  max-width: 600px;
  margin: 16px auto;
  color: rgba(255,255,255,0.6);
}

/* GRID */
.container {
  max-width: 1100px;
  margin: auto;
  padding: 40px 20px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 24px;
}

/* CARD */
.card {
  background: #171310;
  border-radius: 20px;
  padding: 20px;
  transition: 0.3s;
  border: 1px solid rgba(255,255,255,0.05);
}

.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 30px rgba(0,0,0,0.4);
}

.card img {
  width: 80px;
  border-radius: 16px;
}

.card h3 {
  margin: 12px 0 6px;
}

.card p {
  font-size: 14px;
  color: rgba(255,255,255,0.6);
}

.play-btn {
  margin-top: 12px;
  display: inline-block;
}

.play-btn img {
  height: 45px;
}

/* FOOTER */
.footer {
  text-align: center;
  padding: 40px;
  color: rgba(255,255,255,0.4);
  font-size: 14px;
}
</style>
</head>

<body>

<!-- HERO -->
<div class="hero">
  <img src="assets/knocklock.png" />
  <h1>GoldenKing Apps</h1>
  <p>
    Crafting powerful, intuitive mobile experiences that improve everyday life.
  </p>
</div>

<!-- APPS -->
<div class="container">
  <div class="grid">

    <!-- APP 1 -->
    <div class="card">
      <img src="assets/kl.png" />
      <h3>Knock Lock Screen</h3>
      <p>Secure your phone with a unique knock-based lock system.</p>
      <a class="play-btn" href="https://play.google.com/store/apps/details?id=com.knocklock.applock">
        <img src="assets/badge_playstore.png"/>
      </a>
    </div>

    <!-- APP 2 -->
    <div class="card">
      <img src="assets/hn.png" />
      <h3>Health & Nutrition Guide</h3>
      <p>Achieve your fitness goals with smart nutrition insights.</p>
      <a class="play-btn" href="https://play.google.com/store/apps/details?id=knocklock.health.nutrition.foodguide.nutritionsforall.healthyfood">
        <img src="assets/badge_playstore.png"/>
      </a>
    </div>

    <!-- APP 3 -->
    <div class="card">
      <img src="assets/md.png" />
      <h3>Mental Disorders</h3>
      <p>Understand mental health with structured insights and guidance.</p>
      <a class="play-btn" href="https://play.google.com/store/apps/details?id=mental.disorders.treatments">
        <img src="assets/badge_playstore.png"/>
      </a>
    </div>

    <!-- APP 4 -->
    <div class="card">
      <img src="assets/sd.png" />
      <h3>Stomach Diseases</h3>
      <p>Learn about digestive health and prevention methods.</p>
      <a class="play-btn" href="https://play.google.com/store/apps/details?id=stomach.diseases.treatment">
        <img src="assets/badge_playstore.png"/>
      </a>
    </div>

  </div>
</div>

<!-- FOOTER -->
<div class="footer">
  Crafted with ❤️ in 🇮🇳
</div>

</body>
</html>
