---
title: Projects
layout: default
permalink: /projects/
---

## Current projects
- **SUSTAIN-COCOA** — Sustainable sourcing policies for biodiversity protection, climate mitigation, and improved livelihoods in the West African cocoa sector. [https://www.zerodeforestationimpacts.com/](#)

---
<style>
/* ========= THEME ========= */
:root{
  --accent:#2b6e2f;        /* dark green */
  --accent-2:#1d5a25;
  --bg-soft:#eaf7ea;       /* light green card bg */
  --border:#cfe7d3;        /* soft green border */
  --text:#1f2937;          /* dark gray */
  --muted:#6b7280;         /* muted gray */
}

/* ========= LAYOUT ========= */
.proj-wrap{max-width: 1100px; margin: 0 auto;}
.proj-grid{
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
  margin: .75rem 0 2rem 0;
}
@media (max-width: 820px){ .proj-grid{ grid-template-columns: 1fr; } }

/* ========= CARD ========= */
.proj-card{
  background: var(--bg-soft);
  border: 1px solid var(--border);
  border-radius: 14px;
  overflow: hidden;
  box-shadow: 0 2px 6px rgba(0,0,0,.06);
  display: flex; flex-direction: column;
}
.proj-media{
  aspect-ratio: 16/9;
  background: #f2f6f2;
  display:flex; align-items:center; justify-content:center;
  font-size:.9rem; color:var(--muted);
}
.proj-media img{ width:100%; height:100%; object-fit: cover; display:block; }

.proj-body{ padding: 1rem 1.2rem; }
.proj-title{ margin:.1rem 0 .25rem 0; font-size:1.15rem; font-weight:700; line-height:1.35; color:var(--text);}
.proj-meta{ color:var(--muted); font-size:.95rem; margin-bottom:.35rem; }
.proj-desc{ margin:.35rem 0 0 0; line-height:1.55; }

/* tags */
.proj-tags{ margin:.6rem 0 0 0; display:flex; flex-wrap:wrap; gap:.35rem;}
.proj-tag{
  background:#fff; border:1px solid var(--border); color:var(--text);
  padding:.2rem .55rem; border-radius:999px; font-size:.82rem; font-weight:600;
}

/* actions */
.proj-actions{ margin:.75rem 0 1rem 0; display:flex; flex-wrap:wrap; gap:.5rem; }
.proj-actions a{
  display:inline-flex; align-items:center; gap:.45rem;
  padding:.5rem .8rem; border-radius:10px; text-decoration:none; font-weight:700; font-size:.92rem;
  border:1px solid var(--border); background:#fff; color:var(--text);
}
.proj-actions a:hover{ border-color: var(--accent); color: var(--accent); }
.proj-actions a.primary{ background: var(--accent); color:#fff; border-color:var(--accent); }
.proj-actions a.primary:hover{ filter:brightness(.95); }

/* expandable details (no JS) */
.proj-more{ padding: 0 1.2rem 1rem 1.2rem; }
details summary{
  list-style:none; cursor:pointer; font-weight:700; color:var(--accent);
}
details summary::-webkit-details-marker{ display:none; }
details[open] summary{ color: var(--accent-2); }
</style>

<div class="proj-wrap">
  <div class="proj-grid">
    <!-- Project 1 (with image) -->
    <article class="proj-card">
      <div class="proj-media">
        <img src="/assets/projects/sustain-cocoa.jpg" alt="SUSTAIN-COCOA">
      </div>
      <div class="proj-body">
        <h3 class="proj-title">Sustainable sourcing policies for biodiversity protection, climate mitigation, and improved livelihoods in the West African cocoa sector.</h3>
        <div class="proj-meta">Current Implementation: </div>
        <p class="proj-desc">
          A five-year project focusing on smallholder cocoa farmers in West Africa.
        </p>
        <div class="proj-tags">
          <span class="proj-tag">Deforestation/Reforestation</span>
          <span class="proj-tag">Supply chain sustainability initiatives</span>
          <span class="proj-tag">Climate mitigation</span>
          <span class="proj-tag">Livelihoods</span>
        </div>
       <div class="proj-actions">
          <a class="primary" href="https://doi.org/10.1002/sd.3380" target="_blank" rel="noopener">
            <i class="fa-solid fa-book-open"></i> Paper
          </a>
          <a href="https://glp.earth/news-events/events/5th-open-science-meeting-pathways-sustainable-and-just-land-systems/" target="_blank" rel="noopener">
            <i class="fa-solid fa-chalkboard-user"></i> Talk
          </a>
          <a href="https://github.com/priscakmkouakou/YOUR-REPO" target="_blank" rel="noopener">
            <i class="fa-brands fa-github"></i> Code
        </div>
      </div>
      <div class="proj-more">
        <details>
          <summary><i class="fa-regular fa-circle-down"></i> Read more</summary>
          <p>
            Protocol includes plot layout, flight parameters, and biomass allometry. Data will be shared under an
            appropriate license after anonymization and QA/QC.
          </p>
        </details>
      </div>
    </article>

  </div>
</div>
