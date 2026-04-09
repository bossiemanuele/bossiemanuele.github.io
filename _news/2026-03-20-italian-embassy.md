---
title: "Visit to the Italian Embassy in Washington, D.C."
date: 2026-03-20
image: /images/italia_flag.webp
excerpt: "Invited to the Italian Embassy and met with the Science and Space Attachés."
layout: single
author_profile: false
---

Proud to be Italian! I was honored to be invited to the **Italian Embassy** in Washington, D.C., where I had the privilege of meeting the **Science Attaché** and the **Space Attaché**.

<div class="auto-carousel">
  <div class="auto-carousel-track">
    <img src="/images/ItalianEmbassy1.jpg" alt="Italian Embassy photo 1">
    <img src="/images/ItalianEmbassy2.jpg" alt="Italian Embassy photo 2">
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
