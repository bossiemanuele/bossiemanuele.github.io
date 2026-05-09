---
title: "B.S. Graduation – Embry-Riddle Aeronautical University"
date: 2026-04-24
image: /images/gradcap.avif
excerpt: "Graduated Summa Cum Laude from Embry-Riddle Aeronautical University with dual degrees in Software Engineering and Data Science."
layout: single
author_profile: false
---

I officially graduated from **Embry-Riddle Aeronautical University** with:

- **B.S. in Software Engineering**, *Summa Cum Laude* (4.0 GPA)  
- **B.S. in Data Science**, *Summa Cum Laude* (4.0 GPA)  
- **Minor in Mathematics** (4.0 GPA)

This journey has been one of the most transformative experiences of my life. Moving from Italy to the United States at 18 years old, adapting to a new culture and language, balancing academics, research, leadership, and athletics, and pursuing excellence every day came with both challenges and unforgettable opportunities.

During my time at Embry-Riddle, I had the privilege of conducting research in machine learning, control systems, network science, and human-centered AI, contributing to multiple projects and conference publications. Beyond academics, I served as Founder & President of the Data Science Club, competed as a student-athlete on the Men’s Soccer team, and had the opportunity to work alongside incredible professors, mentors, teammates, and friends who profoundly shaped my journey.

I am deeply grateful to my family, professors, collaborators, and everyone who supported me throughout these years. None of this would have been possible without their guidance and encouragement.

As one chapter closes, another begins...

<div class="auto-carousel">
  <div class="auto-carousel-track">
    <img src="/images/graduation1.jpg" alt="Graduation photo 1">
    <img src="/images/graduation2.jpg" alt="Graduation photo 2">
    <img src="/images/graduation3.jpg" alt="Graduation photo 3">
  </div>
</div>

<style>
.auto-carousel {
  width: 100%;
  max-width: 700px;
  margin: 2rem auto;
  overflow: hidden;
  border-radius: 12px;
}

.auto-carousel-track {
  display: flex;
  transition: transform 0.8s ease-in-out;
}

.auto-carousel-track img {
  width: 100%;
  flex: 0 0 100%;
  height: 400px;
  object-fit: contain;
  background: #f5f5f5;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const track = document.querySelector(".auto-carousel-track");
  if (!track) return;

  const slides = Array.from(track.children);
  let index = 0;

  function updateCarousel() {
    track.style.transform = `translateX(-${index * 100}%)`;
  }

  setInterval(() => {
    index = (index + 1) % slides.length;
    updateCarousel();
  }, 3000);
});
</script>
