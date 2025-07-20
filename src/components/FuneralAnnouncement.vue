<template>
  <main class="minimal-bg" aria-label="Funeral Announcement">
    <section class="minimal-hero" role="banner">
      <img
        class="minimal-hero-photo"
        :src="mainImg"
        alt="Philip Tawiah Narh Memorial Photo"
      />
      <div class="minimal-hero-text">
        <h1 class="minimal-hero-title">In Loving Memory of</h1>
        <h2 class="minimal-hero-name">Philip Tawiah Narh</h2>
        <p class="minimal-hero-dates">May 1958 – June 2025</p>
        <p class="minimal-hero-quote">"To live in hearts we leave behind is not to die."</p>
      </div>
    </section>


    <section class="minimal-card" role="region" aria-label="Life Message">
      <p class="minimal-message">
        It is with deep sorrow that the family announces the sudden passing of our beloved
        <strong>Dr. Philip Tawiah Narh</strong>, whose gentle spirit, wisdom, and humility touched all who knew him. His legacy lives on in our hearts.
      </p>
    </section>

    <a href="https://maps.google.com/?q=5.856178,-0.108333" target="_blank" rel="noopener" class="minimal-map-link" aria-label="View location on Google Maps">
        📍 View Location on Map
      </a>

    <section class="minimal-card" role="region" aria-label="Funeral Rites">
      <h3 class="minimal-card-title">Funeral Rites</h3>
      <div class="minimal-funeral-grid">
        <div>
          <span class="minimal-label">Laying in State:</span><br/>
          <span class="text-black">Presbyterian Church, Kpone Bawaleshie<br /> <b>Saturday, 26th July 2025  8:00 AM</b></span>
        </div>
        <div>
          <span class="minimal-label">Burial:</span><br/>
          <span>Same Day<br />Kpone Bawaleshie Public Cemetery</span>
        </div>
        <div>
          <span class="minimal-label">Thanksgiving Service:</span><br/>
          <span>Sunday, 27th July 2025<br />Presbyterian Church, Peniel Congregation<br />9:30 AM</span>
        </div>
        <div>
          <span class="minimal-label">Dress Code:</span><br/>
          <span class="minimal-dress-code">White</span>
        </div>
      </div>
      
    </section>


    <section class="minimal-card minimal-footer" role="contentinfo">
      <div class="minimal-footer-text">
        All sympathisers and well-wishers are cordially invited.<br />
        <span class="minimal-footer-verse">“Blessed are those who mourn, for they shall be comforted.” – Matthew 5:4</span>
      </div>
      <a href="https://wa.me/+233592797074" class="minimal-contact-btn" aria-label="Contact the family on WhatsApp" target="_blank" rel="noopener">Contact the Family on WhatsApp</a>
    </section>
  </main>
</template>

<script setup>
import mainImg from '../assets/philip/main.jpg'
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=EB+Garamond:wght@400;600&display=swap');

.minimal-bg {
  min-height: 100vh;
  background: #f8fafc;
  font-family: 'Inter', Arial, sans-serif;
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.minimal-hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin: 2.5rem 0 2rem 0;
  width: 100%;
}
.minimal-hero-photo {
  width: 140px;
  height: 140px;
  object-fit: cover;
  border-radius: 50%;
  border: 3px solid #e9ecef;
  margin-bottom: 1.2rem;
  background: #fff;
}
.minimal-hero-text {
  text-align: center;
}
.minimal-hero-title {
  font-size: 1.1rem;
  font-family: 'EB Garamond', serif;
  color: #4f8a8b;
  font-weight: 600;
  margin-bottom: 0.2rem;
  letter-spacing: 1px;
}
.minimal-hero-name {
  font-size: 2rem;
  font-family: 'EB Garamond', serif;
  font-weight: 700;
  color: #22223b;
  margin-bottom: 0.2rem;
}
.minimal-hero-dates {
  color: #868e96;
  font-size: 1.05rem;
  font-family: 'EB Garamond', serif;
  margin-bottom: 0.2rem;
}
.minimal-hero-quote {
  color: #495057;
  font-size: 1rem;
  font-style: italic;
  opacity: 0.8;
  font-family: 'EB Garamond', serif;
}
.minimal-card {

  border-radius: 1.1rem;
  margin: 0 auto 1.5rem auto;
  max-width: 540px;
  width: 95vw;
  padding: 1.7rem 1.2rem;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.minimal-card-title {
  font-size: 1.1rem;
  font-family: 'EB Garamond', serif;
  color: #000;
  font-weight: 600;
  margin-bottom: 1rem;
  letter-spacing: 0.5px;
}
.minimal-message {
  color: #22223b;
  font-size: 1.08rem;
  line-height: 1.7;
  text-align: center;
  width: 100%;
}
.minimal-funeral-grid {
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
  width: 100%;
  color: #000;
  margin-bottom: 1.2rem;
}
.minimal-label {
  font-weight: 600;
  color: #000;
  font-family: 'EB Garamond', serif;
  margin-bottom: 0.1rem;
  font-size: 1.05rem;
}
.minimal-dress-code {
  font-weight: 600;
  color: #22223b;
  background: #fbd46d33;
  border-radius: 0.5rem;
  padding: 0.1rem 0.5rem;
  display: inline-block;
}
.minimal-map-link {
  display: inline-block;
  margin-top: 1rem;
  background: #4f8a8b;
  color: #fff;
  font-weight: 600;
  padding: 0.5rem 1.4rem;
  border-radius: 2rem;
  text-decoration: none;
  font-size: 1rem;
  box-shadow: 0 2px 8px 0 rgba(60,60,60,0.08);
  transition: background 0.2s, box-shadow 0.2s, transform 0.2s;
}
.minimal-map-link:hover {
  background: #357376;
  box-shadow: 0 4px 16px 0 rgba(60,60,60,0.13);
  transform: translateY(-2px) scale(1.03);
}
.minimal-survivors-list {
  color: #22223b;
  font-size: 1rem;
  padding-left: 1.2rem;
  margin: 0;
  list-style: disc inside;
  width: 100%;
}
.minimal-footer {
  align-items: center;
  text-align: center;
  background: #f8fafc;
  border: 1px solid #e0e7ff;
  margin-bottom: 2.5rem;
}
.minimal-footer-text {
  color: #000;
  font-size: 1rem;
  margin-bottom: 1rem;
}
.minimal-footer-verse {
  display: block;
  margin-top: 0.5rem;
  font-style: italic;
  color: #000;
  font-family: 'EB Garamond', serif;
}
.minimal-contact-btn {
  display: inline-block;
  margin-top: 1rem;
  background: #4f8a8b;
  color: #fff;
  font-weight: 600;
  padding: 0.6rem 1.6rem;
  border-radius: 2rem;
  text-decoration: none;
  font-size: 1.05rem;
  box-shadow: 0 2px 8px 0 rgba(60,60,60,0.08);
  transition: background 0.2s, box-shadow 0.2s, transform 0.2s;
}
.minimal-contact-btn:hover {
  background: #357376;
  box-shadow: 0 4px 16px 0 rgba(60,60,60,0.13);
  transform: translateY(-2px) scale(1.03);
}
@media (max-width: 700px) {
  .minimal-hero-photo {
    width: 100px;
    height: 100px;
  }
  .minimal-card {
    padding: 1.1rem 0.5rem;
  }
  .minimal-funeral-grid {
    grid-template-columns: 1fr;
    gap: 1rem;
  }
}
</style>
