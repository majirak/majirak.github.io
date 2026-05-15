---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  /* Home research highlight blocks (uses theme feature__* grid) */
  .home-research .feature__wrapper { margin-bottom: 2.25rem; padding-bottom: 2rem; }
  .home-research .feature__item { font-size: 1rem; line-height: 1.55; }
  .home-research .archive__item-body h2 {
    margin-top: 0;
    font-size: 1.35rem;
    letter-spacing: -0.01em;
    border-bottom: 0;
    padding-bottom: 0;
  }
  .home-research .archive__item-body p { font-size: 0.95rem; margin-bottom: 0.65rem; }
  .home-research .archive__item-body .home-ref { font-size: 0.88rem; color: inherit; opacity: 0.92; }
  .home-research .archive__item-teaser {
    max-height: none !important;
    overflow: visible !important;
  }
  .home-research .feature__item {
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    gap: 1.25rem 2rem;
  }
  .home-research .feature__item--left .archive__item-teaser,
  .home-research .feature__item--right .archive__item-teaser {
    float: none !important;
    width: 100% !important;
    margin: 0 !important;
    max-width: 100%;
  }
  @media (min-width: 768px) {
    .home-research .feature__item--left .archive__item-teaser,
    .home-research .feature__item--right .archive__item-teaser {
      flex: 0 1 52%;
      max-width: 52%;
      min-width: 320px;
    }
    .home-research .feature__item--left .archive__item-body,
    .home-research .feature__item--right .archive__item-body {
      flex: 1 1 36%;
      min-width: 240px;
      float: none !important;
      width: auto !important;
      margin: 0 !important;
    }
  }
  .home-research .archive__item-teaser img {
    width: 100%;
    height: auto;
    max-height: none;
    border-radius: 6px;
    box-shadow: 0 2px 12px rgba(0,0,0,0.08);
  }
</style>

## Research profile

Research scientist specializing in probabilistic machine learning, generative modeling, and uncertainty quantification for multivariate time-series and multimodal data. Expertise in scalable variational inference, Gaussian processes, and sequential models. Experience applying ML in healthcare and financial domains across academic and industry environments.

## Research highlights

<div class="home-research">

<div class="feature__wrapper">
  <div class="feature__item feature__item--left">
    <div class="archive__item-teaser">
      <a href="/publication/2025-learning-route-neurips"><img src="/images/home/neurips-2025.png" alt="Learning to Route (NeurIPS 2025)"></a>
    </div>
    <div class="archive__item-body">
      <h2>Multimodal &amp; multitask learning</h2>
      <p>Per-sample adaptive routing for multimodal multitask prediction: each instance can follow a distinct computational path across modalities and tasks.</p>
      <p class="home-ref"><strong>Publication:</strong>
        <a href="/publication/2025-learning-route-neurips">Learning to Route (NeurIPS 2025)</a>
      </p>
    </div>
  </div>
</div>

<div class="feature__wrapper">
  <div class="feature__item feature__item--right">
    <div class="archive__item-teaser">
      <a href="/publication/2024-discrete-representation-eusipco"><img src="/images/home/eusipco-2024.png" alt="Discrete representation learning (EUSIPCO 2024)"></a>
    </div>
    <div class="archive__item-body">
      <h2>Discrete representation learning for time series</h2>
      <p>Generative modeling of multivariate time series with discrete latent structure and a plate-structured graphical model for scalable representation learning.</p>
      <p class="home-ref"><strong>Publication:</strong>
        <a href="/publication/2024-discrete-representation-eusipco">Discrete Representation Learning for Multivariate Time Series (EUSIPCO 2024)</a>
      </p>
    </div>
  </div>
</div>

<div class="feature__wrapper">
  <div class="feature__item feature__item--left">
    <div class="archive__item-teaser">
      <a href="/publication/2024-filtering-high-dimensional-icif"><img src="/images/Marzieh_Ajirak.jpeg" alt="High-dimensional filtering for sequential classification (ICIF 2024)"></a>
    </div>
    <div class="archive__item-body">
      <h2>High-dimensional filtering for sequential classification</h2>
      <p>Filtering methods for high-dimensional data streams applied to sequential classification, with emphasis on tractable inference in dynamic settings.</p>
      <p class="home-ref"><strong>Publication:</strong>
        <a href="/publication/2024-filtering-high-dimensional-icif">Filtering of High-Dimensional Data for Sequential Classification (ICIF 2024)</a>
      </p>
    </div>
  </div>
</div>

<div class="feature__wrapper">
  <div class="feature__item feature__item--right">
    <div class="archive__item-teaser">
      <a href="/research/"><img src="/images/Marzieh_Ajirak.jpeg" alt="Probabilistic modeling"></a>
    </div>
    <div class="archive__item-body">
      <h2>Probabilistic modeling &amp; uncertainty</h2>
      <p>Gaussian processes, deep state-space models, and variational methods for calibrated predictions and sequential decision-making.</p>
      <p class="home-ref"><strong>Representative work:</strong>
        <a href="/publication/2025-exploring-synergies-signal-processing"><i>Signal Processing</i> 2025</a> ·
        <a href="/publication/2024-gp-gated-hme-pami">IEEE TPAMI 2024</a> ·
        <a href="/publication/2023-sequential-estimation-deep-ssm-tsp">IEEE TSP 2023</a>
      </p>
      <p class="home-ref"><a href="/research/">Research page →</a></p>
    </div>
  </div>
</div>

<div class="feature__wrapper">
  <div class="feature__item feature__item--left">
    <div class="archive__item-teaser">
      <a href="/research/"><img src="/images/Marzieh_Ajirak.jpeg" alt="Time series and applications"></a>
    </div>
    <div class="archive__item-body">
      <h2>Time series, graphs &amp; applications</h2>
      <p>Latent-variable models for incomplete and heterogeneous data, graph-structured signals, and learning in healthcare-relevant settings.</p>
      <p class="home-ref"><strong>Representative work:</strong>
        <a href="/publication/2023-gaussian-latent-variable-icassp">ICASSP 2023</a> ·
        <a href="/publication/2023-time-varying-graph-icassp">ICASSP 2023</a> ·
        <a href="/publication/2022-boost-ensemble-ctg-icassp">ICASSP 2022</a>
      </p>
      <p class="home-ref"><a href="/research/">Research page →</a></p>
    </div>
  </div>
</div>

</div>

## News

<div style="font-size: 0.92rem; line-height: 1.45;">
<ul>
  <li><strong>2025</strong> — Neural Information Processing Systems (NeurIPS), San Diego, CA.</li>
  <li><strong>2024</strong> — European Signal Processing Conference (EUSIPCO), Co-organizer, Lyon, France.</li>
  <li><strong>2024</strong> — International Conference on Information Fusion, Invited Talk, Venice, Italy.</li>
  <li><strong>2024</strong> — ISBA–Fusion Joint Workshop, Venice, Italy.</li>
  <li><strong>2023</strong> — IEEE Workshop on Computational Advances in Multi-Sensor Adaptive Processing (CAMSAP), Costa Rica.</li>
  <li><strong>2023</strong> — Asilomar Conference on Signals, Systems, and Computers, Invited Talk, Pacific Grove, CA.</li>
  <li><strong>2023</strong> — IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP).</li>
  <li><strong>2023</strong> — Bellairs Workshop on Machine Learning and Statistical Signal Processing for Data on Graphs, Barbados.</li>
  <li><strong>2022</strong> — SIAM Conference on Mathematics of Data Science (MDS22), San Diego, CA.</li>
  <li><strong>2022</strong> — International Conference on Machine Learning (ICML), selected as Top 10% Reviewer, Baltimore, MD.</li>
  <li><strong>2022</strong> — IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP).</li>
</ul>
</div>
