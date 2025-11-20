---
layout: page
title: "Extras"
---

En dehors de la recherche et de l’enseignement, j’aime explorer des activités créatives  
et réaliser des projets personnels.  
Cela m’aide à rester curieux, équilibré, et connecté à des choses que j’aime simplement faire.

---

## Projets personnels

J’aime construire des choses : outils, sites web, expériences, jeux vidéo…  
Certains projets sont techniques, d’autres plus ludiques,  
mais tous naissent du même plaisir : créer quelque chose de zéro.

Voici quelques projets auxquels j’ai participé :

### Logiciels & outils
- **Pyformlang** — Une bibliothèque Python pour manipuler les langages formels.  
  <https://github.com/Aunsiels/pyformlang>
- **LocalHelix** — Analyseur ADN personnel.  
  Permet d’obtenir des insights sans envoyer ses données à des entreprises externes.  
  <https://github.com/Aunsiels/LocalHelix>
- **Réseau de capteurs sans fil pour le monitoring de performances**  
  <https://github.com/Aunsiels/Mesh_Bee>

### Projets web
- **Tuftlab** — Un site pour calculer la quantité de laine nécessaire pour un projet de tufting.  
  <https://www.tuftlab.app/>
- **Seluna** — Un site de réservation pour une Love Room.  
  <https://www.seluna.fr/>

### IoT & objets connectés
- **BumpBand** — Un bracelet connecté.  
  <https://github.com/projetpact41/bumpband>
- **Kudly** — Un ours en peluche connecté.  
  <https://github.com/Aunsiels/Kudly>

### Jeux vidéo (Ludum Dare game jam)
- **IG/IRL** — Ludum Dare 37  
  <https://aun.itch.io/igirl>
- **The Art of the Rope** — Ludum Dare 36  
  <https://aun.itch.io/the-art-of-the-rope>
- **Pick & Build** — Ludum Dare 34  
  <https://aun.itch.io/pickbuild>
- **Monster Defense** — Ludum Dare 33  
  <https://aun.itch.io/monster-defense>

---

## Musique

La musique occupe une place importante dans ma vie.  
Je chante en **ténor** (en chœur et en solo), et je joue également de la **guitare**,  
du **violon**, et un peu de **piano**.  

J’ai étudié le chant au **conservatoire**, où j’ai appris la technique classique  
et le chant d’ensemble.  

C’est un loisir, pas une activité professionnelle, mais l’un des moyens  
que je préfère pour me détendre, respirer et créer quelque chose de beau.

---

## Dessin, Photos & Couture

J’aime **dessiner**, prendre des **photos**, et parfois faire un peu de **couture**.  
Ce sont des loisirs simples — des façons de ralentir, d’observer,  
et d’expérimenter la lumière, les formes et les textures.

### Galerie  

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

---

Ces activités me rappellent que la créativité prend de nombreuses formes,  
et que la recherche n’en est qu’une partie.

