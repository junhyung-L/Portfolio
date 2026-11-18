# Junhyung Lee | Data Science & AI Portfolio

[한국어](README.ko.md)

I build prediction models and decision simulations from customer, policy, and spatial data. Each repository states the data, the evaluation setting, and what a result does and does not show.

Currently an intern in the BigData&AI Cell at Hana Financial Convergence Technology Institute (Jul 2026–). Undergraduate researcher at DIVE Lab, Incheon National University (Feb 2025–Feb 2026), where I wrote the first-author CRM paper below; a follow-up causal-inference study on marketing fatigue is in progress.

## Selected work

Selected work leads with the paper and the awarded projects; for modeling depth, see the CTR and credit-card repositories in the archive below.

### Purchase Conversion Prediction with Dynamic Marketing Knowledge

First-author paper, *마케팅연구* (Korean Marketing Association), forthcoming November 2026. [crm-conversion-prediction](https://github.com/junhyung-L/crm-conversion-prediction)

On 172 million REES46 CRM messages with a 0.1234% conversion rate, I turned marketing theory into four groups of time-varying features (purchase cycle, temporal response, fatigue, channel effectiveness) and compared nine models. XGBoost with these features had the best F1 (0.3806) and PR-AUC (0.3620) on the original-distribution holdout. Contacting the top 0.78% of messages captured 95.83% of conversions at 15.26% precision (123.7x lift).

### Forestry Crop Suitability and Yield Analysis

2024 Forestry Statistics Smart Use Competition · Grand Prize (Korea Forest Service Commissioner Award) · 13 Dec 2024. [forestry-crop-suitability](https://github.com/junhyung-L/forestry-crop-suitability)

Links GIS soil layers, climate, and production data for seven forest crops, screens variables statistically, and picks a model per crop; the output is a suitability analysis and a map-based service concept for new forest farmers.

### Incheon e-Eum Cashback Policy Simulation

2025 Incheon National University Industry-Academic Capstone Design Competition · Gold Prize · 1 Jul 2025. Team lead of a four-person team. [incheon-eeum-policy-simulation](https://github.com/junhyung-L/incheon-eeum-policy-simulation)

Forecasts district spending with LightGBM under 5% and 10% cashback conditions, then ranks 66 two-month cashback schedules within a KRW 200 billion budget by spending generated and budget left. It is a scenario comparison, not a causal estimate of the policy.

### Dong-Incheon Marketing Pilot

2025 PBL Program · Grand Prize (Incheon Metropolitan City Mayor's Award) · 27 Feb 2026. [dongincheon-marketing-pilot](https://github.com/junhyung-L/dongincheon-marketing-pilot)

In the Marketing & Data Analysis role, I turned vacancy data and merchant interviews into action items for Madam Tea, a store in the old downtown, then ran Naver Place, Instagram, and short-form content for a 30-day pilot.

## Project archive

| Area | Project | Summary |
|---|---|---|
| CRM research | [Purchase Conversion Prediction with Dynamic Marketing Knowledge](https://github.com/junhyung-L/crm-conversion-prediction) | First-author paper: theory-based features across nine models |
| Recommender / ads | [CTR Prediction with DCN-V2 and Behavior-Sequence Encoders](https://github.com/junhyung-L/ctr-sequence-modeling) | DCN-V2 with DIN, DIEN, and BST sequence encoders |
| Customer analytics | [Credit-Card Customer Segment Classification](https://github.com/junhyung-L/credit-card-customer-segmentation) | Missingness-aware classification over 857 columns |
| Pricing | [Used-EV Price Prediction](https://github.com/junhyung-L/used-ev-price-forecasting) | Battery-capacity imputation and XGBoost price regression |
| Policy simulation | [Incheon e-Eum Cashback Policy Simulation](https://github.com/junhyung-L/incheon-eeum-policy-simulation) | 66 budget-constrained cashback schedules |
| Demand simulation | [Cold-Start Demand Simulation for New Products](https://github.com/junhyung-L/cold-start-demand-simulation) | Persona-based Monte Carlo for 15 new food products |
| GIS & forestry | [Forestry Crop Suitability and Yield Analysis](https://github.com/junhyung-L/forestry-crop-suitability) | Per-crop suitability and yield models |
| Spatial safety | [Fallin: GIS Fall-Risk Map for Older Pedestrians](https://github.com/junhyung-L/fallin-gis-risk-mapping) | Rule-based pedestrian fall-risk map prototype |
| Field marketing | [Dong-Incheon Marketing Pilot](https://github.com/junhyung-L/dongincheon-marketing-pilot) | Field research and a 30-day store pilot |
| LLM application | [Job Simulator AI](https://github.com/junhyung-L/ai-interview-simulator) | Next.js roleplay practice with structured feedback |
| Coursework | [Student Depression Survey](https://github.com/junhyung-L/student-depression-risk-analysis) | Interpretable logistic regression on survey data |

Each repository has a README (method and results) and a case study (`PORTFOLIO.md`: decisions, trade-offs, limits). Numbers come from different settings (holdout, validation, leaderboard, simulation, field pilot); each README names its own.

Award certificates are available on request.

---

[Resume](https://github.com/junhyung-L/Resume/blob/main/README.en.md) · [GitHub](https://github.com/junhyung-L) · [LinkedIn](https://www.linkedin.com/in/junhyung-lee-data) · [Email](mailto:jun010914@inu.ac.kr)
