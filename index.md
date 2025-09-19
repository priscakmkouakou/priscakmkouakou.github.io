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
  .news-list {
  list-style: none;
  margin: 0;
  padding: 0;
  position: relative;
}

/* vertical line behind date pills */
.news-list::before {
  content: "";
  position: absolute;
  top: 1.2rem;   /* start mid first pill */
  bottom: 1.2rem;/* end mid last pill */
  left: 3.75rem; /* center of date column (7.5rem / 2) */
  width: 2px;
  background: #cfe7d3;
  z-index: 0;
}

/* news items */
.news-item {
  display: flex;
  gap: 1rem;
  align-items: flex-start;
  padding: .6rem 0;
  border-bottom: 1px solid rgba(127,127,127,.2);
  position: relative;
  z-index: 1;
}

/* pill-styled dates */
.news-date {
  flex: 0 0 7.5rem;
  font-weight: 600;
  white-space: nowrap;
  color: #1f2937;
  background: #eaf7ea;
  border-radius: 999px;
  padding: .25rem .6rem;
  text-align: center;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
  z-index: 2; /* keep pill above line */
}

/* right side text */
.news-text {flex: 1 1 auto; min-width: 0;}
.news-text a {text-decoration: none; border-bottom: 1px solid currentColor;}
.news-text a:hover {border-bottom-color: transparent;}

/* mobile */
@media (max-width: 480px) {
  .news-item {gap: .6rem;}
  .news-date {flex-basis: 6.5rem; font-weight: 600;}
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

---

<div class="section">
  
  <h2>Featured publications</h2>

<style>
/* Card look */
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

/* Expander: keep toggle at the bottom */
.expander input{display:none;}

/* Clamped preview: show only 2 lines + ellipsis */
.abstract{
  font-size:.92rem; line-height:1.55; margin:.6rem 0 0 0;
  display:-webkit-box; -webkit-line-clamp:2; -webkit-box-orient:vertical;
  overflow:hidden; text-overflow:ellipsis;
}

/* When expanded, remove the clamp */
.expander input:checked ~ .abstract{
  -webkit-line-clamp:unset; overflow:visible;
}

/* Toggle link styles */
.expander label{
  display:inline-flex; align-items:center; gap:.35rem;
  font-weight:600; font-size:.92rem; color:#2b6e2f;
  cursor:pointer; user-select:none; text-decoration:none; border-bottom:1px solid transparent;
}
.expander label:hover{border-bottom-color:#2b6e2f;}
.more{display:inline;}
.less{display:none;}
.expander input:checked ~ label .more{display:none;}
.expander input:checked ~ label .less{display:inline;}
.chev{transition:transform .15s ease;}
.expander input:checked ~ label .chev{transform:rotate(180deg);}
</style>

<div class="pub-card">
  <h3><a href="https://doi.org/10.17863/CAM.121371">
    Existing sustainability interventions are insufficient to scale up cocoa agroforestry in West Africa
  </a></h3>
  <div class="journal">2025 · <em>Sustainable Development</em></div>
  <div class="authors">
    <strong>K. M.-P. Kouakou</strong>, J. Lyons-White, W. Thompson, T. Addoah, F. Cammelli,  W. J. Blaser-Hart, V. Maguire-Rajpaul, E. Dawoe, R.D. Garrett
  </div>

  <div class="expander">
    <input id="abs1" type="checkbox">
    <p class="abstract">
      <strong>Abstract:</strong> Sustainability transitions in agri-food systems are required to address climate change, biodiversity loss, and social inequities. In the West African cocoa sector, supply chain sustainability initiatives (SSIs) have emerged as key environmental governance tools to address these challenges and promote agroforestry. Agroforestry is a climate adaptation strategy that supports both nature and the livelihoods of smallholder farmers, yet its adoption remains limited. This study combines the Multi-Level Perspective (MLP) and the Creative Destruction (CD) frameworks to qualitatively assess how the interventions of SSIs influence the scaling up of agroforestry adoption in Côte d’Ivoire and Ghana. Through policy mapping, 101 semi-structured interviews and focus groups with governments, private companies, NGOs, and cocoa farmers, we found that most interventions (~93%) support agroforestry as a niche innovation, relying on extension services and short-term incentives. Only 7% of the interventions pursue regime-level changes, such as land and tree tenure reforms, which remain limited due to institutional and informal barriers. Additionally, SSIs have not significantly changed policy network structures, and smallholder farmers remain excluded from governance processes. Based on these findings, we recommend that scaling up agroforestry adoption requires regime destabilisation interventions, including the integration and strengthening of land and tree tenure reforms, as well as the simplification of tree registration procedures. Furthermore, greater efforts are needed to ensure the inclusion of smallholders within policy networks, as their participation remains limited.
    </p>
    <label for="abs1">
      <span class="more">Read more</span>
      <span class="less">Read less</span>
      <span class="chev">▾</span>
    </label>
  </div>
</div>

<div class="pub-card">
  <h3><a href="https://doi.org/10.1088/2976-601X/adf117">
    Scaling out agroforestry and forest conservation in West Africa requires more transformative policy interventions in cocoa supply chains
  </a></h3>
  <div class="journal">2025 · <em>Environmental Research: Food Systems</em></div>
  <div class="authors">
    F. Cammelli, T. Addoah, N.A. Furrer, <strong>P. Kouakou</strong>, J. Lyons-White, C. Renier, W. Thompson, R.D. Garrett
  </div>

  <div class="expander">
    <input id="abs1" type="checkbox">
    <p class="abstract">
      <strong>Abstract:</strong> Tropical forests are vanishing at an unprecedented rate due to the expansion of commodity production, while climate change is putting increasing strain on food systems. Côte d’Ivoire and Ghana produce over half of the world’s cocoa, a multi-billion-dollar industry, yet most cocoa producers in these two countries live below the poverty line, and economic vulnerability is further exacerbated by climate change and ongoing deforestation largely driven by cocoa expansion. Companies have recently begun implementing policies to promote forest restoration, halt deforestation, and improve farmers’ livelihoods, but there is increasing evidence that these efforts are falling short in terms of both effectiveness and equity. This perspective article argues that several critical design flaws are central to the short-comings of these company policies that are likely to be exacerbated with the new EU deforestation regulation. The first problem is that they target a sub-optimal scale, focusing largely on individual suppliers or on landscape approaches that are only partially implemented, rather than on more manageable supply shed scales. The second flaw is that they focus on tree planting and agroforestry over conservation of remaining forests. We propose that cocoa firms and importing countries embrace more transformative policy approaches that target the correct scale and ambition to tackle structural issues influencing supply chain sustainability and achieve synergies between environmental and social outcomes. First, policies must be integrated in a mitigation and conservation hierarchy, focusing on conservation, not just tree planting. Second, companies must expand their approach beyond their individual supply chains to the broader supply sheds where they source.
    </p>
    <label for="abs1">
      <span class="more">Read more</span>
      <span class="less">Read less</span>
      <span class="chev">▾</span>
    </label>
  </div>
</div>

<div class="pub-card">
  <h3><a href="https://doi.org/10.1002/sd.3380">
    Is the Implementation of Cocoa Companies’ Forest Policies on Track to Effectively and Equitably Address Deforestation in West Africa?
  </a></h3>
  <div class="journal">2025 · <em>Sustainable Development</em></div>
  <div class="authors">
    T. Addoah, J. Lyons-White, F. Cammelli, <strong>K.M.-P. Kouakou</strong>, S. Carodenuto, W.J. Thompson, C. Renier, R.D. Garrett
  </div>

  <div class="expander">
    <input id="abs2" type="checkbox">
    <p class="abstract">
      <strong>Abstract:</strong> Tropical forests play a crucial role in achieving the sustainable development goals by contributing to climate stability, conserving biodiversity and sustaining livelihoods. However, forests are disappearing due to agricultural expansion. In West Africa, cocoa production is a major driver of deforestation. This study examines the design and implementation of forest-focused supply chain policies (FSPs) in cocoa supply chains in Côte d'Ivoire and Ghana, the world's two leading cocoa producers. FSPs are voluntary policies of companies to combat deforestation, restore forests, and improve farmers' livelihoods. Drawing on 91 stakeholder interviews, we developed a conceptual framework to examine FSPs' theory of change, implementation and potential effectiveness and equity. Our findings reveal shortcomings in FSPs' design and implementation. FSPs are mostly narrowly focused on preventing illegal deforestation and only target farmers in companies' ‘direct’ supply chains, neglecting important landscape-scale approaches and processes. Companies also fail to include smallholder farmers sufficiently in policy design and implementation. Lastly, FSPs prioritise productivity enhancement but overlook the importance of addressing farmers' social norms and values. We provide recommendations on how to address the shortcomings to achieve sustainable cocoa production.
    </p>
    <label for="abs2">
      <span class="more">Read more</span>
      <span class="less">Read less</span>
      <span class="chev">▾</span>
    </label>
  </div>
</div>

