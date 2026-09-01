---
permalink: /gallery/
title: "Gallery"
excerpt: "Photos from poster sessions, lab meetings, and milestones."
author_profile: true
---

<span class='anchor' id='gallery'></span>

# 📸 Gallery

A few snapshots from poster sessions, lab meetings, and other milestones along the way.

<style>
.photo-gallery-section { margin: 30px 0 40px 0; }
.photo-gallery-section h2 { margin-bottom: 6px; }

.carousel-row {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-top: 16px;
}
.carousel-track {
  display: flex;
  gap: 16px;
  overflow-x: auto;
  scroll-behavior: smooth;
  scroll-snap-type: x mandatory;
  padding: 4px 2px 12px 2px;
  flex: 1 1 auto;
  scrollbar-width: thin;
}
.photo-card {
  flex: 0 0 240px;
  scroll-snap-align: start;
  border-radius: 8px;
  overflow: hidden;
  border: 1px solid rgba(0,0,0,0.08);
  box-shadow: 0 1px 4px rgba(0,0,0,0.08);
  background: #fff;
}
.photo-card img {
  width: 100%;
  height: 190px;
  object-fit: cover;
  display: block;
  pointer-events: none;
  user-select: none;
}
.photo-caption {
  font-size: 0.85em;
  padding: 8px 10px;
  color: inherit;
  opacity: 0.8;
}
.gallery-arrow {
  flex: 0 0 auto;
  width: 36px;
  height: 36px;
  border-radius: 50%;
  border: 1px solid rgba(0,0,0,0.15);
  background: #fff;
  cursor: pointer;
  font-size: 1.1em;
  line-height: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  color: inherit;
}
.gallery-arrow:hover { background: rgba(0,0,0,0.06); }

#carousel-lab img,
#carousel-milestones img {
  pointer-events: auto;
  cursor: zoom-in;
}

.lightbox-overlay {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.85);
  z-index: 9999;
  align-items: center;
  justify-content: center;
  padding: 40px;
}
.lightbox-overlay.open { display: flex; }
.lightbox-overlay img {
  max-width: 100%;
  max-height: 100%;
  border-radius: 6px;
  box-shadow: 0 4px 24px rgba(0,0,0,0.5);
}
.lightbox-close {
  position: absolute;
  top: 20px;
  right: 28px;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  border: none;
  background: rgba(255,255,255,0.15);
  color: #fff;
  font-size: 1.4em;
  line-height: 1;
  cursor: pointer;
}
.lightbox-close:hover { background: rgba(255,255,255,0.3); }
</style>

---

<div class="photo-gallery-section">
<h2>🎤 Poster Sessions & Talks</h2>

<div class="carousel-row">
  <button class="gallery-arrow" data-target="carousel-posters" data-dir="prev" aria-label="Scroll left">‹</button>
  <div class="carousel-track" id="carousel-posters">
    <div class="photo-card">
      <img src="/images/gallery/postersession-1.jpg" alt="Poster session">
      <div class="photo-caption">Presenting a research poster</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/postersession-2.jpg" alt="Poster session">
      <div class="photo-caption">Poster session Q&amp;A</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/postersession-3.jpg" alt="Poster session">
      <div class="photo-caption">Poster session</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/postersession-4.jpg" alt="Poster session">
      <div class="photo-caption">Poster session</div>
    </div>
  </div>
  <button class="gallery-arrow" data-target="carousel-posters" data-dir="next" aria-label="Scroll right">›</button>
</div>
</div>

<div class="photo-gallery-section">
<h2>🧪 Lab Life & Group Meetings</h2>

<div class="carousel-row">
  <button class="gallery-arrow" data-target="carousel-lab" data-dir="prev" aria-label="Scroll left">‹</button>
  <div class="carousel-track" id="carousel-lab">
    <div class="photo-card">
      <img src="/images/gallery/mattlab-photo.jpg" alt="Travers Lab (CMU)">
      <div class="photo-caption">Travers Lab, CMU</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/mattlab-lunch.jpg" alt="Travers Lab lunch (CMU)">
      <div class="photo-caption">Travers Lab lunch, CMU</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/mm-lab-photo.jpg" alt="M&amp;M Lab (Umich)">
      <div class="photo-caption">M&amp;M Lab, Umich</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/mm-lab-dinner.jpg" alt="M&amp;M Lab dinner (Umich)">
      <div class="photo-caption">M&amp;M Lab dinner, Umich</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/mm-lab-celebrate.jpg" alt="M&amp;M Lab celebration (Umich)">
      <div class="photo-caption">M&amp;M Lab celebration, Umich</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/cm-compbio-group.jpg" alt="CM-Compbio-Group (Umich)">
      <div class="photo-caption">CM-Compbio-Group, Umich</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/with-bernadette.jpg" alt="With Prof. Bernadette Bucher">
      <div class="photo-caption">With Prof. Bernadette Bucher</div>
    </div>
  </div>
  <button class="gallery-arrow" data-target="carousel-lab" data-dir="next" aria-label="Scroll right">›</button>
</div>
</div>

<div class="photo-gallery-section">
<h2>🎓 Milestones</h2>

<div class="carousel-row">
  <button class="gallery-arrow" data-target="carousel-milestones" data-dir="prev" aria-label="Scroll left">‹</button>
  <div class="carousel-track" id="carousel-milestones">
    <div class="photo-card">
      <img src="/images/gallery/graduate-umich.jpg" alt="Graduation, University of Michigan">
      <div class="photo-caption">Graduation, University of Michigan</div>
    </div>
    <div class="photo-card">
      <img src="/images/gallery/honor-graduation-ceremony.jpg" alt="Honors graduation ceremony">
      <div class="photo-caption">Honors graduation ceremony</div>
    </div>
  </div>
  <button class="gallery-arrow" data-target="carousel-milestones" data-dir="next" aria-label="Scroll right">›</button>
</div>
</div>

<div class="lightbox-overlay" id="lightbox-overlay">
  <button class="lightbox-close" id="lightbox-close" aria-label="Close">×</button>
  <img id="lightbox-img" src="" alt="">
</div>

<script>
document.addEventListener('click', function (e) {
  var btn = e.target.closest('.gallery-arrow');
  if (btn) {
    var track = document.getElementById(btn.getAttribute('data-target'));
    if (track) {
      var amount = track.clientWidth * 0.8;
      track.scrollBy({
        left: btn.getAttribute('data-dir') === 'prev' ? -amount : amount,
        behavior: 'smooth'
      });
    }
    return;
  }

  var overlay = document.getElementById('lightbox-overlay');
  var zoomImg = e.target.closest('#carousel-lab img, #carousel-milestones img');
  if (zoomImg) {
    document.getElementById('lightbox-img').src = zoomImg.src;
    document.getElementById('lightbox-img').alt = zoomImg.alt;
    overlay.classList.add('open');
    return;
  }

  if (e.target === overlay || e.target.id === 'lightbox-close') {
    overlay.classList.remove('open');
  }
});

document.addEventListener('keydown', function (e) {
  if (e.key === 'Escape') {
    document.getElementById('lightbox-overlay').classList.remove('open');
  }
});
</script>
