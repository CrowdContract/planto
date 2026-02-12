<script setup>
import logo from "@/assets/logo/image.png"

import heroPlant from "@/assets/plants/plant1.png"
import plant2 from "@/assets/plants/plant2.png"
import plant3 from "@/assets/plants/plant3.png"
import plant4 from "@/assets/plants/plant4.png"

import review1 from "@/assets/reviews/review1.png"
import review2 from "@/assets/reviews/review2.png"
import review3 from "@/assets/reviews/review3.png"
</script>

<template>
  <div class="page">
    <div class="container">

      <!-- NAVBAR -->
      <nav class="navbar">
        <div class="nav-left">
          <img :src="logo" class="logo" />
          <span class="brand">Planto.</span>
        </div>

        <div class="nav-links">
          <a href="#">Home</a>
          <a href="#">Plants Type</a>
          <a href="#">More</a>
          <a href="#">Contact</a>
        </div>

        <div class="nav-icons">
          <span class="icon">🔍</span>
          <span class="icon">🛒</span>
          <span class="icon">☰</span>
        </div>
      </nav>

      <!-- HERO -->
      <section class="hero">

        <div class="hero-left">
          <h1>Breath Natural</h1>

          <p class="hero-desc">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>

          <div class="hero-buttons">
            <button class="explore-btn">Explore</button>

            <button class="demo-btn">
              <span class="play-icon">▶</span>
              Live Demo
            </button>
          </div>
        </div>

        <!-- HERO CARD -->
        <div class="hero-card">

          <img :src="heroPlant" class="card-plant" />

          <div class="card-content">

            <span class="card-label">Trendy House Plant</span>

            <div class="card-title-row">
              <h3>Calathea plant</h3>
              <span class="arrow">›</span>
            </div>

            <button class="buy-btn">Buy Now</button>

            <div class="dots">
              <span></span>
              <span class="active"></span>
              <span></span>
            </div>

          </div>
        </div>

      </section>

      <!-- TRENDY -->
      <section class="section">
        <h2>Our Trendy plants</h2>

        <div class="trendy-box">

          <div class="trendy-image">
            <img :src="plant2" />
          </div>

          <div class="trendy-content">
            <h3>For Small Decs Ai Plat</h3>

            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore.
            </p>

            <span class="price">Rs. 599/-</span>

            <div class="trendy-actions">
              <button class="explore-small">Explore</button>
              <div class="bag">🛍</div>
            </div>
          </div>

        </div>
        <div class="trendy-box">

          <div class="trendy-content">
            <h3>For Small Decs Ai Plat</h3>

            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore.
            </p>

            <span class="price">Rs. 599/-</span>

            <div class="trendy-actions">
              <button class="explore-small">Explore</button>
              <div class="bag">🛍</div>
            </div>
          </div>
           <div class="trendy-image">
            <img :src="plant2" />
          </div>

        </div>
      </section>

      <!-- TOP SELLING -->
<section class="section">
  <h2>Our Top Selling</h2>

  <div class="grid">
    <div class="product">
      <img :src="plant2" />
      <h4>Calathea plant</h4>
      <p>Lorem ipsum dolor sit amet</p>
      <span class="product-price">Rs. 359/-</span>
    </div>

    <div class="product">
      <img :src="plant3" />
      <h4>Calathea plant</h4>
      <p>Lorem ipsum dolor sit amet</p>
      <span class="product-price">Rs. 359/-</span>
    </div>

    <div class="product">
      <img :src="plant4" />
      <h4>Calathea plant</h4>
      <p>Lorem ipsum dolor sit amet</p>
      <span class="product-price">Rs. 359/-</span>
    </div>

    <div class="product">
      <img :src="plant3" />
      <h4>Calathea plant</h4>
      <p>Lorem ipsum dolor sit amet</p>
      <span class="product-price">Rs. 359/-</span>
    </div>

    <div class="product">
      <img :src="plant2" />
      <h4>Calathea plant</h4>
      <p>Lorem ipsum dolor sit amet</p>
      <span class="product-price">Rs. 359/-</span>
    </div>

    <div class="product">
      <img :src="plant4" />
      <h4>Calathea plant</h4>
      <p>Lorem ipsum dolor sit amet</p>
      <span class="product-price">Rs. 359/-</span>
    </div>
  </div>
</section>


    <!-- REVIEWS -->
<section class="section reviews-section">
  <h2>Customer Review</h2>

  <div class="reviews">

    <div class="review-card">
      <div class="review-header">
        <img :src="review1" class="review-img" />

        <div>
          <div class="review-name">Maxn Raval</div>
          <div class="review-stars">★★★★★</div>
        </div>
      </div>

      <p>Lorem ipsum dolor sit amet...</p>
    </div>

    <div class="review-card">
      <div class="review-header">
        <img :src="review2" class="review-img" />

        <div>
          <div class="review-name">Venely K</div>
          <div class="review-stars">★★★★★</div>
        </div>
      </div>

      <p>Lorem ipsum dolor sit amet...</p>
    </div>

    <div class="review-card">
      <div class="review-header">
        <img :src="review3" class="review-img" />

        <div>
          <div class="review-name">Lii Thakur</div>
          <div class="review-stars">★★★★★</div>
        </div>
      </div>

      <p>Lorem ipsum dolor sit amet...</p>
    </div>

  </div>
</section>

 <section class="best-section">

  <h2 class="best-title">Our Best O2</h2>

  <div class="best-box">

    <div class="best-image">
      <img src="/src/assets/plants/plant1.png" />
    </div>

    <div class="best-content">
      <h3>We Have Small And Best O2 Plants Collection’s</h3>

      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit,
        sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </p>

      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit,
        sed do eiusmod tempor incididunt ut labore.
      </p>

      <button class="explore-btn">Explore</button>
    </div>

  </div>

  

</section>

    </div>

    <!-- FOOTER -->
    <footer class="footer">
      <div class="footer-top">
        <!-- LEFT -->
        <div class="footer-brand">
          <div class="footer-logo">
            <img :src="logo" />
            <span>Planto.</span>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <div class="socials">
            <span>FB</span>
            <span>TW</span>
            <span>LI</span>
          </div>
        </div>
        <!-- CENTER -->
        <div class="footer-links">
          <h4>Quick Link's</h4>
          <a href="#">Home</a>
          <a href="#">Type's Of plants</a>
          <a href="#">Contact</a>
          <a href="#">Privacy</a>
        </div>
        <!-- RIGHT -->
        <div class="footer-subscribe">
          <h4>For Every Update.</h4>
          <div class="subscribe-box">
            <input type="text" placeholder="Enter Email" />
            <button>SUBSCRIBE</button>
          </div>
        </div>
      </div>
      <div class="footer-bottom">
        <span>planto © all right reserve</span>
      </div>
    </footer>

  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* GLOBAL PAGE */

.page {
  min-height: 100vh;
  color: white;
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;

  background:
    url("@/assets/plants/plant.png") top center / 100% 180vh no-repeat,
    #0d0f0e;   /* Pure dark bottom */

  background-color: #0d0f0e;
}

/* ✅ CONTAINER */
.container {
  width: 100%;
  max-width: 1200px;
  margin: auto;
  padding: 20px;
}


/* CONTAINER */
.container {
  width: 100%;
  max-width: 1400px;
  margin: 0 auto;
  padding: 24px 60px;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 80px;
  padding: 12px 0;
}

.nav-left {
  display: flex;
  align-items: center;
  gap: 8px;
}

/* LOGO */
.logo {
  width: 48px;
  height: 48px;
  object-fit: contain;
}

.brand {
  font-size: 26px;
  font-weight: 700;
  letter-spacing: -0.5px;
}

/* MENU */
.nav-links {
  display: flex;
  gap: 48px;
  align-items: center;
}

.nav-links a {
  color: rgba(255, 255, 255, 0.9);
  text-decoration: none;
  font-size: 15px;
  font-weight: 500;
  cursor: pointer;
  transition: opacity 0.2s;
}

.nav-links a:hover {
  opacity: 0.7;
}

.nav-links a:first-child {
  font-weight: 600;
}

/* ICONS */
.nav-icons {
  display: flex;
  gap: 24px;
  align-items: center;
}

.icon {
  font-size: 20px;
  cursor: pointer;
  opacity: 0.85;
  transition: opacity 0.2s;
}

.icon:hover {
  opacity: 1;
}

/* HERO */
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 120px;
  margin-bottom: 120px;
}

.hero-left {
  flex: 1;
  max-width: 580px;
}

.hero-left h1 {
  font-size: 72px;
  font-weight: 700;
  line-height: 1.1;
  margin-bottom: 24px;
  letter-spacing: -2px;
}

.hero-desc {
  font-size: 16px;
  line-height: 1.7;
  color: rgba(255, 255, 255, 0.7);
  margin-bottom: 40px;
  max-width: 480px;
}

.hero-buttons {
  display: flex;
  align-items: center;
  gap: 28px;
}

/* BUTTONS */
.explore-btn {
  background: transparent;
  border: 1.5px solid rgba(255, 255, 255, 0.3);
  color: white;
  padding: 14px 36px;
  border-radius: 30px;
  font-size: 15px;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s;
}

.explore-btn:hover {
  background: rgba(255, 255, 255, 0.1);
  border-color: rgba(255, 255, 255, 0.5);
}

.demo-btn {
  background: transparent;
  border: none;
  color: white;
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 15px;
  font-weight: 500;
  cursor: pointer;
  transition: opacity 0.2s;
}

.demo-btn:hover {
  opacity: 0.8;
}

.play-icon {
  width: 44px;
  height: 44px;
  border-radius: 50%;
  border: 1.5px solid rgba(255, 255, 255, 0.4);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 12px;
  padding-left: 3px;
}

/* HERO CARD */
.hero-card {
  width: 340px;
  min-width: 340px;
  background: rgba(255, 255, 255, 0.08);
  backdrop-filter: blur(20px);
  border-radius: 32px;
  padding: 24px;
  position: relative;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

.card-plant {
  width: 100%;
  max-width: 240px;
  display: block;
  margin: -80px auto 0;
  object-fit: contain;
}

.card-content {
  padding: 20px 8px 12px;
  text-align: center;
}

.card-label {
  font-size: 13px;
  color: rgba(255, 255, 255, 0.65);
  font-weight: 500;
  display: block;
  margin-bottom: 12px;
}

.card-title-row {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 12px;
  margin-bottom: 24px;
}

.card-title-row h3 {
  font-size: 24px;
  font-weight: 600;
  letter-spacing: -0.5px;
}

.arrow {
  font-size: 32px;
  font-weight: 300;
  color: rgba(255, 255, 255, 0.5);
}

.buy-btn {
  width: 100%;
  background: rgba(0, 0, 0, 0.6);
  border: none;
  color: white;
  padding: 14px;
  border-radius: 24px;
  font-size: 15px;
  font-weight: 600;
  cursor: pointer;
  margin-bottom: 20px;
  transition: background 0.3s;
}

.buy-btn:hover {
  background: rgba(0, 0, 0, 0.75);
}

.dots {
  display: flex;
  gap: 8px;
  justify-content: center;
}

.dots span {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.25);
  transition: all 0.3s;
}

.dots span.active {
  background: white;
  width: 24px;
  border-radius: 4px;
}

/* SECTIONS */
.section {
  margin-bottom: 100px;
}

.section h2 {
  font-size: 42px;
  font-weight: 700;
  text-align: center;
  margin-bottom: 56px;
  letter-spacing: -1px;
}

/* TRENDY */
.trendy-box {
  background: rgba(255, 255, 255, 0.06);
  border-radius: 32px;
  padding: 48px 56px;
  display: flex;
  align-items: center;
  gap: 80px;
  border: 1px solid rgba(255, 255, 255, 0.08);
}
.trendy-box {
  margin-bottom: 60px;   
}

.trendy-image {
  flex-shrink: 0;
  position: relative;
  overflow: visible;          
}
.trendy-image img {
  width: 360px;              
  height: auto;

  margin-top: -140px;        
  margin-bottom: -40px;      

  filter: drop-shadow(0 35px 45px rgba(0,0,0,0.45));
  transition: 0.35s ease;
}
.trendy-image img:hover {
  transform: translateY(-6px) scale(1.02);
}


.trendy-content {
  flex: 1;
}

.trendy-content h3 {
  font-size: 32px;
  font-weight: 700;
  margin-bottom: 20px;
  letter-spacing: -0.5px;
}

.trendy-content p {
  font-size: 15px;
  line-height: 1.7;
  color: rgba(255, 255, 255, 0.7);
  margin-bottom: 24px;
  max-width: 520px;
}

.price {
  display: block;
  font-size: 22px;
  font-weight: 600;
  margin-bottom: 32px;
}

.trendy-actions {
  display: flex;
  align-items: center;
  gap: 20px;
}

.explore-small {
  background: transparent;
  border: 1.5px solid rgba(255, 255, 255, 0.3);
  color: white;
  padding: 12px 32px;
  border-radius: 28px;
  font-size: 14px;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s;
}

.explore-small:hover {
  background: rgba(255, 255, 255, 0.1);
  border-color: rgba(255, 255, 255, 0.5);
}

.bag {
  width: 48px;
  height: 48px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
  cursor: pointer;
  transition: background 0.3s;
}

.bag:hover {
  background: rgba(255, 255, 255, 0.15);
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 28px;
  max-width: 1200px;
  margin: 0 auto;
}

/* PRODUCT CARD */
.product {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 20px;
  padding: 28px 20px;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  transition: all 0.3s;
  cursor: pointer;
}

.product:hover {
  background: rgba(255, 255, 255, 0.08);
  transform: translateY(-4px);
}

.product {
  background: rgba(255, 255, 255, 0.06);
  backdrop-filter: blur(14px);

  border-radius: 28px;

  padding: 95px 20px 28px;
  text-align: center;

  position: relative;
  overflow: visible;

  /* 🔥 GLASS BORDER */
  border: 1px solid rgba(255, 255, 255, 0.12);

  /* 🔥 OUTER GLOW */
  box-shadow:
    0 10px 30px rgba(0, 0, 0, 0.45),
    inset 0 0 0 rgba(255,255,255,0),
    0 0 18px rgba(76, 175, 139, 0.15);   /* soft green glow */

  transition: 0.3s ease;
}

/* 🔥 SUBTLE HOVER LIKE FIGMA */
.product:hover {
  transform: translateY(-6px);

  box-shadow:
    0 18px 45px rgba(0, 0, 0, 0.55),
    0 0 28px rgba(76, 175, 139, 0.35);  /* stronger glow */
}

.product img {
  width: 150px;
  height: 150px;

  position: absolute;
  top: -35px;
  left: 50%;
  transform: translateX(-50%);

  object-fit: contain;

  filter: drop-shadow(0 22px 35px rgba(0,0,0,0.55));
}

/* 🔥 TEXT POLISH */
.product h4 {
  font-size: 17px;
  margin-bottom: 6px;
}

.product p {
  font-size: 13px;
  opacity: 0.6;
  margin-bottom: 10px;
}

.product-price {
  font-size: 18px;
  font-weight: 600;
}

/* 🔥 SHOPPING ICON */
.product-price::after {
  content: " 🛍";
  font-size: 16px;
}


.product h4 {
  font-size: 18px;
  font-weight: 600;
  margin-bottom: 8px;
  letter-spacing: -0.3px;
}

.product p {
  font-size: 13px;
  color: rgba(255, 255, 255, 0.6);
  margin-bottom: 16px;
  line-height: 1.5;
}

.product-price {
  font-size: 16px;
  font-weight: 600;
  color: rgba(255, 255, 255, 0.95);
}
.reviews {
  display: grid;
  grid-template-columns: repeat(3, 1fr);   /* 🔥 ALWAYS 3 IN ROW */
  gap: 28px;

  max-width: 1100px;
  margin: 0 auto;
}

.review-card {
  background: rgba(255, 255, 255, 0.06);
  backdrop-filter: blur(14px);

  border-radius: 26px;
  padding: 22px;

  border: 1px solid rgba(255, 255, 255, 0.12);

  box-shadow:
    0 10px 30px rgba(0, 0, 0, 0.45),
    0 0 18px rgba(76, 175, 139, 0.12);
}

/* 🔥 IMAGE + NAME ROW */
.review-header {
  display: flex;
  align-items: center;
  gap: 12px;

  margin-bottom: 10px;
}

.review-img {
  width: 44px;
  height: 44px;
  border-radius: 50%;
  object-fit: cover;
}

/* 🔥 NAME */
.review-name {
  font-size: 15px;
  font-weight: 600;
  margin-bottom: 4px;
}

/* 🔥 STARS */
.review-stars {
  font-size: 13px;
  color: #ffd54f;
  letter-spacing: 2px;
}

/* 🔥 TEXT */
.review-card p {
  font-size: 13px;
  color: rgba(255, 255, 255, 0.65);
  line-height: 1.5;
  margin-top: 10px;
}

/* ✅ MOBILE STACK */
@media (max-width: 768px) {
  .reviews {
    grid-template-columns: 1fr;
  }
}

/* ✅ MOBILE */
@media (max-width: 768px) {

  .best-box {
    flex-direction: column;
    text-align: center;
    gap: 10px;
  }

  .best-content {
    text-align: center;
  }

  .best-image img {
    width: 210px;
    margin-top: -55px;
  }
}
.best-section {
  margin: 100px 0;
  text-align: center;
}

.best-title {
  font-size: 30px;
  margin-bottom: 55px;
}

/* 🔥 GLASS BOX */
.best-box {
  background: rgba(255, 255, 255, 0.06);
  border-radius: 32px;
  padding: 48px 56px;

  display: flex;
  align-items: center;
  gap: 70px;

  border: 1px solid rgba(255, 255, 255, 0.08);

  max-width: 1050px;
  margin: auto;

  position: relative;
}

/* 🔥 IMAGE (INSIDE + FLOATING SLIGHTLY) */
.best-image {
  flex-shrink: 0;
  position: relative;
  overflow: visible;
}

.best-image img {
  width: 260px;              /* ✅ NOT HUGE */
  height: auto;

  margin-top: -90px;         /* ✅ POP EFFECT */
  margin-bottom: -20px;

  filter: drop-shadow(0 30px 40px rgba(0,0,0,0.45));
}

/* 🔥 CONTENT */
.best-content {
  text-align: left;
}

.best-content h3 {
  font-size: 24px;
  margin-bottom: 16px;
}

.best-content p {
  font-size: 14px;
  line-height: 1.7;
  opacity: 0.7;
  margin-bottom: 14px;
  max-width: 480px;
}

/* 🔥 BUTTON */
.explore-btn {
  background: transparent;
  border: 1px solid rgba(255,255,255,0.35);
  color: white;

  padding: 10px 26px;
  border-radius: 24px;

  margin-top: 8px;
}

/* 🔥 FOOTER */
.best-footer {
  margin-top: 38px;
}

/* DOTS */
.slider-dots {
  display: flex;
  justify-content: center;
  gap: 8px;
  margin-bottom: 14px;
}

.slider-dots span {
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background: rgba(255,255,255,0.35);
}

.slider-dots .active {
  background: white;
}

/* CONTROLS */
.slider-controls {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;

  font-size: 20px;
}

.counter {
  font-size: 22px;
  font-weight: 600;
}

/* ✅ MOBILE */
@media (max-width: 768px) {

  .best-box {
    flex-direction: column;
    text-align: center;
    gap: 10px;
  }

  .best-content {
    text-align: center;
  }

  .best-image img {
    width: 210px;
    margin-top: -55px;
  }
}


/* FOOTER */
.footer {
  background: rgba(0, 0, 0, 0.3);
  border-top: 1px solid rgba(255, 255, 255, 0.08);
  padding: 60px 0 0;
  margin-top: 100px;
}

.footer-top {
  width: 100%;
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 60px 50px;
  display: grid;
  grid-template-columns: 2fr 1fr 1.5fr;
  gap: 80px;
}

.footer-brand {
  max-width: 400px;
}

.footer-logo {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 20px;
}

.footer-logo img {
  width: 40px;
  height: 40px;
  object-fit: contain;
}

.footer-logo span {
  font-size: 24px;
  font-weight: 700;
  letter-spacing: -0.5px;
}

.footer-brand p {
  font-size: 14px;
  line-height: 1.7;
  color: rgba(255, 255, 255, 0.65);
  margin-bottom: 28px;
}

.socials {
  display: flex;
  gap: 16px;
}

.socials span {
  width: 40px;
  height: 40px;
  background: rgba(255, 255, 255, 0.08);
  border: 1px solid rgba(255, 255, 255, 0.15);
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 12px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s;
}

.socials span:hover {
  background: rgba(255, 255, 255, 0.15);
  border-color: rgba(255, 255, 255, 0.3);
}

.footer-links {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.footer-links h4 {
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 8px;
  letter-spacing: -0.3px;
}

.footer-links a {
  color: rgba(255, 255, 255, 0.7);
  text-decoration: none;
  font-size: 14px;
  transition: color 0.2s;
}

.footer-links a:hover {
  color: white;
}

.footer-subscribe h4 {
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 20px;
  letter-spacing: -0.3px;
}

.subscribe-box {
  display: flex;
  gap: 12px;
}

.subscribe-box input {
  flex: 1;
  background: rgba(255, 255, 255, 0.08);
  border: 1px solid rgba(255, 255, 255, 0.15);
  border-radius: 8px;
  padding: 12px 16px;
  color: white;
  font-size: 14px;
  outline: none;
  transition: all 0.3s;
}

.subscribe-box input::placeholder {
  color: rgba(255, 255, 255, 0.5);
}

.subscribe-box input:focus {
  background: rgba(255, 255, 255, 0.12);
  border-color: rgba(255, 255, 255, 0.3);
}

.subscribe-box button {
  background: rgba(255, 255, 255, 0.15);
  border: 1px solid rgba(255, 255, 255, 0.2);
  color: white;
  padding: 12px 24px;
  border-radius: 8px;
  font-size: 13px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s;
  white-space: nowrap;
  letter-spacing: 0.5px;
}

.subscribe-box button:hover {
  background: rgba(255, 255, 255, 0.25);
  border-color: rgba(255, 255, 255, 0.4);
}

.footer-bottom {
  text-align: center;
  padding: 24px 0;
  border-top: 1px solid rgba(255, 255, 255, 0.08);
}

.footer-bottom span {
  font-size: 13px;
  color: rgba(255, 255, 255, 0.6);
}

/* MOBILE */
@media (max-width: 1024px) {
  .container,
  .footer-top {
    padding-left: 40px;
    padding-right: 40px;
  }

  .hero {
    gap: 60px;
  }

  .hero-left h1 {
    font-size: 56px;
  }

  .trendy-box {
    gap: 50px;
  }

  .footer-top {
    grid-template-columns: 1fr;
    gap: 50px;
  }
}

@media (max-width: 768px) {
  .container,
  .footer-top {
    padding-left: 24px;
    padding-right: 24px;
  }

  .navbar {
    flex-wrap: wrap;
    gap: 20px;
  }

  .nav-links {
    order: 3;
    width: 100%;
    justify-content: center;
    gap: 32px;
  }

  .hero {
    flex-direction: column;
    gap: 40px;
    text-align: center;
  }

  .hero-left {
    max-width: 100%;
  }

  .hero-left h1 {
    font-size: 48px;
  }

  .hero-desc {
    max-width: 100%;
  }

  .hero-buttons {
    justify-content: center;
  }

  .hero-card {
    width: 100%;
    max-width: 380px;
  }

  .trendy-box {
    flex-direction: column;
    text-align: center;
    padding: 40px 32px;
  }

  .trendy-actions {
    justify-content: center;
  }

  .reviews {
    grid-template-columns: 1fr;
    gap: 48px;
  }

  .section h2 {
    font-size: 36px;
  }

  .subscribe-box {
    flex-direction: column;
  }
}

@media (max-width: 480px) {
  .hero-left h1 {
    font-size: 40px;
  }

  .grid {
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 20px;
  }

  .section h2 {
    font-size: 32px;
  }
}
</style>