---
layout: page
title: R data workflows
permalink: /showcase/r-workflows/
description: End-to-end R pipelines for cleaning, structuring tables, and ggplot reporting
---

<div class="case">

<header class="case__header">
  <h1 class="case__title">R data workflows</h1>
  <div class="case__links">
    <a href="/showcase/">Showcase</a>
    <span class="case__links-right">
      <a href="https://github.com/a-teixeira/party-discourse-lda-r" target="_blank" rel="noopener">GitHub</a>
    </span>
  </div>
</header>

<div class="case__grid">
  <article class="case__main">

    <img class="case__hero"
         src="/assets/img/showcase/r-hero.jpg"
         alt="R data workflow and ggplot output">

    <blockquote class="case__quote">
      “Good charts start long before ggplot — in clean types, stable keys, and tables
      you can trust.”
    </blockquote>

    <h2 id="role">Focus</h2>
    <p>
      Practical <strong>R</strong> work across <strong>1,000+ lines</strong> of code:
      cleaning messy extracts, structuring analysis-ready tables, and building
      clear <strong>ggplot2</strong> figures for exploration and reporting.
      Overlaps with research-data habits from CoronaNet (validation, repeatable steps).
    </p>

    <h2 id="problem">Problem</h2>
    <p>
      Raw files rarely arrive analysis-ready: mixed types, inconsistent categories,
      missing keys, and one-off spreadsheet logic. Without a documented pipeline,
      every new chart becomes a new cleanup.
    </p>

    <h2 id="what-i-did">What I did</h2>
    <ul>
      <li><strong>Cleaning:</strong> type fixes, missing-value rules, category standardization, duplicate checks.</li>
      <li><strong>Structuring:</strong> joins/reshapes into tidy tables meant for reuse (not one notebook cell).</li>
      <li><strong>Tables:</strong> summary tables for QA and stakeholder-facing metrics.</li>
      <li><strong>Visualization:</strong> ggplot2 for distributions, comparisons over time, and category breakdowns.</li>
      <li><strong>Reproducibility:</strong> scripts ordered as clean → tables → plots so results can be re-run.</li>
    </ul>

    <img class="case__photo"
         src="/assets/img/showcase/r-ggplot.jpg"
         alt="Example ggplot figure">

    <h2 id="stack">Stack</h2>
    <p>
      R · tidyverse-style wrangling · data validation checks · ggplot2 ·
      exportable figures for reports
    </p>

    <h2 id="output">Output</h2>
    <ul>
      <li>Analysis-ready tables from raw extracts</li>
      <li>Documented transformation steps</li>
      <li>ggplot figures suitable for slides or write-ups</li>
    </ul>

    <h2 id="note">Note on data</h2>
    <p>
      Portfolio code uses <strong>public, toy, or anonymized</strong> samples where needed.
      Confidential research microdata is not published — the GitHub repo shows
      <em>method</em> and structure, not restricted sources.
    </p>

    <h2 id="links">Links</h2>
    <ul>
      <li><a href="https://github.com/a-teixeira/YOUR-R-REPO">R workflows on GitHub</a> <!-- replace URL --></li>
      <li><a href="/showcase/coronanet/">Related experience: CoronaNet</a></li>
    </ul>

  </article>

  <aside class="case__rail">
    <div class="case__rail-block">
      <h3>Description</h3>
      <p>R pipelines from raw extracts to tidy tables and ggplot reporting — 1000+ lines of practical code.</p>
    </div>
    <div class="case__rail-block">
      <h3>Table of contents</h3>
      <nav>
        <a href="#role">Focus</a>
        <a href="#problem">Problem</a>
        <a href="#what-i-did">What I did</a>
        <a href="#stack">Stack</a>
        <a href="#output">Output</a>
        <a href="#note">Note on data</a>
        <a href="#links">Links</a>
      </nav>
    </div>
  </aside>
</div>

</div>