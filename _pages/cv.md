---
layout: archive
title: ""
permalink: /cv/
author_profile: false
#redirect_from:
#  - /resume
---

{% include base_path %}

<style>
.cv-wrap {
  max-width: 900px;
}

.cv-download {
  margin: 0 0 1.8rem 0;
}

.cv-download a {
  display: inline-block;
  padding: 0.48rem 0.85rem;
  border: 1px solid #d9dde2;
  border-radius: 8px;
  background: #f7f8fa;
  color: #333;
  font-size: 0.9em;
  font-weight: 600;
  text-decoration: none;
  transition: background 0.18s ease, transform 0.18s ease;
}

.cv-download a:hover {
  background: #eef1f4;
  transform: translateY(-1px);
}

.cv-section {
  margin: 0 0 2.25rem 0;
}

.cv-heading {
  font-size: 1.28em;
  font-weight: 700;
  line-height: 1.25;
  margin: 0 0 0.9rem 0;
  padding-bottom: 0.38rem;
  border-bottom: 1px solid #e8eaed;
  color: #2b2b2b;
}

.cv-entry {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 105px;
  column-gap: 1rem;
  padding: 0.58rem 0;
}

.cv-entry + .cv-entry {
  border-top: 1px solid #f0f1f2;
}

.cv-main {
  min-width: 0;
}

.cv-title {
  font-size: 0.97em;
  font-weight: 650;
  color: #292929;
  line-height: 1.4;
}

.cv-place {
  margin-top: 0.08rem;
  font-size: 0.89em;
  color: #686d73;
  line-height: 1.4;
}

.cv-date {
  text-align: right;
  font-size: 0.85em;
  color: #7a7f86;
  white-space: nowrap;
  padding-top: 0.08rem;
}

.award-list {
  border-left: 2px solid #edf0f3;
  margin-left: 0.35rem;
  padding-left: 1.05rem;
}

.award-item {
  position: relative;
  padding: 0.46rem 0 0.7rem 0;
  font-size: 0.94em;
  line-height: 1.5;
  color: #333;
}

.award-item::before {
  content: "";
  position: absolute;
  left: -1.37rem;
  top: 0.83rem;
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #8d98a5;
  border: 2px solid #fff;
  box-shadow: 0 0 0 1px #d9dde2;
}

.award-note {
  color: #74787d;
  font-size: 0.92em;
}

@media (max-width: 600px) {
  .cv-entry {
    grid-template-columns: 1fr;
    row-gap: 0.12rem;
  }

  .cv-date {
    text-align: left;
  }
}
</style>

<div class="cv-wrap">

  <div class="cv-download">
    <a href="https://www.dropbox.com/scl/fi/8ee74fsz94n5c0tzhfib8/cv_shi.pdf?rlkey=0jxbsqpyhoqu3ozpevl9xay93&st=nswqggrd&dl=0">Download CV (PDF)</a>
  </div>

  <section class="cv-section">
    <h2 class="cv-heading">Education</h2>

    <div class="cv-entry">
      <div class="cv-main">
        <div class="cv-title">Ph.D. in Statistics</div>
        <div class="cv-place">University of California, Davis</div>
      </div>
      <div class="cv-date">2019–2024</div>
    </div>

    <div class="cv-entry">
      <div class="cv-main">
        <div class="cv-title">B.S. in Mathematics</div>
        <div class="cv-place">Fudan University</div>
      </div>
      <div class="cv-date">2015–2019</div>
    </div>
  </section>

  <section class="cv-section">
    <h2 class="cv-heading">Honors &amp; Awards</h2>

    <div class="award-list">
      <div class="award-item">22nd INFORMS Applied Probability Society Conference Travel Award</div>
      <div class="award-item">Graduate Studies 2023–24 Spring Travel Award, UC Davis</div>
      <div class="award-item">
        Peter Hall Graduate Student Research Award
        <span class="award-note"> · recognizing overall excellence in statistical research during doctoral study at UC Davis</span>
      </div>
      <div class="award-item">
        Graduate Star Award nominee
        <span class="award-note"> · highest undergraduate student award at Fudan University, among the top 10 nominees</span>
      </div>
      <div class="award-item">
        National Scholarship
        <span class="award-note"> · highest national honor for undergraduate students in China, awarded to the top 0.2% nationwide</span>
      </div>
    </div>
  </section>

</div>
