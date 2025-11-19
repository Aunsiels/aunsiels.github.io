---
layout: page
title: "Extras"
---

Outside research and teaching, I enjoy exploring creative activities and personal side projects.  
They help me stay curious, grounded, and connected to things I simply love doing.

---

## Side Projects

I love building things—small tools, websites, experiments, games.  
Some projects are technical, others playful, but all come from the same place:  
the joy of creating something from scratch.

Here are some of the side projects I’ve worked on:

### Software & Tools
- **Pyformlang** — A Python library to manipulate formal languages.  
  <https://github.com/Aunsiels/pyformlang>
- **LocalHelix** — Your Personal DNA Analyzer.  
  Get insights on your DNA without sending your data to external companies.  
  <https://github.com/Aunsiels/LocalHelix>
- **Wireless sensors network for performance monitoring**  
  <https://github.com/Aunsiels/Mesh_Bee>

### Web projects
- **Tuftlab** — A website to compute the yarn required for tufting projects.  
  <https://www.tuftlab.app/>
- **Seluna** — A booking website for a Love Room experience.  
  <https://www.seluna.fr/>

### IoT & Hardware
- **BumpBand** — A connected bracelet.  
  <https://github.com/projetpact41/bumpband>
- **Kudly** — A connected teddy bear.  
  <https://github.com/Aunsiels/Kudly>

### Video games (Ludum Dare game jam)
- **IG/IRL** — Ludum Dare 37  
  <https://aun.itch.io/igirl>
- **The Art of the Rope** — Ludum Dare 36  
  <https://aun.itch.io/the-art-of-the-rope>
- **Pick & Build** — Ludum Dare 34  
  <https://aun.itch.io/pickbuild>
- **Monster Defense** — Ludum Dare 33  
  <https://aun.itch.io/monster-defense>

---

## Music

Music has been part of my life for a long time.  
I sing as a **tenor** (both solo and in choir), and I also play **guitar**, **violin**,  
and a bit of **piano**.  

I studied voice at the **conservatory**, where I learned classical technique  
and ensemble singing.  

Even though it is purely a passion and not something I do professionally,  
it’s one of my favorite ways to disconnect, breathe, and create something beautiful.

---

## Drawing, Photos & Sewing

I enjoy **sketching**, taking **photographs**, and occasionally **sewing**.  
These are casual hobbies—simple ways to slow down, observe the world,  
and experiment with textures, light, and shapes.

### Gallery  

<div class="gallery">
  <img src="{{ '/assets/img/gallery/drawing1.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing2.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing3.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing4.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing5.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing6.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing7.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing8.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing9.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing10.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/drawing11.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/photo1.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/photo2.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/photo3.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/img/gallery/oil1.jpg' | relative_url }}" alt="">
</div>

<div id="lightbox" class="lightbox">
  <span class="lightbox-close">&times;</span>
  <img class="lightbox-content" id="lightbox-img">
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var galleryImages = document.querySelectorAll('.gallery img');
  var lightbox = document.getElementById('lightbox');
  var lightboxImg = document.getElementById('lightbox-img');
  var lightboxClose = document.querySelector('.lightbox-close');

  galleryImages.forEach(function(img) {
    img.addEventListener('click', function() {
      lightbox.style.display = 'flex';
      lightboxImg.src = this.src;
    });
  });

  lightboxClose.addEventListener('click', function() {
    lightbox.style.display = 'none';
    lightboxImg.src = '';
  });

  lightbox.addEventListener('click', function(e) {
    if (e.target === lightbox) {
      lightbox.style.display = 'none';
      lightboxImg.src = '';
    }
  });
});
</script>


---


These activities remind me that creativity takes many forms,  
and that research is only one piece of a larger picture.

