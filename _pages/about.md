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
  <p class="title"><i>Ph.D. Student</i></p>
  <p class="affiliation"><a href="https://erau.edu" target="_blank">Georgia Institute of Technology</a></p>
  <p class="contact"><a href="mailto:bossie@my.erau.edu">bossie@my.erau.edu</a></p>

  <!-- LinkedIn Icon -->
  <div class="social-icons">
    <a href="https://www.linkedin.com/in/emanuele-bossi" target="_blank">
      <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/linkedin.svg" alt="LinkedIn" class="linkedin-icon">
    </a>
  </div>
  
</div>
{% endraw %}

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
    <img src="/images/georgia_tech_logo.png" alt="Georgia Tech" />
    <img src="/images/20TWENTIES_winner_badge.png" alt="20Twenties" />
    <img src="/images/issnaf_logo_2.png" alt="ISSNAF" />
    <img src="/images/italia_flag.webp" alt="Italy" />
    <img src="/images/usa_flag.webp" alt="USA" />

    <img src="/images/wvu_logo.webp" alt="WVU" />
    <img src="/images/erau_logo.png" alt="ERAU" />
    <img src="/images/purdue_logo.png" alt="Purdue" />
    <img src="/images/georgia_tech_logo.png" alt="Georgia Tech" />
    <img src="/images/20TWENTIES_winner_badge.png" alt="20Twenties" />
    <img src="/images/issnaf_logo_2.png" alt="ISSNAF" />
    <img src="/images/italia_flag.webp" alt="Italy" />
    <img src="/images/usa_flag.webp" alt="USA" />
    
    <img src="/images/wvu_logo.webp" alt="WVU" />
    <img src="/images/erau_logo.png" alt="ERAU" />
    <img src="/images/purdue_logo.png" alt="Purdue" />
    <img src="/images/georgia_tech_logo.png" alt="Georgia Tech" />
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

I am a Ph.D. student in *Machine Learning* at the **Georgia Institute of Technology**, where I work with [*Dr. Matthew Hale*](https://research.gatech.edu/people/matthew-hale) in the *Controls, Optimization, Robotics Engineering (CORE) Laboratory*. My research focuses on anomaly detection, change-point detection, and the intersection of machine learning, control theory, and dynamical systems.

I earned dual B.S. degrees, *Summa Cum Laude*, in Software Engineering and Data Science from **Embry-Riddle Aeronautical University**, along with a minor in Mathematics. During my undergraduate studies, I contributed to several [research projects](https://bossiemanuele.github.io/portfolio/) under the mentorship of *Dr. Abd AlRahman AlMomani*, *Dr. Andri M. Gretarsson*, and other faculty members, working on topics spanning machine learning, network science, scientific computing, and autonomous systems. In Summer 2025, I joined the [*Jain Research Lab*](https://engineering.purdue.edu/JainResearchLab/) at **Purdue University** as a *Visiting Research Fellow*, conducting research on human cognition and automation in safety-critical systems.

My work and academic journey have been recognized through several honors and awards. I was selected as a recipient of the [**Aviation Week Network 20 Twenties Award**](https://www.einpresswire.com/article/880869714/aviation-week-network-announces-class-of-2026-20-twenties-winners), [Class of 2026](https://20twenties.aviationweek.com/winners/winners1/), recognizing emerging leaders expected to shape the future of the aerospace, aviation, and defense industries. At Embry-Riddle, I received the **Chancellor’s Award**, the university’s highest distinction for a graduating senior, recognizing exceptional academic achievement, leadership, and service to the campus community. Additional recognitions include the **College of Engineering Outstanding Graduate Award**, the **Phi Kappa Phi Top Scholar Award**, and the **IEEE-HKN Top Graduate Award**.

<div style="
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
">

  <h2 style="margin: 0;">Recent News</h2>

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

<hr>

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
