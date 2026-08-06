---
layout: page
title: Party discourse (R / LDA)
permalink: /showcase/party-discourse-lda/
description: LDA topic models on ~1.59M German party tweets — TUM CSS
---

<div class="case">
<div class="case__grid">

<article class="case__main">

<p class="case__back"><a href="{{ '/showcase/' | relative_url }}">← Showcase</a>
·
<a href="https://github.com/a-teixeira/party-discourse-lda-r" target="_blank" rel="noopener">GitHub</a></p>

<img class="case__hero" src="{{ '/assets/img/showcase/discourse-lda-r.png' | relative_url }}" alt="Party discourse LDA poster">

<h2 id="focus">Focus</h2>
<p>TUM CSS course project: large-scale text analysis of German party communication on Twitter using <strong>R</strong>, <strong>quanteda</strong>, and <strong>LDA</strong>.</p>

<h2 id="problem">Problem</h2>
<p>Which latent themes structure German party tweets, and how do <strong>AfD, Linke, CDU, CSU, Grüne, SPD</strong> differ in emphasis over time?</p>

<h2 id="what-i-did">What I did</h2>
<ul>
<li>Built a pipeline on <strong>~1.59 million tweets (2012–2018)</strong>.</li>
<li><strong>Preprocessing</strong> with quanteda (tokens, cleaning, document-feature matrix).</li>
<li><strong>Topic discovery:</strong> seeded LDA (<code>seededlda::textmodel_lda</code>, k=5/10) and Gibbs LDA (K=5, 500 iterations).</li>
<li><strong>Longitudinal analysis:</strong> tracked LDA-derived top terms by party and month.</li>
<li><strong>Visualization:</strong> ggplot2 comparisons of frequencies and party shares over time.</li>
<li>Documented an interpretable topic structure (e.g. law/critique, Euro, government, Europe/migration, parliament, democracy/violence) and cross-party differences in emphasis.</li>
</ul>

<h2 id="result">Result</h2>
<p>Computational social science / big-text analysis at multi-million document scale: clear topics plus time series of how parties weight themes differently.</p>

<h2 id="stack">Stack</h2>
<p>R · quanteda · seededlda · topicmodels · dplyr · lubridate · ggplot2 · readtext</p>

<h2 id="links">Links</h2>
<p><a href="https://github.com/a-teixeira/party-discourse-lda-r" target="_blank" rel="noopener">GitHub</a></p>


</article>
</div>
</div>