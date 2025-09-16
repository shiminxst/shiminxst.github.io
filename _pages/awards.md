---
layout: archive
title: ""
permalink: /awards/
author_profile: true
---

## Funded Projects

<style>
  /* --- Awards Card Styles (no left border highlight) --- */
  .awards { 
    counter-reset: item; 
    list-style: none; 
    padding-left: 0; 
    margin: 1rem 0 0;
  }
  .awards > li {
    counter-increment: item;
    margin: 0 0 1rem 0;
  }
  .award-card {
    border: 1px solid rgba(0,0,0,.12);
    border-radius: 10px;
    padding: 1rem 1.25rem;
    background: #fff;
    box-shadow: 0 2px 6px rgba(0,0,0,.05);
  }
  .award-title {
    font-weight: 700;
    margin: 0 0 .35rem 0;
  }
  .award-title::before {
    content: counter(item) ". ";
    font-weight: 600;
    color: #444;
  }
  .award-meta {
    margin: .2rem 0;
    color: #333;
  }
  .award-meta b {
    font-weight: 600;
  }
  .award-sponsor { margin-top: .2rem; }

  /* Dark mode friendly */
  @media (prefers-color-scheme: dark) {
    .award-card { 
      background: #1e1f22; 
      border-color: #333; 
      box-shadow: none;
    }
    .award-meta, .award-title { color: #eee; }
  }
</style>

<ul class="awards">
  <li>
    <div class="award-card">
      <h3 class="award-title">Mitigating Unfairness in Foundation Models for Medical Applications</h3>
      <p class="award-meta"><b>Principal Investigator:</b> Min Shi (Computing and Informatics)</p>
      <p class="award-meta award-sponsor"><b>Sponsor:</b> Louisiana BorSF – Research Competitiveness Subprogram</p>
      <p class="award-meta"><b>Amount Awarded:</b> $181,392</p>
      <p class="award-meta"><b>Grant Period:</b> 06/01/2025 – 06/30/2028</p>
    </div>
  </li>
  <li>
    <div class="award-card">
      <h3 class="award-title">Mitigating Unfairness in Foundation Models for Medical Applications</h3>
      <p class="award-meta"><b>Principal Investigator:</b> Min Shi (Computing and Informatics)</p>
      <p class="award-meta award-sponsor"><b>Sponsor:</b> Louisiana BorSF – Research Competitiveness Subprogram</p>
      <p class="award-meta"><b>Amount Awarded:</b> $181,392</p>
      <p class="award-meta"><b>Grant Period:</b> 06/01/2025 – 06/30/2028</p>
    </div>
  </li>
</ul>
