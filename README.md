### Hi, I'm Jerry Zachary Bannister

Statistician and data scientist in Bauchi, Nigeria. I build uncertainty-aware models and open tools for health, poverty and inclusion data.


I have over ten years of experience in institutional statistics at Abubakar Tafawa Balewa University (ATBU), where I am now a Senior Statistician, supporting National Universities Commission (NUC) reporting, accreditation and Senate decisions.

#### What I do

- **Bayesian and machine-learning models**, always reported against an honest baseline and with their uncertainty shown.
- **AI and LLM applications (RAG)**: retrieval measured on held-out question sets, answers that cite their sources and are checked automatically, and an AI judge used alongside human-checked ground truth. Example: [DRLCA](https://github.com/batestguy/NGOdisabilityRAG).
- **End-to-end pipelines** on free cloud infrastructure: scheduled ingestion, provenance manifests, tests and CI.
- **Accessible apps**: screen-reader-safe layouts, keyboard navigation, voice input and high contrast.
- **Reproducible research**: raw data to manuscript-ready tables and figures in code, with R, Python and Quarto.
- **Statistical consultancy and training** through JJMB Datascience Hub.

#### Featured projects

| Project | Result | Stack | Links |
|---|---|---|---|
| Price intelligence pipeline<br>📍 **Nigeria** | XGBoost demand forecast at 10.9% MAPE vs a 13.8% naive baseline; fine-tuned FinBERT at 76.8% vs 71.0% majority class; LP optimiser for price and stock moves. Synthetic sales data, documented as such. | Python, XGBoost, FinBERT, SciPy, Supabase, GitHub Actions | [repo](https://github.com/batestguy/tobacco-price-intelligence) · [dashboard](https://tobacco-price-intelligence.streamlit.app) |
| Crude Blend Optimizer<br>📍 **Nigeria** | ML yield surrogates (5-fold R² ≥ 0.982) drive differential evolution to within $0.005/bbl of the exact LP optimum; VaR/CVaR over 10,000 price scenarios; 140 offline tests. | Python, scikit-learn, SciPy, Docker | [repo](https://github.com/batestguy/dangote-refinery-optimizer) · [site](https://batestguy.github.io/dangote-refinery-optimizer/) |
| Bayesian World Cup | Hierarchical model of 22 World Cups with partial pooling; 50,000-run Monte Carlo tournament, counterfactual `do()` scenarios, served from precomputed posteriors. | Python, PyMC, Gradio | [repo](https://github.com/batestguy/soccer-eurovsSA) · [app](https://bayesian-world-cup-prediction.onrender.com) |
| Disability Rights Assistant (DRLCA)<br>📍 **Nigeria** | Multi-turn chatbot over Nigeria's Disability Act 2018, the 1999 Constitution and a 2020 factsheet. It quotes the law word for word with a citation on every excerpt, puts the DRAC toll-free helpline first and lists 20 browser-verified disability organisations. It works offline by default; an opt-in plain-language AI answer is checked against the excerpts it cites. Measured honestly: held-out strict recall 0.63–0.65 on two blind sets, 0 false refusals, refusal calibration 0 / 212. WCAG 2.2 AA with 0 axe issues across 33 views. English, Hausa, Igbo and Yorùbá interface. It states that no lawyer has reviewed it yet. Zero cost. | Python, TF-IDF retrieval, Streamlit, Gemini (opt-in), Playwright + axe, GitHub Actions | [repo](https://github.com/batestguy/NGOdisabilityRAG) · [app](https://ngodisabilityrag.onrender.com) · [demo video](https://github.com/batestguy/NGOdisabilityRAG/blob/main/docs/media/demo.mp4) |
| Impact Mosaic (Ayuba Gufwan disability programme)<br>📍 **Nigeria** | Independent, source-linked showcase of the programme plus a learning sandbox: 8 courses and 48 lessons, experimental Hausa, Yoruba and Igbo journeys, administrator learner maps by state and LGA, scorecards and grant-planning reports. Zero axe accessibility violations on the audited scorecard views. | React, TypeScript, Vite, Cloudflare Pages Functions, Playwright | [repo](https://github.com/batestguy/AyubaDisabilityProg) |
| Fieldmargin (crop value predictor)<br>📍 **Nigeria** | Offline-first planner that lets Nigerian farmers compare crop margins under their own land, yield, price and cost assumptions, with custom crops and bag equivalents; installs on a phone and keeps working offline. | React, TypeScript, Cloudflare Pages | [repo](https://github.com/batestguy/crop-value-predictor) · [app](https://crop-value-predictor.pages.dev/) |
| Nigeria Equity Atlas<br>📍 **Nigeria** | State-level Multidimensional Poverty Index for all 36 states and the FCT, with conflict and climate overlays and a four-round trend, from a numbered, re-runnable pipeline. | Python, Tableau | [repo](https://github.com/batestguy/NigeriaEquityAtlas-Tableau) |
| Messi vs Ronaldo, weighted | Difficulty-weighted scoring rates (FAMD weighting) with a 10,000-resample match bootstrap; intervals and effect sizes instead of significance labels. | R, Shiny, bslib, Docker | [repo](https://github.com/batestguy/messi-vs-ronaldo-r) · [dashboard](https://qqxot9-batest-hommie.shinyapps.io/messi-vs-ronaldo-r/) |
| Sol Searching<br>📍 **Nigeria** | 50 verified Kaduna businesses from a one-time OpenStreetMap import turned into a ranked solar sales pipeline with payback and risk–reward. | Python, Streamlit, OpenStreetMap | [repo](https://github.com/batestguy/kaduna-solar-lead-gen) · [demo](https://kaduna-solar-lead-ge-y3wljh2pqvkadljhlytgkg.streamlit.app) |
| Urban Agriculture, Where It Concentrates<br>📍 **Nigeria** | Spatial study of 484 OpenStreetMap cultivated-land features across 775 LGAs: Moran's I = 0.300, only 19 LGAs significant after FDR control — 13 in Kano, 6 in Lagos, none elsewhere. Density falls 66% per doubling of LGA area, and the effect strengthens (−1.001 → −1.421, ΔAIC ≈ 20) once uneven OSM mapping coverage is controlled for; a rainfall hypothesis is withdrawn rather than claimed. | R, sf, spdep, spatialreg, MASS, Quarto | [repo](https://github.com/batestguy/urban-agriculture-nigeria-spatial) · [source](https://github.com/batestguy/urban-agriculture-nigeria-spatial/blob/master/manuscript/manuscript.qmd) · [summary panel](https://raw.githubusercontent.com/batestguy/urban-agriculture-nigeria-spatial/master/docs/figures/readme/summary-panel.png) · [LISA map](https://raw.githubusercontent.com/batestguy/urban-agriculture-nigeria-spatial/master/docs/figures/readme/lisa-fdr.png) |

#### Education and honours

- 🎓 **PhD Statistics, ATBU (2026–present):** in progress; hybrid Bayesian deep learning for spatio-temporal risk forecasting
- 🥇 **MSc Statistics, ATBU (2024):** **Best in class** (top 1%)
- 🥈 **BSc Statistics, University of Maiduguri (2013):** **2nd best in class** (top 2%)
- 🏅 **MTN Foundation Scholarship (2009–2012)**, plus a place on the **Dean's List** every year from 2009 to 2012
- 📜 **Commendation letter** from ATBU's Directorate of Academic Planning (2021)
- 🏛️ **CISON / NANS** — **Registered Statistician**, member ID 20260732, joined September 2026. All three fees paid; status and membership verified on the portal.

#### More apps and tools

- [Dandali](https://github.com/batestguy/HealthMgtDashboard): maps 51,022 health facilities live from the GRID3 ArcGIS feed and falls back per feed when one is offline. Plain JavaScript and Leaflet, no build step. [Demo](https://batestguy.github.io/HealthMgtDashboard/).
- [ATBU Academic Planning Portal](https://github.com/batestguy/atbu-proflist-nuc-updates): a desktop app that manages 223 professor records and exports them in NUC format. Python, Flet and SQLite.

#### Research

7 peer-reviewed papers in health and applied statistics, 5 citations.

[Google Scholar](https://scholar.google.com/citations?user=oKaejtMAAAAJ) · [ORCID](https://orcid.org/0009-0002-3302-9558)

**Research pipelines**, each reproducible from raw data to manuscript tables and figures:
- [Bayesian change-points in Nigerian rainfall](https://github.com/batestguy/Bayesian-Change-Point-Detection-in-Nigerian-Rainfall-Patterns-A-Hierarchical-Analysis-Climate-Zones): a hierarchical model of 74 years of rainfall at 9 stations in 3 climate zones; LOO cross-validation rejects the no-change model in every zone. Python and PyMC; manuscript in preparation.
- [Avian influenza in Nigeria, systematic review](https://github.com/batestguy/avian-influenza-nigeria-systematic-review): PRISMA 2020 screening of 2,157 records from six databases down to 113 included studies.
- [Anti-trypanosomal plant extracts](https://github.com/batestguy/comparative-anti-trypanosomal-activity-azadirachta-indica-moringa-oleifera): parses a messy Excel workbook into tidy data and runs block-level non-parametric tests with Holm adjustment through to a Word report. R and Quarto.
- [Non-O157 *E. coli* in fermented milk](https://github.com/batestguy/nono-analysis): prevalence with 95% CIs, ANOVA and antibiotic-susceptibility profiles for 200 isolates.
- [Urban agriculture in Nigerian cities, spatial analysis](https://github.com/batestguy/urban-agriculture-nigeria-spatial): where cultivated land concentrates across 775 Nigerian LGAs, with an explicit correction for uneven OpenStreetMap coverage — Moran's I = 0.300, the area effect surviving the coverage control (ΔAIC = 20). Spatial statistics on API-sourced data, frozen to CSV, 175 automated claim checks. Listed under [featured projects](#featured-projects) above; manuscript in preparation for *TeMA — Journal of Land Use, Mobility and Environment*.

#### Toolbox

- **Languages:** Python, R, SQL, TypeScript/JavaScript
- **Statistics and ML:** PyMC, scikit-learn, XGBoost, TensorFlow/Keras, SciPy optimisation, survival, spatial and time-series models
- **Apps and reporting:** Streamlit, R Shiny, Gradio, React, Quarto, Tableau, Power BI
- **Engineering:** Git, GitHub Actions, Docker, Supabase, Cloudflare Pages, Render

#### Off the clock

♟️ Chess, peak 2000+: [Chess.com rapid](https://www.chess.com/member/BayesianRules) and [Lichess blitz](https://lichess.org/@/BayesianRules), as **BayesianRules**.

#### Contact

[batesthommie@gmail.com](mailto:batesthommie@gmail.com) · [Blog](https://batestguy.github.io/QuartoWebsite-blog-others/)
