---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  .research-highlights .feature__wrapper { margin-bottom: 2.25rem; padding-bottom: 2rem; }
  .research-highlights .feature__item { font-size: 1rem; line-height: 1.55; }
  .research-highlights .archive__item-body h2 {
    margin-top: 0;
    font-size: 1.35rem;
    letter-spacing: -0.01em;
    border-bottom: 0;
    padding-bottom: 0;
  }
  .research-highlights .archive__item-body p { font-size: 0.95rem; margin-bottom: 0.65rem; }
  .research-highlights .archive__item-body ul { font-size: 0.95rem; margin-top: 0.5rem; }
  .research-highlights .archive__item-teaser {
    max-height: none !important;
    overflow: visible !important;
  }
  .research-highlights .feature__item {
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    gap: 1.25rem 2rem;
  }
  .research-highlights .feature__item--left .archive__item-teaser,
  .research-highlights .feature__item--right .archive__item-teaser {
    float: none !important;
    width: 100% !important;
    margin: 0 !important;
    max-width: 100%;
  }
  @media (min-width: 768px) {
    /* Image left, text right */
    .research-highlights .feature__item--left:not(.feature__item--text-only) {
      flex-direction: row;
    }
    /* Image right, text left (reverse DOM order: teaser is first in HTML) */
    .research-highlights .feature__item--right:not(.feature__item--text-only) {
      flex-direction: row-reverse;
    }
    .research-highlights .feature__item--left .archive__item-teaser,
    .research-highlights .feature__item--right .archive__item-teaser {
      flex: 0 1 48%;
      max-width: 48%;
      min-width: 280px;
    }
    .research-highlights .feature__item--left .archive__item-body,
    .research-highlights .feature__item--right .archive__item-body {
      flex: 1 1 40%;
      min-width: 240px;
      float: none !important;
      width: auto !important;
      margin: 0 !important;
      text-align: left;
    }
    .research-highlights .feature__item--text-only .archive__item-body {
      flex: 1 1 100%;
      max-width: 100%;
    }
  }
  .research-highlights .archive__item-teaser img {
    width: 100%;
    height: auto;
    border-radius: 6px;
    box-shadow: 0 2px 12px rgba(0,0,0,0.08);
  }
  .research-highlights .feature__wrapper--eusipco .archive__item-teaser {
    flex: 0 0 auto !important;
    max-width: 220px !important;
    min-width: 0 !important;
  }
  .research-highlights .feature__wrapper--eusipco .archive__item-teaser img {
    max-width: 220px;
  }
</style>

<div class="research-highlights">

<div class="feature__wrapper">
  <div class="feature__item feature__item--left">
    <div class="archive__item-teaser">
      <a href="/publication/2025-learning-route-neurips"><img src="/images/home/neurips-2025.png" alt="Learning to Route (NeurIPS 2025)"></a>
    </div>
    <div class="archive__item-body">
      <h2>Multimodal and multitask learning</h2>
      <p>Per-sample adaptive routing for multimodal multitask prediction: each instance can follow a distinct computational path across modalities and tasks.</p>
      <p><strong>Selected paper:</strong></p>
      <ul>
        <li><a href="/publication/2025-learning-route-neurips">Learning to Route: Per-Sample Adaptive Routing for Multimodal Multitask Prediction (NeurIPS, 2025)</a></li>
      </ul>
    </div>
  </div>
</div>

<div class="feature__wrapper feature__wrapper--eusipco">
  <div class="feature__item feature__item--right">
    <div class="archive__item-teaser">
      <a href="/publication/2024-discrete-representation-eusipco"><img src="/images/home/eusipco-2024-generative-model.png" alt="Discrete representation learning (EUSIPCO 2024)"></a>
    </div>
    <div class="archive__item-body">
      <h2>Discrete representation learning for time series</h2>
      <p>Generative modeling of multivariate time series with discrete latent structure and a plate-structured graphical model for scalable representation learning.</p>
      <p><strong>Selected paper:</strong></p>
      <ul>
        <li><a href="/publication/2024-discrete-representation-eusipco">Discrete Representation Learning for Multivariate Time Series (EUSIPCO, 2024)</a></li>
      </ul>
    </div>
  </div>
</div>

<div class="feature__wrapper">
  <div class="feature__item feature__item--left feature__item--text-only">
    <div class="archive__item-body">
      <h2>High-dimensional filtering for sequential classification</h2>
      <p>Filtering methods for high-dimensional data streams applied to sequential classification, with emphasis on tractable inference in dynamic settings.</p>
      <p><strong>Selected paper:</strong></p>
      <ul>
        <li><a href="/publication/2024-filtering-high-dimensional-icif">Filtering of High-Dimensional Data for Sequential Classification (ICIF, 2024)</a></li>
      </ul>
    </div>
  </div>
</div>

<div class="feature__wrapper">
  <div class="feature__item feature__item--right feature__item--text-only">
    <div class="archive__item-body">
      <h2>Probabilistic ML and uncertainty quantification</h2>
      <p>The probabilistic machine learning thread emphasizes uncertainty quantification in deep and sequential models, scalable inference, and reliable prediction under distribution shift.</p>
      <p><strong>Selected papers:</strong></p>
      <ul>
        <li><a href="/publication/2025-exploring-synergies-signal-processing">Exploring Synergies: Advancing Neuroscience with Machine Learning (<i>Signal Processing</i>, 2025)</a></li>
        <li><a href="/publication/2024-gp-gated-hme-pami">Gaussian Process-gated Hierarchical Mixtures of Experts (IEEE TPAMI, 2024)</a></li>
        <li><a href="/publication/2023-sequential-estimation-deep-ssm-tsp">Sequential Estimation of Gaussian Process-based Deep State-space Models (IEEE TSP, 2023)</a></li>
      </ul>
    </div>
  </div>
</div>

<div class="feature__wrapper">
  <div class="feature__item feature__item--left feature__item--text-only">
    <div class="archive__item-body">
      <h2>Time series, graphs, and healthcare applications</h2>
      <p>Bayesian and probabilistic models address multivariate time-series and graph-structured data in applied settings, including healthcare and sensor-driven decision systems.</p>
      <p><strong>Selected papers:</strong></p>
      <ul>
        <li><a href="/publication/2023-gaussian-latent-variable-icassp">A Gaussian Latent Variable Model for Incomplete Mixed Type Data (ICASSP, 2023)</a></li>
        <li><a href="/publication/2023-time-varying-graph-icassp">Estimation of Time-Varying Graph Topologies from Graph Signals (ICASSP, 2023)</a></li>
        <li><a href="/publication/2022-boost-ensemble-ctg-icassp">Boost Ensemble Learning for Classification of CTG Signals (ICASSP, 2022)</a></li>
      </ul>
    </div>
  </div>
</div>

</div>
