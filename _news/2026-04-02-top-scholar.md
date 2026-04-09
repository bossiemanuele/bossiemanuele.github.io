---
title: "Top Scholar Award – Phi Kappa Phi"
date: 2026-04-02
image: /images/phi_kappa_phi.png
excerpt: "Recognized for outstanding academic achievement as a graduating senior."
layout: single
author_profile: false
---

I am honored to have received the **Top Scholar Award** from the Phi Kappa Phi Honor Society, recognizing the outstanding academic achievements of a graduating senior.

<div class="award-carousel">
  <div class="award-carousel-track">
    <img src="/images/phi1.jpg" alt="Phi Kappa Phi photo 1">
    <img src="/images/phi2.jpg" alt="Phi Kappa Phi photo 2">
    <img src="/images/phi3.jpg" alt="Phi Kappa Phi photo 3">
  </div>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const track = document.querySelector(".award-carousel-track");
  if (!track) return;

  const slides = track.children;
  let index = 0;

  function showSlide(i) {
    track.style.transform = `translateX(-${i * 100}%)`;
  }

  setInterval(() => {
    index = (index + 1) % slides.length;
    showSlide(index);
  }, 3000);
});
</script>
