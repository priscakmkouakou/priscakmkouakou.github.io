---
title: Projects
layout: default
permalink: /projects/
---

## Current projects

<div class="proj-wrap">
  <div class="proj-grid">
    <!-- Project 1 -->
    <article class="proj-card horizontal">
      <div class="proj-media">
        <img src="/assets/sustain-cocoa.jpg" alt="SUSTAIN-COCOA project illustration">
      </div>
      <div class="proj-body">
        <h3 class="proj-title"><a class="primary" href="https://www.sustain-cocoa.earth/" target="_blank"><i class="fa-solid fa-cocoa"></i>SUSTAIN-COCOA</h3></a>
        <p class="proj-desc">
          A five-year project focusing on understanding the impacts of sustainable sourcing policies on biodiversity protection, climate mitigation,
          and improved livelihoods in the West African cocoa sector. 
        </p>
        </div>
        <div class="proj-actions">
          <a class="primary" href="https://doi.org/10.1002/sd.3380" target="_blank"><i class="fa-solid fa-book-open"></i> Paper</a>
          <a href="https://glp.earth/news-events/events/5th-open-science-meeting-pathways-sustainable-and-just-land-systems/" target="_blank"><i class="fa-solid fa-chalkboard-user"></i> Talk</a>
          <a href="https://github.com/priscakmkouakou" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
        </div>
      </div>
    </article>

  </div>
</div>

<style>
/* Base styles same as before … */

/* Horizontal card variation */
.proj-card.horizontal {
  flex-direction: row;             /* image + text side by side */
  align-items: stretch;
}

.proj-card.horizontal .proj-media {
  flex: 0 0 40%;                   /* take 40% width for the image */
  aspect-ratio: auto;              /* allow free height */
  max-height: 100%; 
}

.proj-card.horizontal .proj-media img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.proj-card.horizontal .proj-body {
  flex: 1;
  padding: 1.2rem 1.5rem;
}
</style>

