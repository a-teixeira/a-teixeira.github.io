---
layout: page
title: Projects
permalink: /projects/
description: Data analysis, research data, SQL, Python, R, and BI projects
---

Work across **research data**, **SQL**, **Python**, **R**, and **BI/Tableau** — from messy sources to analysis-ready outputs and clear visuals.

---

## Flagship

### CoronaNet Research Project (TUM / HfP)
**Data integration · harmonization · quality · R / analytics · coordination** · Jul 2021 – Oct 2023

[CoronaNet](https://www.coronanet-project.org) builds a fine-grained, public dataset of government COVID-19 policy responses for statistical and qualitative research.

#### Problem
Policy information was scattered across sources, formats, and languages. It had to be collected, coded, and **harmonized** so researchers could compare measures across countries and time.

#### What I did
- Completed a **500-hour** research internship, then continued as a hired contributor working with the principal investigators.
- Worked as **country expert**: weekly coding in a structured survey workflow (Qualtrics), validation, and coordination meetings.
- Led **data integration / harmonization**: brought external dataset feeds into CoronaNet and helped keep large, evolving tables consistent.
- Served as **Data Science Analyst**: supported technical management of the living dataset and reliable update pipelines for research use.
- As **regional / PM support**, monitored research assistants’ work and **data quality** in a network of **200+** RAs; onboarding, standards, feedback on errors.
- Used **R** for manipulation, descriptive analysis, and automated reporting; strong focus on process quality and reproducible steps.

#### Recognition
Named acknowledgement in the project article on harmonizing government COVID-19 responses — for **onboarding/training** RAs on data harmonization and for **monitoring and feedback on harmonization errors**; also involved in the **summer 2021 pilot** of the harmonization workflow.

*Article: “Harmonizing government responses to the COVID-19 pandemic” (acknowledgements; non-author contributor).*  
*Reference: Luca Messerschmidt, PI, CoronaNet / TUM — available on request.*

#### Stack
Research data workflows · data harmonization · quality control · R · structured coding · coordination

Links: [CoronaNet](https://www.coronanet-project.org) · [Article](https://www.nature.com/articles/s41597-023-02881-x)


<!-- 
## SQL

### [Title of your SQL project]
**SQL · analytics** · Year

**Problem.** What business or data question?  
**Approach.** Tables, joins, filters, metrics you defined.  
**Result.** What you could answer or automate.  
**Link.** [GitHub repo](https://github.com/a-teixeira/...)
 -->
<!-- Delete this block until you have a real project -->

---
<!-- 
## Python

### [Title of your Python project]
**Python · pandas / analysis** · Year

**Problem.**  
**Approach.** Cleaning, transforms, analysis.  
**Result.**  
**Link.** [GitHub](https://github.com/a-teixeira/...)
 -->
---

## R

### Party Discourse in German Political Communication (TUM CSS)
**R · quanteda · LDA · large-scale text · political communication** · TUM course project

**Problem:** Which latent themes structure German party tweets, and how do AfD, Linke, CDU, CSU, Grüne and SPD differ in emphasis over time?

**Approach:** Built a two-stage NLP pipeline on **~1.59M tweets (2012–2018)**: (1) quanteda preprocessing and **LDA topic discovery** (`seededlda::textmodel_lda` k=5/10 and Gibbs LDA K=5, 500 iterations); (2) longitudinal tracking of LDA-derived top terms by party and month, with ggplot2 comparisons of frequencies and party shares.

**Result:** Interpretable topic structure (e.g. law/critique, Euro, government, Europe/migration, parliament, democracy/violence) and cross-party time series showing differential thematic emphasis — computational social science / big-text analysis at multi-million document scale.

**Stack:** R, quanteda, seededlda, topicmodels, dplyr, lubridate, ggplot2, readtext

**Link:** [GitHub — party-discourse-lda-r](https://github.com/a-teixeira/party-discourse-lda-r)

<!-- ### [Title — or “Reporting workflows (CoronaNet-related)”]
**R · statistics / reporting** · Year

**Problem.**  
**Approach.**  
**Result.**  
**Link.** -->

---

## BI / Tableau

### Tableau Public portfolio (14+ vizzes)
**Tableau · interactive dashboards · Open data** · ongoing

**Problem:** Turn sales, geography, and operational data into views that answer business questions quickly — profitability, category trends, customer patterns, loss hotspots.

**Approach:** Built and published **15 visualizations** on Tableau Public (dashboards and analytical sheets): calculated fields, dual axes, maps, scatterplots, control charts, filters, and dashboard layout for stakeholder storytelling. Mix of **interactive dashboards** and focused single-sheet analyses (mainly Superstore; also CO₂, conflict, and other open datasets).

**Result:** A public portfolio of KPI- and question-driven views recruiters can open in the browser — no install needed.

**Stack:** Tableau Desktop / Public · calculated fields · dashboard actions · maps · time series

**Link:** [Tableau Public — Augusto Teixeira](https://public.tableau.com/app/profile/augusto.teixeira/vizzes)

---

### Featured 1 — Which of our sales are less profitable? - Map of Meaning
**Tableau · dashboard · profitability · geography**

**Problem:** Which regions/segments sell a lot but earn little (or lose money)?

**Approach:** Interactive **Map of Meaning** dashboard combining sales volume and profit signals so low-profit / high-sales areas stand out at a glance.

**Result:** Geographic profitability story — where to investigate discounts, mix, or cost — not just “who sold most.”

**Link:** [Open dashboard](https://public.tableau.com/app/profile/augusto.teixeira/viz/WhichofoursalesarelessprofitableMapofMeaning/Dashboard1)

---

### Featured 2 — Total Sales by Category over Time
**Tableau · time series · category performance**

**Problem:** How do category sales evolve — growth, seasonality, relative strength?

**Approach:** Category × time view of total sales to compare trajectories and spot shifts in the mix.

**Result:** Clear trend comparison across categories for planning and narrative (“what’s growing vs flat”).

**Link:** [Open viz](https://public.tableau.com/app/profile/augusto.teixeira/viz/TotalSalesbyCategoryoverTime/TotalSalesbyCategoryoverTime)

---

### Featured 3 — Superstore: are we losing or winning?
**Tableau · loss patterns · Superstore**

**Problem:** Overall, is the business winning on profit — and where do losses cluster?

**Approach:** Pattern-of-losses style view on Superstore to separate winning vs losing pockets (products/segments), not only headline revenue.

**Result:** Decision-oriented loss map: where profitability breaks even when sales look fine.

**Link:** [Open viz](https://public.tableau.com/app/profile/augusto.teixeira/viz/SuperstoreDatasetareweloosingorwinnning/PatternofLosses)

---

### Featured 4 — Customer Scatterplot
**Tableau · customer analytics · scatter**

**Problem:** How do customers distribute on key value metrics (e.g. sales vs profit)?

**Approach:** Scatterplot of customers to surface outliers, high-value vs high-volume, and segments that need a different offer or cost structure.

**Result:** Quick customer portfolio read — who to protect, who to fix, who is noise.

**Link:** [Open viz](https://public.tableau.com/app/profile/augusto.teixeira/viz/CustomerScatterplot_16934843484120/CustomerScatterplot)

---

<!-- Optional: keep this short list under the featured blocks if you want all titles visible -->
<details>
<summary>All published vizzes (15)</summary>

1. [Global CO2 Emissions](https://public.tableau.com/app/profile/augusto.teixeira/viz/GlobalCO2Emissions_17107622359230/Sheet1)
2. [Map of Meaning: Sales and Profits by Region](https://public.tableau.com/app/profile/augusto.teixeira/viz/MapofMeaningSalesandProfitsbyRegion/MapofMeaningSalesandProfitbyRegion)
3. [Total Sales by Category over Time](https://public.tableau.com/app/profile/augusto.teixeira/viz/TotalSalesbyCategoryoverTime/TotalSalesbyCategoryoverTime)
4. [Shipping Trend Q4 2014 - SuperSales Store](https://public.tableau.com/app/profile/augusto.teixeira/viz/ShippingTrendQ42014-SuperSalesStore/Dashboard1)
5. [Customer Scatterplot](https://public.tableau.com/app/profile/augusto.teixeira/viz/CustomerScatterplot_16934843484120/CustomerScatterplot)
6. [Which of our sales are less profitable? Map of Meaning](https://public.tableau.com/app/profile/augusto.teixeira/viz/WhichofoursalesarelessprofitableMapofMeaning/Dashboard1)
7. [Strip Plot & Control Chart](https://public.tableau.com/app/profile/augusto.teixeira/viz/StripPlotControlChart_16932326497170/ControlChart)
8. [Dont trust only in Statistics!](https://public.tableau.com/app/profile/augusto.teixeira/viz/DonttrustonlyinStatistics/VisualiseyourdatanotonlyStatistics)
9. [SuperStore Discount & Profit - 2011 until 2015](https://public.tableau.com/app/profile/augusto.teixeira/viz/SuperStoreDiscountProfit-2011until2015_16920266729280/Dashboard1)
10. [SuperStore Discount & Profit (sheet)](https://public.tableau.com/app/profile/augusto.teixeira/viz/SuperStoreDiscountProfit-2011until2015/SuperStoreDiscountProfit-2011until2015)
11. [Superstore Dataset: are we loosing or winnning?](https://public.tableau.com/app/profile/augusto.teixeira/viz/SuperstoreDatasetareweloosingorwinnning/PatternofLosses)
12. [Tallest Buildings Worldwide](https://public.tableau.com/app/profile/augusto.teixeira/viz/TallestBuildingsWorldwide/TallestBuildingsWorldwide)
13. [Superstore Calculation Table](https://public.tableau.com/app/profile/augusto.teixeira/viz/SuperstoreCalculationTable/ProfitabilitybyItem)
14. [Visualizing Conflict Worldwide](https://public.tableau.com/app/profile/augusto.teixeira/viz/VisualizingConflictWorldwide/Dashboard1)
15. [Data Visualization with Tableau](https://public.tableau.com/app/profile/augusto.teixeira/viz/DataVisualizationwithTableau_16914068120650/Dashboard1)

</details>

---

## How I work on projects

1. Consult with Stakeholders  
2. Define the question and success metric  
3. Choose SQL, Python, R, or BI for each task  
4. Clean, structure, and validate 
5. Analize, model, and visualize to extract insights
6. Deliver something another person can audit and use