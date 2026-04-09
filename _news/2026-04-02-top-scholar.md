---
title: "Top Scholar Award – Phi Kappa Phi"
date: 2026-04-02
image: /images/phi_kappa_phi.png
excerpt: "Recognized for outstanding academic achievement as a graduating senior."
layout: single
author_profile: false
---

I am honored to have received the **Top Scholar Award** from the Phi Kappa Phi Honor Society, recognizing the outstanding academic achievements of a graduating senior.

<div class="auto-carousel">
  <div class="auto-carousel-track">
    <img src="/images/phi1.jpg" alt="Phi Kappa Phi photo 1">
    <img src="/images/phi2.jpg" alt="Phi Kappa Phi photo 2">
    <img src="/images/phi3.jpg" alt="Phi Kappa Phi photo 3">
    <img src="/images/phi4.jpg" alt="Phi Kappa Phi photo 4">
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
  object-fit: contain; /* use 'cover' if you prefer cropping */
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
