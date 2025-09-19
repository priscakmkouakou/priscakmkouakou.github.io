---
title: Prisca Kouakou
layout: default
---
<style>
/* Make the bio section wider */
.lead {
  max-width: 750px;   /* default was ~600px */
  margin: 0 auto;     /* keep it centered */
  font-size: 1.05rem; /* optional: slightly larger text */
  line-height: 1.6;
  text-align: centered;   /* align text centered instead of centered */
}

/* Make the profile picture larger */
.avatar {
  width: 250px;   /* increase size (try 220–250px) */
  height: auto;
  border-radius: 50%;
  margin-bottom: 1rem;
}
</style>

<div class="hero">
  <img class="avatar" src="/assets/profile.jpg" alt="Prisca Kouakou headshot">
  <div class="icons">
    <a href="mailto:you@example.com" title="Email"><i class="fa-solid fa-envelope"></i></a>
    <a href="https://scholar.google.com/citations?user=I9N3bjcAAAAJ&hl=en&oi=ao" title="Google Scholar"><i class="fa-brands fa-google"></i></a>
    <a href="https://orcid.org/0009-0001-3711-1578" title="ORCID"><i class="fa-brands fa-orcid"></i></a>
    <a href="https://github.com/priscakmkouakou" title="GitHub"><i class="fa-brands fa-github"></i></a>
    <a href="https://www.linkedin.com/in/maria-prisca-kouakou/" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
    <a href="/docs/KouakouCV_August2025.pdf" title="Curriculum Vitae" target="_blank"><i class="fa-solid fa-file-lines"></i></a>
  </div>
  
  <h1 class="hero-name">Prisca Kouakou</h1>
  <p class="lead">
  I am an interdisciplinary researcher with backgrounds in ecology, environmental science, and social science.
  Currently, I am a PhD Candidate in the <a href="https://www.geog.cam.ac.uk/people/kouakou/">Department of Geography at the University of Cambridge</a>,   supported by the Cambridge Trust Scholarship. My research examines the conditions under which supply chain sustainability initiatives 
  can lead to the adoption of agroforestry and how these initiatives shape social and ecological outcomes in the cocoa 
  sectors of Côte d’Ivoire and Ghana. I use a mixed-methods approach that combines policy analysis with biophysical 
  and household surveys. My work is supervised by <a href="https://www.geog.cam.ac.uk/people/garrett/">Professor Rachael Garrett</a>. 
</p>
</div>

<div class="section">
  <h2>News</h2>

<style>
  /* --- News list styling --- */
  .news-list {list-style: none; margin: 0; padding: 0;}
  .news-item {
    display: flex; gap: 1rem; align-items: flex-start;
    padding: .6rem 0; border-bottom: 1px solid rgba(127,127,127,.2);
  }
  .news-date {
    flex: 0 0 7.5rem; /* left column width */
    font-weight: 600; white-space: nowrap; color: inherit; opacity: .8;
  }
  .news-text {flex: 1 1 auto; min-width: 0;}
  .news-text a {text-decoration: none; border-bottom: 1px solid currentColor;}
  .news-text a:hover {text-decoration: none; border-bottom-color: transparent;}
  /* Small screens: stack a bit tighter */
  @media (max-width: 480px) {
    .news-item {gap: .6rem;}
    .news-date {flex-basis: 6.5rem; font-weight: 600;}
  }
</style>

<ul class="news-list">

  <li class="news-item">
    <time class="news-date">Sep 15, 2025</time>
    <div class="news-text">
      My first-author and first-PhD paper, 
      <a href="https://www.repository.cam.ac.uk/handle/1810/389512">“Existing sustainability interventions are insufficient to scale up cocoa agroforestry in West Africa”</a>,
      has been accepted in <em>Sustainable Development</em>!
    </div>
  </li>

<li class="news-item">
    <time class="news-date">Aug 25, 2025</time>
    <div class="news-text">
      I joined the <a href="https://glp.earth/who-we-are/members">Global Land Program</a> as a member.
    </div>
  </li>
  
  <li class="news-item">
    <time class="news-date">Feb 13, 2025</time>
    <div class="news-text">
      I was invited as a guest speaker at the 
      <a href="https://www.globalfood.cam.ac.uk/events/lunchtime-conversation-socio-economic-levers-scale-more-sustainable-farming">Cambridge Global Food Security Lunchtime Conversation</a> on 
      “Socio-economic levers to scale up more sustainable farming.”
    </div>
  </li>

  <li class="news-item">
    <time class="news-date">Nov 4, 2024</time>
    <div class="news-text">
      I attended the <a href="https://glp.earth/news-events/events/5th-open-science-meeting-pathways-sustainable-and-just-land-systems">Global Land Programme 5th Open Science Meeting</a> and gave a talk on 
      “Identifying enablers for just sustainability transitions to scale up cocoa agroforestry in West Africa.”
    </div>
  </li>

  <li class="news-item">
    <time class="news-date">Dec 8, 2023</time>
    <div class="news-text">
      I returned from a six-month fieldwork campaign in Côte d’Ivoire, where I worked with smallholder cocoa farmers. The campaign aimed to (1) identify suitable study communities, (2) recruit farmers through free, prior, and informed consent, and (3) conduct property-level drone surveys, household surveys, and on-farm biomass assessments. With the support of five field researchers whom I have recruited and trained, we surveyed 350 households and 128 cocoa farms. The resulting dataset will enable me to analyse the determinants of agroforestry adoption and adoption intensity, as well as their socio-economic and ecological implications for smallholder cocoa farmers. 
    </div>
  </li>

</ul>
</div>

<div class="section">
  
  <h2>Featured publications</h2>

<style>
.pub-card{
  background:#eaf7ea; /* light green */
  border-radius:12px;
  padding:1.5rem;
  margin-bottom:1.25rem;
  box-shadow:0 2px 4px rgba(0,0,0,.06);
}
.pub-card h3{margin:0 0 .25rem 0;font-size:1.15rem;font-weight:600;}
.pub-card .journal{font-style:italic;color:#555;font-size:.95rem;}
.pub-card .authors{margin:.5rem 0;color:#333;font-size:.95rem;}
.abstract-preview{margin-top:.5rem;font-size:.92rem;line-height:1.45;}

/* details/summary: link-like button + chevron */
details{margin-top:.4rem;}
summary{cursor:pointer; list-style:none; display:inline-flex; align-items:center; gap:.35rem;}
summary::-webkit-details-marker{display:none;}
.summary-link{font-weight:600;font-size:.92rem;color:#2b6e2f;text-decoration:none;border-bottom:1px solid transparent;}
summary:hover .summary-link{border-bottom-color:#2b6e2f;}
.chev{transition:transform .15s ease;}

/* toggle text: show “more” by default, switch to “less” when open */
.more{display:inline;}
.less{display:none;}
details[open] .more{display:none;}
details[open] .less{display:inline;}
details[open] .chev{transform:rotate(180deg);}

/* full abstract block */
.abstract-full{margin:.5rem 0 0 0;font-size:.92rem;line-height:1.55;}
</style>

<div class="pub-card">
  <h3><a href="https://doi.org/10.1088/2976-601X/adf117">
    Scaling out agroforestry and forest conservation in West Africa requires more transformative policy interventions in cocoa supply chains
  </a></h3>
  <div class="journal">2025 · <em>Environmental Research: Food Systems</em></div>
  <div class="authors">
    F. Cammelli, T. Addoah, N.A. Furrer, <strong>P. Kouakou</strong>, J. Lyons-White, C. Renier, W. Thompson, R.D. Garrett
  </div>

  <p class="abstract-preview">
    In this paper we examine how cocoa supply chain interventions in West Africa can support the scaling of
    agroforestry and forest conservation through policy transformation, identifying leverage points and barriers across
    firms and governance actors.
  </p>

  <details>
    <summary>
      <span class="summary-link">
        <span class="more">Read more</span>
        <span class="less">Read less</span>
      </span>
      <span class="chev">▾</span>
    </summary>
    <p class="abstract-full">
      We synthesize evidence from policy analysis and sector interviews to evaluate the effectiveness of existing
      sustainability initiatives, comparing voluntary corporate commitments with public regulation. We find that
      transformative impact requires stronger incentive alignment, smallholder finance, and monitoring frameworks that
      explicitly value agroforestry outcomes alongside deforestation risk reduction.
    </p>
  </details>
</div>

<div class="pub-card">
  <h3><a href="https://doi.org/10.1002/sd.3380">
    Is the Implementation of Cocoa Companies’ Forest Policies on Track to Effectively and Equitably Address Deforestation in West Africa?
  </a></h3>
  <div class="journal">2025 · <em>Sustainable Development</em></div>
  <div class="authors">
    T. Addoah, J. Lyons-White, F. Cammelli, <strong>K.M.-P. Kouakou</strong>, S. Carodenuto, W.J. Thompson, C. Renier, R.D. Garrett
  </div>

  <p class="abstract-preview">
    We evaluate how company forest policies align with equitable deforestation reduction, focusing on smallholder
    inclusion, transparency, and accountability across Côte d’Ivoire and Ghana.
  </p>

  <details>
    <summary>
      <span class="summary-link">
        <span class="more">Read more</span>
        <span class="less">Read less</span>
      </span>
      <span class="chev">▾</span>
    </summary>
    <p class="abstract-full">
      Using a policy scoring framework and document review, we identify gaps in implementation timelines, farmer
      support, and grievance mechanisms. Without targeted smallholder financing and fair burden sharing, policies risk
      uneven impacts and limited forest outcomes.
    </p>
  </details>
</div>
