---
layout: archive
title: ""
permalink: /publications/
author_profile: false
---

{% include base_path %}

<style>
/* ---------- Publication page ---------- */
.pub-list {
  margin-top: 0.35rem;
}

.pub-section {
  margin: 2.1rem 0 1.05rem 0;
  padding-bottom: 0.38rem;
  border-bottom: 1px solid #eceff3;
  font-size: 1.22rem;
  font-weight: 650;
  line-height: 1.25;
  color: #2b2f33;
}

.pub-section:first-of-type {
  margin-top: 0.8rem;
}

.pub-row {
  display: flex;
  gap: 1.15rem;
  align-items: center;
  margin: 0 0 1.35rem 0;
  padding: 0.5rem 0;
}

.pub-left {
  flex: 0 0 170px;
  width: 170px;
}

/* The frame follows the PNG's own aspect ratio so the full figure is visible. */
.pub-figure {
  width: 170px;
  overflow: hidden;
  box-sizing: border-box;
  background: #f4f6f9;
  border: 1px solid #e1e5eb;
  border-radius: 10px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.025);
}

.pub-figure img {
  width: 100%;
  height: auto;
  display: block;
  transition: transform 0.24s ease;
  transform-origin: center;
}

.pub-figure:hover img {
  transform: scale(1.055);
}

.pub-right {
  flex: 1 1 auto;
  min-width: 0;
}

.pub-title {
  margin: 0 0 0.28rem 0;
  font-size: 1.01rem;
  font-weight: 650;
  line-height: 1.33;
  color: #202428;
}

.pub-title a,
.pub-title a:visited {
  color: #202428;
  text-decoration: none;
}

.pub-title a:hover {
  color: #111;
  text-decoration: underline;
  text-decoration-thickness: 1px;
  text-underline-offset: 2px;
}

.pub-authors {
  margin-bottom: 0.26rem;
  font-size: 0.91rem;
  line-height: 1.38;
  color: #4b5055;
}

.pub-meta {
  font-size: 0.89rem;
  line-height: 1.35;
  color: #686d72;
}

.pub-venue-name {
  color: #0067c5;
  font-weight: 650;
}

.pub-note {
  margin-top: 0.24rem;
  font-size: 0.86rem;
  line-height: 1.35;
  color: #73787d;
}

.pub-row-text-only {
  padding-left: 0;
}

@media (max-width: 720px) {
  .pub-row {
    gap: 0.9rem;
    align-items: flex-start;
  }

  .pub-left,
  .pub-figure {
    width: 120px;
  }

  .pub-left {
    flex-basis: 120px;
  }

  .pub-title {
    font-size: 0.96rem;
  }

  .pub-authors,
  .pub-meta {
    font-size: 0.85rem;
  }
}

@media (max-width: 480px) {
  .pub-row {
    display: block;
    margin-bottom: 1.55rem;
  }

  .pub-left,
  .pub-figure {
    width: 100%;
  }

  .pub-left {
    margin-bottom: 0.7rem;
  }

  .pub-figure {
    max-width: 260px;
  }
}
</style>

<div class="pub-list">

<h2 class="pub-section">Statistical Inference &amp; Learning</h2>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/LPSE_FM_github.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/pdf/2608.08422">Population-Level Generative Modeling for Ranking Data</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>.</div>
    <div class="pub-meta"><span class="pub-venue-name">Preprint</span> · 2026</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/demixing.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2603.27457">Optimal Demixing of Nonparametric Densities</a></div>
    <div class="pub-authors">Jianqing Fan, Zheng Tracy Ke and <strong>Zhaoyang Shi</strong>. <span style="color:#777;">(alphabetical order)</span></div>
    <div class="pub-meta"><span class="pub-venue-name">Preprint</span> · 2026</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/random_forest_pnn_thumbnail.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2403.09960">Multivariate Gaussian Approximation for Random Forest via Region-based Stabilization</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>, Chinmoy Bhattacharjee, Krishna Balasubramanian and Wolfgang Polonik.</div>
    <div class="pub-meta"><span class="pub-venue-name">Annals of Applied Probability</span> · Under revision, 2026</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/gaussian_ATE.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2412.17181">Gaussian and Bootstrap Approximation for Matching-based Average Treatment Effect Estimators</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>, Chinmoy Bhattacharjee, Krishna Balasubramanian and Wolfgang Polonik.</div>
    <div class="pub-meta"><span class="pub-venue-name">Annals of Statistics</span> · 2026</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/nonsmooth_regression.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2402.14985">Minimax Optimal Nonsmooth Nonparametric Regression via Fractional Laplacian Eigenmaps</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>, Krishna Balasubramanian and Wolfgang Polonik.</div>
    <div class="pub-meta"><span class="pub-venue-name">UAI</span> · 2025</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/eigenmap_regression.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2311.00140">Adaptive and Non-adaptive Minimax Rates for Weighted Laplacian-Eigenmap Based Nonparametric Regression</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>, Krishna Balasubramanian and Wolfgang Polonik.</div>
    <div class="pub-meta"><span class="pub-venue-name">AISTATS</span> · 2024</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/FSS.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2210.10744v1">A Flexible Approach for Normal Approximation of Geometric and Topological Statistics</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>, Krishna Balasubramanian and Wolfgang Polonik.</div>
    <div class="pub-meta"><span class="pub-venue-name">Bernoulli</span> · 2024</div>
  </div>
</div>

<h2 class="pub-section">Foundations of Generative AI</h2>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/energy_decrease.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2506.10801v1">Dense Associative Memory with Epanechnikov Energy</a></div>
    <div class="pub-authors">Benjamin Hoover, <strong>Zhaoyang Shi</strong>, Krishna Balasubramanian, Dmitry Krotov and Parikshit Ram.</div>
    <div class="pub-meta"><span class="pub-venue-name">NeurIPS</span> · Spotlight (Top 3%), 2025</div>
  </div>
</div>

<h2 class="pub-section">AI for Science &amp; Data Science</h2>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/LPSE_FM_github.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/pdf/2608.08422">Population-Level Generative Modeling for Ranking Data</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>.</div>
    <div class="pub-meta"><span class="pub-venue-name">Preprint</span> · 2026</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/CMARL.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2505.09756v1">Community-based Multi-Agent Reinforcement Learning with Transfer and Active Exploration</a></div>
    <div class="pub-authors"><strong>Zhaoyang Shi</strong>.</div>
    <div class="pub-meta"><span class="pub-venue-name">Preprint</span> · 2026</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/energy_decrease.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://arxiv.org/abs/2506.10801v1">Dense Associative Memory with Epanechnikov Energy</a></div>
    <div class="pub-authors">Benjamin Hoover, <strong>Zhaoyang Shi</strong>, Krishna Balasubramanian, Dmitry Krotov and Parikshit Ram.</div>
    <div class="pub-meta"><span class="pub-venue-name">NeurIPS</span> · Spotlight (Top 3%), 2025</div>
  </div>
</div>

<div class="pub-row">
  <div class="pub-left">
    <div class="pub-figure">
      <img src="/website/images/mask_rcnn.png">
    </div>
  </div>
  <div class="pub-right">
    <div class="pub-title"><a href="https://dl.acm.org/doi/abs/10.1145/3215525.3215539">The Analysis of Features Importance in Electrical Infrared Images Faults Diagnosis</a></div>
    <div class="pub-authors">Qi Zhao, Lei Su, <strong>Zhaoyang Shi</strong>, Ping Ling, Nannan Yan, Chunjie Gu and Zhixiong Shi.</div>
    <div class="pub-meta"><span class="pub-venue-name">ACM</span> · 2018</div>
  </div>
</div>

<h2 class="pub-section">Under Preparation</h2>

<div class="pub-row pub-row-text-only">
  <div class="pub-right">
    <div class="pub-title">Minimax Optimal Mixed-membership Estimation in Continuous-time Dynamic Network</div>
    <div class="pub-authors">Zheng Tracy Ke and <strong>Zhaoyang Shi</strong>.</div>
    <div class="pub-note">Presented at JSM 2025.</div>
  </div>
</div>

</div>
