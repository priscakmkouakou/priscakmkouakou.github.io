---
title: Projects
layout: default
permalink: /projects/
---

## Projects

<div class="proj-wrap">
  <div class="proj-grid">
    <!-- Project 1 -->
    <article class="proj-card horizontal">
      <div class="proj-media">
        <img src="/assets/sustain-cocoa.jpg" alt="SUSTAIN-COCOA project illustration">
        <span class="photo-credit">Photo by Emmanuel Bobbie</span>
      </div>
      <div class="proj-body">
        <h3 class="proj-title">
        <a href="https://www.sustain-cocoa.earth/" target="_blank" rel="noopener">
        🌱🍫 SUSTAIN-COCOA
        </a>
      </h3>
        <div class="proj-meta">Current implementation </div>
        <p class="proj-desc">
          A 5-year project focused on understanding how sustainable sourcing policies can support biodiversity protection, climate mitigation,
          and smallholder livelihoods in the West African cocoa sector.
        </p>
        <div class="proj-tags">
          <span class="proj-tag">nature-based solutions (NbS)</span>
          <span class="proj-tag">supply chains</span>
          <span class="proj-tag">climate</span>
          <span class="proj-tag">livelihoods</span>
        </div>
        <div class="proj-actions">
          <a class="primary" href="https://priscakmkouakou.github.io/publications/" target="_blank" rel="noopener">
            <i class="fa-solid fa-book-open"></i> Papers
          </a>
          <a href="https://www.globalfood.cam.ac.uk/events/lunchtime-conversation-socio-economic-levers-scale-more-sustainable-farming" target="_blank" rel="noopener">
            <i class="fa-solid fa-chalkboard-user"></i> Talk
          </a>
          <a href="https://github.com/priscakmkouakou" target="_blank" rel="noopener">
            <i class="fa-brands fa-github"></i> Code
          </a>
        </div>
      </div>
    </article>

  </div>
</div>

<style>
/* ===== Theme (scoped to projects) ===== */
.proj-wrap{
  --accent:#2b6e2f;      /* dark green */
  --accent-2:#1d5a25;
  --bg-soft:#eaf7ea;     /* light green */
  --border:#cfe7d3;      /* soft green border */
  --text:#1f2937;        /* dark gray */
  --muted:#6b7280;       /* muted gray */
  max-width:1100px; margin:0 auto;
}

/* ===== Grid ===== */
.proj-grid{
  display:grid; grid-template-columns:1fr; gap:1rem; margin:.75rem 0 2rem 0;
}

/* ===== Card ===== */
.proj-card{
  background:var(--bg-soft);
  border:1px solid var(--border);
  border-radius:14px;
  box-shadow:0 2px 6px rgba(0,0,0,.06);
  overflow:hidden;
  display:flex; flex-direction:column;
}

/* Horizontal layout (wide, not long) */
.proj-card.horizontal{ flex-direction:row; align-items:stretch; }
.proj-card.horizontal .proj-media{ flex:0 0 42%; aspect-ratio:auto; max-height:100%; }
.proj-card.horizontal .proj-body{ flex:1; padding:1.2rem 1.5rem; }

/* Media */
.proj-media{
  aspect-ratio:16/9;
  background:#f2f6f2;
  display:flex; align-items:center; justify-content:center;
  color:var(--muted);
}
.proj-media img{ width:100%; height:100%; object-fit:cover; display:block; }

.proj-media {
  position: relative;
}

.photo-credit {
  position: absolute;
  bottom: 6px;
  right: 10px;
  font-size: 0.75rem;
  color: rgba(255, 255, 255, 0.9);
  background: rgba(0, 0, 0, 0.4);
  padding: 2px 6px;
  border-radius: 4px;
}

/* Text */
.proj-title{ margin:.1rem 0 .25rem 0; font-size:1.25rem; font-weight:700; line-height:1.3; }
.proj-title a{ color:var(--text); text-decoration:none; border-bottom:1px solid transparent; }
.proj-title a:hover{ border-bottom-color:var(--accent); }
.proj-meta{ color:var(--muted); font-size:.95rem; margin-bottom:.35rem; }
.proj-desc{ margin:.45rem 0 0 0; line-height:1.55; }

/* Tags */
.proj-tags{ margin:.6rem 0 0 0; display:flex; flex-wrap:wrap; gap:.35rem; }
.proj-tag{
  background:#fff; border:1px solid var(--border); color:var(--text);
  padding:.2rem .55rem; border-radius:999px; font-size:.82rem; font-weight:600;
}

/* Actions */
.proj-actions{ margin:.9rem 0 0 0; display:flex; flex-wrap:wrap; gap:.5rem; }
.proj-actions a{
  display:inline-flex; align-items:center; gap:.45rem;
  padding:.5rem .8rem; border-radius:10px; text-decoration:none; font-weight:700; font-size:.92rem;
  border:1px solid var(--border); background:#fff; color:var(--text);
}
.proj-actions a:hover{ border-color:var(--accent); color:var(--accent); }
.proj-actions a.primary{ background:var(--accent); color:#fff; border-color:var(--accent); }
.proj-actions a.primary:hover{ filter:brightness(.95); }

/* Mobile */
@media (max-width:860px){
  .proj-card.horizontal{ flex-direction:column; }
  .proj-card.horizontal .proj-media{ flex-basis:auto; aspect-ratio:16/9; }
  .proj-title{ font-size:1.15rem; }
}
</style>


