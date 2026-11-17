# MahaBite-
It's a good delivery 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MAHABITE | Mumbai Food Delivery</title>
<meta name="description" content="Discover the taste of Maharashtra with MahaBite. Mumbai's upcoming food delivery platform.">
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700;800&family=Noto+Sans+Devanagari:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root {
  --orange:#D95828;
  --green:#237A58;
  --cream:#FFF7EF;
  --dark:#26352D;
  --white:#fff;
}
* { box-sizing:border-box; margin:0; padding:0; }
html { scroll-behavior:smooth; }
body {
  font-family:'DM Sans','Noto Sans Devanagari',sans-serif;
  background:var(--cream);
  color:var(--dark);
}
header {
  background:var(--white);
  padding:16px 7%;
  display:flex;
  justify-content:space-between;
  align-items:center;
  position:sticky;
  top:0;
  z-index:10;
  box-shadow:0 2px 15px #0000000c;
}
.logo { font-size:27px; font-weight:800; color:var(--orange); }
.logo span { color:var(--green); }
nav { display:flex; gap:25px; align-items:center; }
nav a { text-decoration:none; color:var(--dark); font-weight:600; }
.btn {
  display:inline-block;
  padding:13px 22px;
  border-radius:30px;
  background:var(--orange);
  color:white;
  text-decoration:none;
  font-weight:700;
  border:0;
  cursor:pointer;
}
.menu { display:none; background:none; border:0; font-size:25px; }
.hero {
  padding:75px 7%;
  display:grid;
  grid-template-columns:1.1fr .9fr;
  align-items:center;
  gap:35px;
}
.eyebrow {
  color:var(--green);
  font-weight:800;
  letter-spacing:2px;
  text-transform:uppercase;
  font-size:13px;
}
h1 {
  font-size:clamp(42px,6vw,70px);
  line-height:1.05;
  margin:18px 0;
}
h1 span { color:var(--orange); }
.hero p { font-size:18px; line-height:1.7; max-width:520px; }
.hero-image {
  min-height:350px;
  border-radius:30px;
  background:
    linear-gradient(0deg,#18251b55,#18251b00),
    url('https://images.unsplash.com/photo-1546833999-b9f581a1996d?w=1100') center/cover;
  box-shadow:0 20px 50px #5d3c2520;
}
section { padding:65px 7%; }
.section-heading { text-align:center; margin-bottom:35px; }
.section-heading h2 { font-size:35px; margin-bottom:10px; }
.section-heading p { color:#69736c; }
.categories {
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:18px;
}
.category {
  background:white;
  border-radius:20px;
  overflow:hidden;
  text-align:center;
  box-shadow:0 8px 25px #00000008;
}
.category img { width:100%; height:155px; object-fit:cover; }
.category h3 { padding:15px 8px 18px; font-size:16px; }
.green-section { background:var(--green); color:white; }
.green-section .section-heading p { color:#e4f1e9; }
.features {
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:20px;
}
.feature {
  background:#ffffff18;
  padding:25px;
  border-radius:18px;
}
.feature h3 { margin:10px 0; }
.form-section {
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:25px;
}
.form-card {
  background:white;
  padding:28px;
  border-radius:22px;
  box-shadow:0 8px 30px #00000008;
}
.form-card h3 { font-size:23px; margin-bottom:8px; }
.form-card p { color:#69736c; margin-bottom:20px; }
input,select {
  width:100%;
  padding:14px;
  margin-bottom:13px;
  border:1px solid #ddd;
  border-radius:10px;
  font:inherit;
  background:white;
}
.form-card button { width:100%; }
.note { font-size:12px; color:#777; margin-top:12px; line-height:1.5; }
.faq { max-width:750px; margin:auto; }
details {
  background:white;
  margin:12px 0;
  padding:18px;
  border-radius:12px;
}
summary { font-weight:700; cursor:pointer; }
details p { margin-top:12px; color:#657067; line-height:1.6; }
footer {
  background:var(--dark);
  color:white;
  padding:40px 7%;
  text-align:center;
}
footer p { margin-top:12px; color:#d4ddd6; }
@media(max-width:800px) {
  nav {
    display:none;
    position:absolute;
    top:65px; left:0; right:0;
    background:white;
    padding:22px;
    flex-direction:column;
  }
  nav.open { display:flex; }
  .menu { display:block; }
  .hero { grid-template-columns:1fr; padding-top:45px; }
  .hero-image { min-height:260px; }
  .categories { grid-template-columns:repeat(2,1fr); }
  .features { grid-template-columns:1fr; }
  .form-section { grid-template-columns:1fr; }
  section { padding:48px 6%; }
}
</style>
</head>
<body>
<header>
  <div class="logo">MAHA<span>BITE</span></div>
  <button class="menu" onclick="document.querySelector('nav').classList.toggle('open')">☰</button>
  <nav>
    <a href="#home">Home</a>
    <a href="#food">Explore Food</a>
    <a href="#about">About</a>
    <a href="#partner">Restaurant Partner</a>
    <a href="#join" class="btn">Join Us</a>
  </nav>
</header>
<main>
<section class="hero" id="home">
  <div>
    <div class="eyebrow">A new taste of Mumbai</div>
    <h1>Good food.<br><span>Good mood.</span><br>MahaBite.</h1>
    <p>महाराष्ट्राची चव. आता एका क्लिकवर.</p>
    <p>From Mumbai's favourite street food to delicious meals, we're bringing food lovers and local restaurants closer together.</p>
    <br>
    <a href="#join" class="btn">Get Early Access</a>
  </div>
  <div class="hero-image" role="img" aria-label="Indian food platter"></div>
</section>
<section id="food">
  <div class="section-heading">
    <h2>What are you craving?</h2>
    <p>A taste for every mood.</p>
  </div>
  <div class="categories">
    <article class="category">
      <img src="https://images.unsplash.com/photo-1606491956689-2ea866880c84?w=500" alt="Indian street food">
      <h3>Vada Pav & Snacks</h3>
    </article>
    <article class="category">
      <img src="https://images.unsplash.com/photo-1631452180519-c014fe946bc7?w=500" alt="Indian curry">
      <h3>Misal & Usal</h3>
    </article>
    <article class="category">
      <img src="https://images.unsplash.com/photo-1546833999-b9f581a1996d?w=500" alt="Indian thali">
      <h3>Thalis & Meals</h3>
    </article>
    <article class="category">
      <img src="https://images.unsplash.com/photo-1563379091339-03246963d51a?w=500" alt="Biryani">
      <h3>Biryani</h3>
    </article>
    <article class="category">
      <img src="https://images.unsplash.com/photo-1569718212165-3a8278d5f624?w=500" alt="Noodles">
      <h3>Chinese</h3>
    </article>
    <article class="category">
      <img src="https://images.unsplash.com/photo-1630384060421-cb20d0e0649d?w=500" alt="South Indian food">
      <h3>South Indian</h3>
    </article>
    <article class="category">
      <img src="https://images.unsplash.com/photo-1551024506-0bccd828d307?w=500" alt="Dessert">
      <h3>Sweets & Desserts</h3>
    </article>
    <article class="category">
      <img src="https://images.unsplash.com/photo-1579751626657-72bc17010498?w=500" alt="Fast food">
      <h3>Fast Food</h3>
    </article>
  </div>
</section>
<section class="green-section" id="about">
  <div class="section-heading">
    <h2>Why MahaBite?</h2>
    <p>Local flavour. Big dreams. A better food experience.</p>
  </div>
  <div class="features">
    <div class="feature">
      <div style="font-size:32px">🍛</div>
      <h3>Local favourites</h3>
      <p>Celebrate the food and flavours Mumbai loves.</p>
    </div>
    <div class="feature">
      <div style="font-size:32px">🏪</div>
      <h3>Support local restaurants</h3>
      <p>Help neighbourhood food businesses reach more people.</p>
    </div>
    <div class="feature">
      <div style="font-size:32px">❤️</div>
      <h3>Made with love</h3>
      <p>A food brand built around people, taste and community.</p>
    </div>
  </div>
</section>
<section id="join">
  <div class="section-heading">
    <h2>Be part of MahaBite</h2>
    <p>We're preparing for our Mumbai launch. Register your interest.</p>
  </div>
  <div class="form-section">
    <form class="form-card" onsubmit="demoSubmit(event,'customer')">
      <h3>For food lovers ❤️</h3>
      <p>Be among the first to hear about our launch.</p>
      <input name="name" placeholder="Your name" required>
      <input name="contact" placeholder="Email or phone number" required>
      <input name="locality" placeholder="Your Mumbai locality" required>
      <select name="favourite" required>
        <option value="">Your favourite food</option>
        <option>Vada Pav & Snacks</option>
        <option>Misal & Usal</option>
        <option>Thali & Meals</option>
        <option>Biryani</option>
        <option>Other</option>
      </select>
      <button class="btn" type="submit">Register Interest</button>
      <div class="note">Demo only: this form does not send or save your details.</div>
    </form>
    <form class="form-card" id="partner" onsubmit="demoSubmit(event,'restaurant')">
      <h3>Restaurant owners 🏪</h3>
      <p>Want to grow your restaurant with MahaBite?</p>
      <input name="restaurant" placeholder="Restaurant name" required>
      <input name="owner" placeholder="Owner / contact person" required>
      <input name="contact" placeholder="Phone or email" required>
      <input name="locality" placeholder="Restaurant locality" required>
      <select name="type" required>
        <option value="">Food category</option>
        <option>Street Food</option>
        <option>Maharashtrian</option>
        <option>Indian Meals</option>
        <option>Fast Food</option>
        <option>Other</option>
      </select>
      <button class="btn" type="submit">Become a Partner</button>
      <div class="note">Demo only: this form does not send or save your details.</div>
    </form>
  </div>
</section>
<section>
  <div class="section-heading">
    <h2>Frequently asked questions</h2>
  </div>
  <div class="faq">
    <details>
      <summary>Is MahaBite currently delivering?</summary>
      <p>Not yet. We're preparing our launch and inviting customers and restaurant partners to register their interest.</p>
    </details>
    <details>
      <summary>Which areas will MahaBite serve?</summary>
      <p>Our launch focus is Mumbai. Exact service areas will be announced after restaurant and delivery partnerships are confirmed.</p>
    </details>
    <details>
      <summary>How can my restaurant join?</summary>
      <p>Use the restaurant partner form above to express your interest. Our team will follow up once the partner programme is ready.</p>
    </details>
  </div>
</section>
</main>
<footer>
  <div class="logo" style="color:white">MAHA<span style="color:#f3a17d">BITE</span></div>
  <p>महाराष्ट्राची चव. आता एका क्लिकवर.</p>
  <p>Launching in Mumbai • Made for food lovers</p>
  <p style="font-size:12px;margin-top:22px">© 2026 MahaBite. All rights reserved.</p>
</footer>
<script>
function demoSubmit(event, type) {
  event.preventDefault();
  const message = type === 'customer'
    ? 'Thanks for your interest in MahaBite! This is a demo form. No information has been submitted or saved.'
    : 'Thanks for your restaurant interest! This is a demo form. No information has been submitted or saved.';
  alert(message);
}
</script>
</body>
</html>
