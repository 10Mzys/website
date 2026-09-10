---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-wrap {
  max-width: 880px;
  color: #333;
}

/* Intro */
.home-intro {
  margin: 0 0 1.45rem 0;
  font-size: 0.98em;
  line-height: 1.7;
}

.home-intro p {
  margin: 0 0 0.85rem 0;
}

.home-intro a,
.home-news a {
  text-decoration: none;
}

.home-intro a:hover,
.home-news a:hover {
  text-decoration: underline;
}

/* Research areas */
.home-section-title {
  font-size: 1.22em;
  font-weight: 700;
  line-height: 1.3;
  color: #2b2b2b;
  margin: 1.65rem 0 0.8rem 0;
  padding-bottom: 0.35rem;
  border-bottom: 1px solid #e8eaed;
}

.research-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.65rem;
  margin: 0.2rem 0 1.35rem 0;
}

.research-card {
  padding: 0.82rem 0.9rem;
  border: 1px solid #e5e8eb;
  border-radius: 9px;
  background: #f8f9fa;
}

.research-card-title {
  font-size: 0.91em;
  font-weight: 700;
  color: #2d3135;
  line-height: 1.35;
  margin-bottom: 0.3rem;
}

.research-card-text {
  font-size: 0.82em;
  color: #666b70;
  line-height: 1.48;
}

/* Appointment / collaboration callout */
.home-callout {
  margin: 1.15rem 0 1.65rem 0;
  padding: 0.9rem 1rem;
  border-left: 3px solid #8a97a5;
  background: #f7f8fa;
  border-radius: 0 8px 8px 0;
  font-size: 0.92em;
  line-height: 1.58;
  color: #42464b;
}

.home-callout strong {
  color: #272b2f;
}

/* News timeline */
.home-news {
  position: relative;
  margin: 0.15rem 0 0 0;
  padding-left: 1.05rem;
  border-left: 2px solid #eceff2;
}

.news-item {
  position: relative;
  padding: 0.05rem 0 0.95rem 0.75rem;
  font-size: 0.91em;
  line-height: 1.55;
  color: #44484d;
}

.news-item::before {
  content: "";
  position: absolute;
  left: -1.35rem;
  top: 0.43rem;
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #8d98a5;
  border: 2px solid #fff;
  box-shadow: 0 0 0 1px #d9dde2;
}

.news-tag {
  display: inline-block;
  margin-right: 0.35rem;
  font-size: 0.78em;
  font-weight: 700;
  letter-spacing: 0.01em;
  color: #69717a;
}

.news-item strong {
  color: #303438;
}

@media (max-width: 820px) {
  .research-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="home-wrap">

  <div class="home-intro">
    <p>
      I am an Assistant Professor of the Center for Applied Mathematics at Fudan University,
    with a joint appointment in the School of Mathematical Sciences. From 2024 to 2026, I was a Postdoctoral Fellow in the Department of Statistics at Harvard University, under the supervision of
      <a href="https://zke.fas.harvard.edu/">Prof. Zheng (Tracy) Ke</a>.
      I received my Ph.D. in Statistics from UC Davis, where I was co-advised by
      <a href="https://sites.google.com/view/kriznakumar/">Prof. Krishna Balasubramanian</a> and
      <a href="https://www.stat.ucdavis.edu/~polonik/">Prof. Wolfgang Polonik</a>.
      Before UC Davis, I received my B.S. in Mathematics from Fudan University, where I was advised by
      <a href="https://mastone1983.github.io/">Prof. Lei Shi</a>.
    </p>

    <p>
      My research lies at the intersection of <strong>statistics, machine learning, and artificial intelligence</strong>,
      with an emphasis on developing theory and methods for reliable statistical inference, understanding modern AI models,
      and solving complex scientific and data-driven problems.
    </p>
  </div>

  <h2 class="home-section-title">Research</h2>

  <div class="research-grid">
    <div class="research-card">
      <div class="research-card-title">Statistical Inference &amp; Learning</div>
      <div class="research-card-text">
        Nonparametric and high-dimensional statistics, network analysis, Gaussian and bootstrap approximation,
        and uncertainty quantification.
      </div>
    </div>

    <div class="research-card">
      <div class="research-card-title">Foundations of Generative AI</div>
      <div class="research-card-text">
        Associative memory, energy-based models, diffusion models, and flow-based generative models.
      </div>
    </div>

    <div class="research-card">
      <div class="research-card-title">Data Science &amp; Decision Making</div>
      <div class="research-card-text">
        AI and statistical methods for scientific discovery, complex systems, interdisciplinary data,
        and data-driven decision-making.
      </div>
    </div>
  </div>

  <div class="home-callout">
    <strong> Collaborations:</strong> I am always open to collaborations and new research directions. Feel free to reach out if you are interested in working together.
  </div>
  
  <div class="home-callout">
    <strong> Prospective PhD Students:</strong> : PhD admissions are handled by the departmental admissions committee. If you are interested in working with me, please indicate me as a potential advisor in your application.
  </div>

  <h2 class="home-section-title">Recent News</h2>

  <div class="home-news">

      <div class="news-item">
      <span class="news-tag">New Position</span>
       I joined the Center for Applied Mathematics at Fudan University,
    with a joint appointment in the School of Mathematical Sciences, as a tenure-track Assistant Professor on Sep 3 2026.
    </div>


    <div class="news-item">
      <span class="news-tag">CMStatistics 2026</span>
      Invited talk:
      <strong>Mixed Membership Amid Dynamic Networks</strong>,
      <a href="https://www.cmstatistics.org/CFECMStatistics2026/">the 20th International Joint Conference on Computational and Financial Econometrics (CFE) and Computational and Methodological Statistics (CMStatistics)</a>, HTW Berlin, Germany, Dec 12-Dec 14, 2026.
    </div>


    <div class="news-item">
      <span class="news-tag">NEW</span>
      Our work
      <a href="https://arxiv.org/pdf/2608.08422"><strong>Population-Level Generative Modeling for Ranking Data</strong></a>
      is now available on arXiv. We introduce latent preference simplex embedding with flow matching (LPSE-FM)
      for accurate synthetic ranking generation and interpretable modeling of preference heterogeneity.
    </div>

    <div class="news-item">
      <span class="news-tag">ICLR 2026</span>
      I will co-organize the workshop
      <a href="https://nfam2026.amemory.net/"><strong>New Frontiers in Associative Memory</strong></a>.
    </div>

    <div class="news-item">
      <span class="news-tag">AoS</span>
      <a href="https://arxiv.org/abs/2412.17181"><strong>Gaussian and Bootstrap Approximation for Matching-based Average Treatment Effect Estimators</strong></a>
      has been accepted by <strong>Annals of Statistics</strong>. Using ATE estimation in causal inference as a motivating example,
      we develop a general framework for non-asymptotic statistical inference through local geometry and stabilization.
    </div>

    <div class="news-item">
      <span class="news-tag">NeurIPS</span>
      <a href="https://arxiv.org/abs/2506.10801v1"><strong>Dense Associative Memory with Epanechnikov Energy</strong></a>
      was accepted as a <strong>Spotlight (top 3%)</strong>. We propose the log-sum-ReLU (LSR) energy,
      inspired by the optimal kernel in kernel density estimation, to address the memorization-generation trade-off in dense associative memories.
    </div>

    <div class="news-item">
      <span class="news-tag">SIAM UQ26</span>
      Invited talk:
      <strong>From Smooth to Nonsmooth: Minimax Optimal Regression with Laplacian Eigenmaps</strong>,
      at the minisymposium
      <a href="https://www.siam.org/conferences-events/siam-conferences/uq26/">Probabilistic Manifold Learning and Deep Embeddings for Uncertainty Quantification</a>,
      March 2026.
    </div>

    <div class="news-item">
      <span class="news-tag">JSM 2025</span>
      Invited talk:
      <strong>Smooth Dynamic Network Analysis</strong>,
      at <a href="https://ww2.amstat.org/meetings/jsm/2025/">JSM 2025</a>, August 2025.
    </div>

    <div class="news-item">
      <span class="news-tag">APS 2025</span>
      Talk:
      <strong>On the Nonasymptotic Statistical Inferences via Stabilization Theory of Gaussian Approximation Bounds</strong>,
      at the <a href="https://informs-aps.isye.gatech.edu/program">22nd INFORMS Applied Probability Society Conference</a>,
      Georgia Institute of Technology, June 30–July 3, 2025.
    </div>

    <div class="news-item">
      <span class="news-tag">2024</span>
      I joined the Department of Statistics at Harvard University as a Postdoctoral Fellow on September 1, 2024.
    </div>

  </div>

</div>
