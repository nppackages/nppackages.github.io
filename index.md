---
layout: page
title: Home
permalink: /
description: Software packages for nonparametric and semiparametric methods.
---

<section class="hero" aria-labelledby="intro">
  <h1 id="intro">Nonparametric & Semiparametric Methods</h1>
  <p class="lead">NP Packages collects maintained software for estimation, inference, and visualization using nonparametric and semiparametric methods with applications to program evaluation, treatment effect estimation, causal inference, and related problems.</p>
</section>

<section id="packages" class="section" aria-labelledby="packages-title">
  <div class="section-header">
    <h2 id="packages-title">Packages</h2>
  </div>

  <div class="package-grid">
    <article class="package-card">
      <div>
        <div class="package-card-header">
          <h3><a href="https://github.com/nppackages/binsreg">binsreg</a></h3>
        </div>
        <p>Binscatter methods for partition selection, point estimation, pointwise and uniform inference, and graphical procedures.</p>
      </div>
      <ul class="language-list" aria-label="Available languages">
        <li>Python</li>
        <li>R</li>
        <li>Stata</li>
      </ul>
    </article>

    <article class="package-card">
      <div>
        <div class="package-card-header">
          <h3><a href="https://github.com/nppackages/portsort">portsort</a></h3>
        </div>
        <p>Estimation and inference using portfolio sorting methods.</p>
      </div>
      <ul class="language-list" aria-label="Available languages">
        <li>Python</li>
        <li>R</li>
        <li>Stata</li>
      </ul>
    </article>

    <article class="package-card">
      <div>
        <div class="package-card-header">
          <h3><a href="https://github.com/nppackages/lspartition">lspartition</a></h3>
        </div>
        <p>Estimation and inference using partitioning-based least squares methods, B-splines, wavelets, and piecewise polynomials.</p>
      </div>
      <ul class="language-list" aria-label="Available languages">
        <li>R</li>
      </ul>
    </article>

    <article class="package-card">
      <div>
        <div class="package-card-header">
          <h3><a href="https://github.com/nppackages/nprobust">nprobust</a></h3>
        </div>
        <p>Estimation and inference using kernel density and local polynomial regression methods.</p>
      </div>
      <ul class="language-list" aria-label="Available languages">
        <li>R</li>
        <li>Stata</li>
      </ul>
    </article>

    <article class="package-card">
      <div>
        <div class="package-card-header">
          <h3><a href="https://github.com/nppackages/lpdensity">lpdensity</a></h3>
        </div>
        <p>Estimation and inference using local polynomial distribution and density regression methods.</p>
      </div>
      <ul class="language-list" aria-label="Available languages">
        <li>Python</li>
        <li>R</li>
        <li>Stata</li>
      </ul>
    </article>

    <article class="package-card">
      <div>
        <div class="package-card-header">
          <h3><a href="https://github.com/nppackages/lpcde">lpcde</a></h3>
        </div>
        <p>Estimation and inference using local polynomial conditional distribution and density regression methods.</p>
      </div>
      <ul class="language-list" aria-label="Available languages">
        <li>R</li>
      </ul>
    </article>

    <article class="package-card">
      <div>
        <div class="package-card-header">
          <h3><a href="https://github.com/nppackages/scpi">scpi</a></h3>
        </div>
        <p>Estimation and inference using synthetic control methods for causal analysis.</p>
      </div>
      <ul class="language-list" aria-label="Available languages">
        <li>Python</li>
        <li>R</li>
        <li>Stata</li>
      </ul>
    </article>
  </div>
</section>

<section id="replication" class="section" aria-labelledby="replication-title">
  <div class="section-header">
    <h2 id="replication-title">Replication Files</h2>
    <p>Examples, paper replications, and companion code are collected on the <a href="{{ '/replication/' | relative_url }}">replication page</a>.</p>
  </div>
</section>

<section id="references" class="section" aria-labelledby="references-title">
  <div class="section-header">
    <h2 id="references-title">References</h2>
    <p>Selected software articles and methodological references for NP methods and applications.</p>
  </div>

  <ol class="reference-list">
    <li>
      Calonico, Cattaneo and Farrell (2019): <a href="{{ '/references/Calonico-Cattaneo-Farrell_2019_JSS.pdf' | relative_url }}">nprobust: Nonparametric Kernel-Based Estimation and Robust Bias-Corrected Inference</a>.
      <span><em>Journal of Statistical Software</em> 91(8): 1-33.</span>
    </li>
    <li>
      Cattaneo, Farrell and Feng (2020): <a href="{{ '/references/Cattaneo-Farrell-Feng_2020_R.pdf' | relative_url }}">lspartition: Partitioning-Based Least Squares Regression</a>.
      <span><em>R Journal</em> 12(1): 172-187.</span>
    </li>
    <li>
      Cattaneo, Jansson and Ma (2022): <a href="{{ '/references/Cattaneo-Jansson-Ma_2022_JSS.pdf' | relative_url }}">lpdensity: Local Polynomial Density Estimation and Inference</a>.
      <span><em>Journal of Statistical Software</em> 101(2): 1-25.</span>
    </li>
    <li>
      Cattaneo, Chandak, Jansson and Ma (2025): <a href="{{ '/references/Cattaneo-Chandak-Jansson-Ma_2025_JOSS.pdf' | relative_url }}">lpcde: Estimation and Inference for Local Polynomial Conditional Density Estimators</a>.
      <span><em>Journal of Open Source Software</em> 10(107): 7241.</span>
    </li>
    <li>
      Cattaneo, Crump, Farrell and Feng (2025): <a href="{{ '/references/Cattaneo-Crump-Farrell-Feng_2025_Stata.pdf' | relative_url }}">Binscatter Regressions</a>.
      <span><em>Stata Journal</em> 25(1): 3-50.</span>
    </li>
    <li>
      Cattaneo, Feng, Palomba and Titiunik (2025): <a href="{{ '/references/Cattaneo-Feng-Palomba-Titiunik_2025_JSS.pdf' | relative_url }}">scpi: Uncertainty Quantification for Synthetic Control Methods</a>.
      <span><em>Journal of Statistical Software</em> 113(1): 1-38.</span>
    </li>
  </ol>
</section>

<section id="contributors" class="section" aria-labelledby="contributors-title">
  <div class="section-header">
    <h2 id="contributors-title">Contributors</h2>
  </div>

  <ul class="people-list">
    <li><a href="https://sites.google.com/site/scalonico">Sebastian Calonico</a>UC Davis</li>
    <li><a href="https://mdcattaneo.github.io/">Matias D. Cattaneo</a>Princeton University</li>
    <li><a href="https://rajitachandak.github.io">Rajita Chandak</a>University of Wisconsin-Madison</li>
    <li><a href="https://richardcrump.github.io/">Richard K. Crump</a>Federal Reserve Bank of New York</li>
    <li><a href="https://maxhfarrell.com">Max H. Farrell</a>UC Santa Barbara</li>
    <li><a href="https://sites.google.com/site/yingjieum">Yingjie Feng</a>Tsinghua University</li>
    <li><a href="http://www.econ.berkeley.edu/~mjansson/index.html">Michael Jansson</a>UC Berkeley</li>
    <li><a href="https://sites.google.com/view/xinweima">Xinwei Ma</a>UC San Diego</li>
    <li><a href="https://anson.ucdavis.edu/~rmasini">Ricardo Masini</a>UC Davis</li>
    <li><a href="https://filippopalomba.github.io">Filippo Palomba</a>Princeton University</li>
    <li><a href="https://titiunik.github.io">Rocio Titiunik</a>Princeton University</li>
  </ul>
</section>

<section id="funding" class="section" aria-labelledby="funding-title">
  <div class="section-header">
    <h2 id="funding-title">Funding</h2>
    <p>This work was supported in part by the National Science Foundation, the National Institutes of Health, and the National Institute for Food and Agriculture.</p>
  </div>

  <ul class="funding-list" aria-label="Funding grants">
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1459931">NSF SES-1459931</a></li>
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1459967">NSF SES-1459967</a></li>
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1947662">NSF SES-1947662</a></li>
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1947805">NSF SES-1947805</a></li>
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2019432">NSF SES-2019432</a></li>
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2210561">NSF DMS-2210561</a></li>
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2241575">NSF SES-2241575</a></li>
    <li><a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2342226">NSF SES-2342226</a></li>
    <li><a href="https://reporter.nih.gov/project-details/10093056">NIH R01 GM072611-16</a></li>
    <li><a href="https://www.nifa.usda.gov/data">NIFA 2024-67023-42704</a></li>
  </ul>
</section>
