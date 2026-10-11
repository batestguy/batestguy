### Hi, I'm Jerry Zachary Bannister

Statistician and data scientist in Bauchi, Nigeria. I build uncertainty-aware models and open tools for health, poverty and inclusion data.

#### What I do

- **Bayesian and machine-learning models**, always reported against an honest baseline and with their uncertainty shown.
- **End-to-end pipelines** on free cloud infrastructure: scheduled ingestion, provenance manifests, tests and CI.
- **Accessible apps**: screen-reader-safe layouts, keyboard navigation, voice input and high contrast.
- **Reproducible research**: raw data to manuscript-ready tables and figures in code, with R, Python and Quarto.
- **Statistical consultancy and training** through JJMB Datascience Hub.

#### Featured projects

| Project | Result | Stack | Links |
|---|---|---|---|
| Price intelligence pipeline | XGBoost demand forecast at 10.9% MAPE vs a 13.8% naive baseline; fine-tuned FinBERT at 76.8% vs 71.0% majority class; LP optimiser for price and stock moves. Synthetic sales data, documented as such. | Python, XGBoost, FinBERT, SciPy, Supabase, GitHub Actions | [repo](https://github.com/batestguy/tobacco-price-intelligence) · [dashboard](https://tobacco-price-intelligence.streamlit.app) |
| Crude Blend Optimizer | ML yield surrogates (5-fold R² ≥ 0.982) drive differential evolution to within $0.005/bbl of the exact LP optimum; VaR/CVaR over 10,000 price scenarios; 140 offline tests. | Python, scikit-learn, SciPy, Docker | [repo](https://github.com/batestguy/dangote-refinery-optimizer) · [site](https://batestguy.github.io/dangote-refinery-optimizer/) |
| Bayesian rainfall change-points | Hierarchical change-point model of 74 years of rainfall at 9 stations in 3 climate zones; the no-change model is rejected in every zone by LOO cross-validation. Manuscript in preparation. | Python, PyMC | [repo](https://github.com/batestguy/Bayesian-Change-Point-Detection-in-Nigerian-Rainfall-Patterns-A-Hierarchical-Analysis-Climate-Zones) |
| Bayesian World Cup | Hierarchical model of 22 World Cups with partial pooling; 50,000-run Monte Carlo tournament, counterfactual `do()` scenarios, served from precomputed posteriors. | Python, PyMC, Gradio | [repo](https://github.com/batestguy/soccer-eurovsSA) · [app](https://bayesian-world-cup-prediction.onrender.com) |
| Disability Rights Assistant | Multi-turn RAG over Nigeria's Disability Act 2018 and the Constitution, with a verified NGO and helpline connector. Built accessible from the start. | Python, RAG, Streamlit | [repo](https://github.com/batestguy/NGOdisabilityRAG) · [demo](https://ngodisabilityrag.onrender.com) |
| Nigeria Equity Atlas | State-level Multidimensional Poverty Index for all 36 states and the FCT, with conflict and climate overlays and a four-round trend, from a numbered, re-runnable pipeline. | Python, Tableau | [repo](https://github.com/batestguy/NigeriaEquityAtlas-Tableau) |
| Messi vs Ronaldo, weighted | Difficulty-weighted scoring rates (FAMD weighting) with a 10,000-resample match bootstrap; intervals and effect sizes instead of significance labels. | R, Shiny, bslib, Docker | [repo](https://github.com/batestguy/messi-vs-ronaldo-r) · [dashboard](https://qqxot9-batest-hommie.shinyapps.io/messi-vs-ronaldo-r/) |
| Sol Searching | 50 verified Kaduna businesses from a one-time OpenStreetMap import turned into a ranked solar sales pipeline with payback and risk–reward. | Python, Streamlit, OpenStreetMap | [repo](https://github.com/batestguy/kaduna-solar-lead-gen) · [demo](https://kaduna-solar-lead-ge-y3wljh2pqvkadljhlytgkg.streamlit.app) |

#### Education and honours

- 🥇 **MSc Statistics, ATBU (2024):** **Best in class** (top 1%)
- 🥈 **BSc Statistics, University of Maiduguri (2013):** **2nd best in class** (top 2%)
- 🎓 **MTN Foundation Scholarship (2009–2012)**, plus a place on the **Dean's List** every year from 2009 to 2012
- 📜 **Commendation letter** from ATBU's Directorate of Academic Planning (2021)

#### More work

**Apps and tools**
- [Dandali](https://github.com/batestguy/HealthMgtDashboard): maps 51,022 health facilities live from the GRID3 ArcGIS feed and falls back per feed when one is offline. Plain JavaScript and Leaflet, no build step. [Demo](https://batestguy.github.io/HealthMgtDashboard/).
- [Fieldmargin](https://github.com/batestguy/crop-value-predictor): an offline-first crop margin planner for Nigerian farmers that installs on a phone. React and TypeScript on Cloudflare Pages. [App](https://crop-value-predictor.pages.dev/).
- [Impact Mosaic](https://github.com/batestguy/AyubaDisabilityProg): a disability-programme showcase and learning sandbox with 8 courses, experimental Hausa, Yoruba and Igbo course journeys and administrator reports. React, TypeScript and Cloudflare Pages Functions.
- [ATBU Academic Planning Portal](https://github.com/batestguy/atbu-proflist-nuc-updates): a desktop app that manages 223 professor records and exports them in NUC format. Python, Flet and SQLite.

**Research pipelines**
- [Avian influenza in Nigeria, systematic review](https://github.com/batestguy/avian-influenza-nigeria-systematic-review): PRISMA 2020 screening of 2,157 records from six databases down to 113 included studies.
- [Anti-trypanosomal plant extracts](https://github.com/batestguy/comparative-anti-trypanosomal-activity-azadirachta-indica-moringa-oleifera): parses a messy Excel workbook into tidy data and runs block-level non-parametric tests with Holm adjustment through to a Word report. R and Quarto.
- [Non-O157 *E. coli* in fermented milk](https://github.com/batestguy/nono-analysis): prevalence with 95% CIs, ANOVA and antibiotic-susceptibility profiles for 200 isolates.
- [Urban agriculture and food security](https://github.com/batestguy/urban-agriculture-and-urban-food-security-in-nigeria): spatial statistics on API-sourced data, frozen to CSV for reproducibility.

#### Research

7 peer-reviewed papers in health and applied statistics, 5 citations. PhD in Statistics in progress at Abubakar Tafawa Balewa University (ATBU).

[Google Scholar](https://scholar.google.com/citations?user=oKaejtMAAAAJ) · [ORCID 0009-0002-3302-9558](https://orcid.org/0009-0002-3302-9558)

#### Toolbox

- **Languages:** Python, R, SQL, TypeScript/JavaScript
- **Statistics and ML:** PyMC, scikit-learn, XGBoost, TensorFlow/Keras, SciPy optimisation, survival, spatial and time-series models
- **Apps and reporting:** Streamlit, R Shiny, Gradio, React, Quarto, Tableau, Power BI
- **Engineering:** Git, GitHub Actions, Docker, Supabase, Cloudflare Pages, Render

#### Contact

[batesthommie@gmail.com](mailto:batesthommie@gmail.com) · [Blog](https://batestguy.github.io/QuartoWebsite-blog-others/)
