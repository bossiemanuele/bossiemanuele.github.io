---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% raw %}
<!-- 👤 Header Section -->
<div class="hero-header">
  <h1><b>Emanuele Bossi</b></h1>
  <p class="title"><i>Undergraduate Student</i></p>
  <p class="affiliation"><a href="https://erau.edu" target="_blank">Embry‑Riddle Aeronautical University</a></p>
  <p class="contact"><a href="mailto:bossie@my.erau.edu">bossie@my.erau.edu</a></p>

  <!-- LinkedIn Icon -->
  <div class="social-icons">
    <a href="https://www.linkedin.com/in/emanuele-bossi" target="_blank">
      <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/linkedin.svg" alt="LinkedIn" class="linkedin-icon">
    </a>
  </div>
  
</div>
{% endraw %}

<div style="border: 2px solid red; padding: 16px; border-radius: 8px;">

Starting in Fall 2026, I will join <strong>UniversityName</strong>, where I will pursue a <strong>Ph.D. in Machine Learning</strong>. I am excited to work with <strong>Dr. ProfessorName</strong> and be part of his research group.

(DETAILS WILL BE ANNOUNCED SOON!)

</div>

---

<style>
.hero-header {
  text-align: center;
  margin-top: 30px;
  margin-bottom: 40px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  color: #333;
}

.hero-header h1 {
  font-size: 1.8em;
  margin-bottom: 0.1em;
  font-weight: 500;
}

.hero-header p {
  font-size: 0.95em;
  margin: 2px 0;
  line-height: 1.3;
  color: #444;
}

.hero-header .affiliation a,
.hero-header .contact a {
  color: #007acc;
  text-decoration: none;
  font-weight: normal;
}

.hero-header .affiliation a:hover,
.hero-header .contact a:hover {
  text-decoration: underline;
}

.social-icons {
  margin-top: 8px;
}

.linkedin-icon {
  width: 22px;
  height: 22px;
  filter: invert(33%) sepia(95%) saturate(800%) hue-rotate(176deg) brightness(100%) contrast(92%);
  transition: transform 0.2s ease;
  vertical-align: middle;
}

.linkedin-icon:hover {
  transform: scale(1.1);
}
</style>

<!-- 🔄 Auto-scrolling Mini Banner -->
<div class="mini-banner-container">
  <div class="mini-banner-track">
    <!-- Logos duplicated for seamless loop -->
    <img src="/images/wvu_logo.webp" alt="WVU" />
    <img src="/images/erau_logo.png" alt="ERAU" />
    <img src="/images/purdue_logo.png" alt="Purdue" />
    <img src="/images/20TWENTIES_winner_badge.png" alt="20Twenties" />
    <img src="/images/issnaf_logo_2.png" alt="ISSNAF" />
    <img src="/images/italia_flag.webp" alt="Italy" />
    <img src="/images/usa_flag.webp" alt="USA" />

    <img src="/images/wvu_logo.webp" alt="WVU" />
    <img src="/images/erau_logo.png" alt="ERAU" />
    <img src="/images/purdue_logo.png" alt="Purdue" />
    <img src="/images/20TWENTIES_winner_badge.png" alt="20Twenties" />
    <img src="/images/issnaf_logo_2.png" alt="ISSNAF" />
    <img src="/images/italia_flag.webp" alt="Italy" />
    <img src="/images/usa_flag.webp" alt="USA" />
    
    <img src="/images/wvu_logo.webp" alt="WVU" />
    <img src="/images/erau_logo.png" alt="ERAU" />
    <img src="/images/purdue_logo.png" alt="Purdue" />
    <img src="/images/20TWENTIES_winner_badge.png" alt="20Twenties" />
    <img src="/images/issnaf_logo_2.png" alt="ISSNAF" />
    <img src="/images/italia_flag.webp" alt="Italy" />
    <img src="/images/usa_flag.webp" alt="USA" />
  </div>
</div>

<style>
.mini-banner-container {
  overflow: hidden;
  width: 100%;
  border-top: 1px solid #eee;
  border-bottom: 1px solid #eee;
  padding: 6px 0;
  margin-bottom: 20px;
}

.mini-banner-track {
  display: flex;
  align-items: center;
  gap: 18px;
  white-space: nowrap;
  animation: scroll-mini 10s linear infinite;
}

.mini-banner-track img {
  height: 28px;
  width: auto;
  vertical-align: middle;
  opacity: 0.8;
  filter: grayscale(60%);
}

@keyframes scroll-mini {
  0% {
    transform: translateX(0%);
  }
  100% {
    transform: translateX(-50%);
  }
}
</style>

I am an Undergraduate student at **Embry-Riddle Aeronautical University** in the *College of Engineering* and *College of Arts & Sciences*. I am dual major in **Data Science** and **Software Engineering**, with a minor in **Mathematics**. I am an **Undergraduate Researcher** in the *Undergraduate Research Institute*, working in multiple [**Research Projects**](https://bossiemanuele.github.io/portfolio/) under the mentorship of *Dr. Abd AlRahman AlMomani*, Assistant Professor of Data Science and Mathematics and Data Science Program Coordinator, and *Dr. Andri M. Gretarrson*, Professor of Physics. Moreover, I am a [**Teaching Assistant**](https://bossiemanuele.github.io/teaching/) for Professor *Timothy King* and Professor *Christopher Warner*. During Summer 2025, I joined as *Visiting Research Fellow* the [**Jain Research Lab**](https://engineering.purdue.edu/JainResearchLab/) at **Purdue University**.

My **research interests** focus on *machine learning theory*, particularly inference and learning in high-dimensional systems with low-dimensional structure, including networked and dynamical settings.

I had the pleasure of being recognized with several awards. I was selected as a recipient of the [**Aviation Week Network's 20 Twenties Award**](https://www.einpresswire.com/article/880869714/aviation-week-network-announces-class-of-2026-20-twenties-winners), [Class of 2026](https://20twenties.aviationweek.com/winners/winners1/) which recognizes "talented individuals on course to change the face of the aviation, aerospace and defense industry." At Embry-Riddle Aeronautical University, I was awarded the **Chancellor’s Award**, the highest distinction bestowed upon a graduating senior, honoring exceptional academic achievement alongside a strong record of leadership and campus involvement. I was also recognized by the Phi Kappa Phi Honor Society with the **Top Scholar Award**, celebrating outstanding academic excellence among graduating seniors.

## Recent News

## News

{% assign recent_news = site.news | sort: "date" | reverse | slice: 0, 3 %}

<div class="news-home">

  {% for post in recent_news %}
  <div class="news-item">
    
    <div class="news-date">
      {{ post.date | date: "%B %Y" }}
    </div>

    {% if post.image %}
    <img src="{{ post.image }}" alt="{{ post.title }}" class="news-image">
    {% endif %}

    <div class="news-text">
      <a href="{{ post.url | relative_url }}" style="color: inherit; text-decoration: underline; text-underline-offset: 3px;">
        <strong>{{ post.title }}</strong>
      </a><br>
      {{ post.excerpt }}
    </div>

  </div>
  {% endfor %}

</div>

<div style="text-align: right; margin-top: 18px;">
  <a href="{{ '/news/' | relative_url }}" style="
    text-decoration: none;
    font-size: 14px;
    padding: 6px 12px;
    border-radius: 6px;
    border: 1px solid #ccc;
    background: #f8f9fb;
    color: inherit;
    display: inline-block;
  ">
    📰 View full news archive
  </a>
</div>

<style>
.news-home {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.news-item {
  display: flex;
  align-items: flex-start;
  gap: 15px;
  padding-bottom: 12px;
  border-bottom: 1px solid #e0e0e0;
}

.news-date {
  font-size: 0.85em;
  color: #555;
  min-width: 100px;
  flex-shrink: 0;
}

.news-image {
  width: 60px;
  height: 60px;
  object-fit: contain;
  border-radius: 8px;
  flex-shrink: 0;
}

.news-text {
  font-size: 0.95em;
  line-height: 1.4;
}
</style>

<br>
<br>
<br>




{% raw %}
<h2 style="font-size: 1.6em; font-weight: bold; margin-top: 30px; text-align: center;">
  Media Coverage
</h2>
<!-- ===================== NEWS CAROUSEL (FULL WORKING BLOCK) ===================== -->

<div class="news-carousel-container" id="newsCarousel">

  <div class="news-carousel-track" id="mediaCarouselTrack">

    <div class="news-carousel-item">
      <a href="https://bossiemanuele.github.io/files/Intervista Emanuele Bossi.pdf" target="_blank">
        <h3>"Guardavo gli aerei in volo e ora li rendo intelligenti”</h3>
      </a>
      <img src="/images/LaPrealpNews.png" alt="">
    </div>
    
    <div class="news-carousel-item">
      <a href="https://www.varesenews.it/2026/01/emanuele-bossi-di-gallarate-primo-italiano-premiato-con-laviation-week-network-20-twenties-award/2453560/" target="_blank">
        <h3>Emanuele Bossi di Gallarate primo italiano premiato con l’Aviation Week Network “20 Twenties Award”</h3>
      </a>
      <img src="/images/emanuele-bossi-gallarate-2016139.610x431.jpg" alt="">
    </div>
    
    <div class="news-carousel-item">
      <a href="https://www.prealpina.it/pages/un-gallaratese-tra-gli-under30-campioni-di-aviazione-401415.html" target="_blank">
        <h3>Un gallaratese tra gli under 30 “campioni di aviazione” nel mondo</h3>
      </a>
      <img src="/images/GN4_DAT_48366927.jpg" alt="">
    </div>
    
    <div class="news-carousel-item">
      <a href="https://www.malpensa24.it/gallarate-usa-aviation-week/" target="_blank">
        <h3>Da Gallarate agli Usa: studente premiato da Aviation Week. E’ il primo italiano</h3>
      </a>
      <img src="/images/20251202-AgriAI-8852.jpg" alt="">
    </div>
    
    <div class="news-carousel-item">
      <a href="https://news.erau.edu/headlines/six-embry-riddle-students-honored-aviation-week-20-twenties-list" target="_blank">
        <h3>Six Embry‑Riddle Students Honored in Aviation Week’s Prestigious 20 Twenties List</h3>
      </a>
      <img src="/images/embry-riddle-twenty-20-2026.jpg" alt="">
    </div>
    
    <div class="news-carousel-item">
      <a href="https://news.erau.edu/headlines/embry-riddle-students-shine-on-national-stage-at-undergraduate-research-conference" target="_blank">
        <h3>Embry-Riddle Students Shine on National Stage at Undergraduate Research Conference</h3>
      </a>
      <img src="/images/erau-team-ncur.jpg" alt="">
    </div>

    <div class="news-carousel-item">
      <a href="https://news.erau.edu/headlines/embry-riddle-student-team-plants-the-seed-for-smart-farming-system" target="_blank">
        <h3>Embry-Riddle Student Team Plants the Seed for Smart Farming System</h3>
      </a>
      <img src="/images/iftp_texas.jpg" alt="">
    </div>

    <div class="news-carousel-item">
      <a href="https://news.erau.edu/headlines/a-record-year-for-student-research-projects-showcased-at-annual-embry-riddle-symposiums" target="_blank">
        <h3>A Record Year for Student Research Projects Showcased at Annual Embry-Riddle Symposiums</h3>
      </a>
      <img src="/images/erau-symposium.jpeg" alt="">
    </div>

    <div class="news-carousel-item">
      <a href="https://erau.edu/hub-spoke/stories/blending-athletics-and-academia-a-journey-of-dedication-and-passion" target="_blank">
        <h3>Blending Athletics and Academia: A Journey of Dedication and Passion</h3>
      </a>
      <img src="/images/bossi_erau_article.jpg" alt="">
    </div>

  </div>

  <!-- Navigation -->
  <button class="carousel-arrow left" onclick="carouselPrev()">&#10094;</button>
  <button class="carousel-arrow right" onclick="carouselNext()">&#10095;</button>

</div>

<style>
.news-carousel-container {
  width: 100%;
  max-width: 700px;
  height: 380px;
  overflow: hidden;
  position: relative;
  margin: 20px auto;
  border: 1px solid #ddd;
}

.news-carousel-track {
  display: flex;
  transition: transform 0.6s ease;
}

.news-carousel-item {
  flex: 0 0 100%;
  text-align: center;
  padding: 15px;
}

.news-carousel-item img {
  width: 100%;
  height: 280px;
  object-fit: cover;
  border-radius: 8px;
}

.carousel-arrow {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.6);
  color: #fff;
  border: none;
  font-size: 26px;
  padding: 8px 12px;
  cursor: pointer;
  z-index: 10;
  border-radius: 50%;
}

.carousel-arrow.left { left: 10px; }
.carousel-arrow.right { right: 10px; }
</style>

<script>
/* ======= NO DOMContentLoaded, NO EVENT LISTENERS ======= */

let carouselIndex = 0;
const carouselTrack = document.getElementById("mediaCarouselTrack");
const carouselItems = document.getElementsByClassName("news-carousel-item");
const carouselContainer = document.getElementById("newsCarousel");

function carouselUpdate() {
  const width = carouselContainer.offsetWidth;
  carouselTrack.style.transform =
    "translateX(" + (-carouselIndex * width) + "px)";
}

function carouselNext() {
  carouselIndex = (carouselIndex + 1) % carouselItems.length;
  carouselUpdate();
}

function carouselPrev() {
  carouselIndex =
    (carouselIndex - 1 + carouselItems.length) % carouselItems.length;
  carouselUpdate();
}

/* Auto scroll */
setInterval(carouselNext, 5000);

/* Resize safety */
window.onresize = carouselUpdate;

/* Initial position */
carouselUpdate();
</script>

<!-- ===================== END NEWS CAROUSEL ===================== -->


{% endraw %}
