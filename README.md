# Awesome-Sales-Pipeline-Forecasting-Win-Rate-Analyzers

# Top Sales Pipeline Forecasting & Win-Rate Analyzers Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Revenue Forecasting, Deal Risk Scoring & Conversation Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Sales Pipeline Forecasting & Win-Rate Analysis**. These tools analyze CRM data, sales transcripts, and buyer signals to predict which deals will close, forecast revenue accurately, and surface the risks hiding in your pipeline — turning gut-feel forecasting into data-driven revenue intelligence.

**Examples** include Clari, Gong, Revenue.io, Aviso, InsightSquared, BoostUp, Troops, Atrium, Mediafly, and Klue (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom win-rate modeling, and transparent pipeline analytics — ideal for revenue operations teams prioritizing data sovereignty, developers building forecasting pipelines, and organizations avoiding per-seat AI pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Clari](https://www.clari.com/)**  
  Revenue operations platform with AI-powered forecasting, pipeline inspection, and deal risk detection. Provides revenue leak analysis and forecast accuracy improvements for enterprise sales teams.

- **[Gong](https://www.gong.io/)**  
  Revenue intelligence platform that analyzes sales conversations (calls, emails, meetings) to predict deal outcomes, forecast revenue, and coach reps. Features deal boards, win-loss analysis, and forecast roll-ups based on actual buyer signals.

- **[Revenue.io](https://www.revenue.io/)**  
  Revenue operations and conversation intelligence platform with AI-guided selling, real-time coaching, and pipeline analytics.

- **[Aviso](https://www.aviso.com/)**  
  AI-driven sales forecasting and pipeline management platform with predictive analytics, deal risk assessment, and what-if scenario modeling.

- **[InsightSquared](https://www.insightsquared.com/)**  
  Revenue intelligence and forecasting platform with pipeline analytics, win-rate analysis, and sales performance dashboards.

- **[BoostUp](https://www.boostup.ai/)**  
  Revenue operations and intelligence platform with forecasting, pipeline analytics, deal risk prediction, and buyer sentiment analysis.

- **[Troops](https://www.troops.ai/)**  
  Revenue operations platform delivering pipeline insights and deal alerts directly into Slack, with CRM automation.

- **[Atrium](https://www.atriumhq.com/)**  
  Sales management and forecasting platform with AI-powered pipeline inspection, deal scoring, and coaching recommendations.

- **[Mediafly](https://www.mediafly.com/)**  
  Revenue enablement platform with conversation intelligence, content management, and deal analytics.

- **[Klue](https://klue.com/)**  
  Competitive intelligence platform with win-loss analysis, battlecards, and revenue impact tracking.

## Open-Source GitHub Projects

- **[b2b-revenue-forecasting](https://pypi.org/project/b2b-revenue-forecasting/)**  
  Python library for B2B revenue forecasting with **hierarchical quota cascading**, metric weighting via Pearson correlation, and brand-new IC detection. Features **CommitReconciler** for detecting and fixing forecasting bias (sandbagging/over-committing) with ML baseline blending. Exports to CSV, SQL, or interactive Chart.js HTML dashboards. Any numeric metric works — boolean and 0/1 sparse metrics auto-detected and excluded from zero-imputation.

- **[CRMlytics](https://wordpress.org/plugins/crmlytics/)**  
  Open-source WooCommerce CRM combining machine learning, customer management, and email campaigns. Runs models on order history to calculate customer health scores (0-100), identify churn risk, predict future orders (30/90/180 days), and compute RFM scores automatically. Everything runs locally — no external APIs, no monthly fees for number crunching.

- **[AI-Driven CRM Analytics System](https://github.com/Isha2605/AI-Driven-CRM-Analytics-System)**  
  Full-stack AI-powered CRM with sales tracking, event management, employee performance prediction, rewards, PyTorch chatbot, and lead-classification ML. Achieves **82% accuracy on lead scoring** across 10,000+ customer records using KNN + Feedforward Neural Network. Built with Flask, MySQL, PyTorch, and scikit-learn. Includes conversational assistant for natural-language CRM queries. MIT licensed.

- **[CallSense](https://github.com/aaron-seq/ML-voice-lead-analysis)**  
  Self-hosted conversation intelligence turning recorded sales calls into qualified leads with explainable scores. Features **0-100 lead scoring with every weighted component shown** and transcript quote behind each one, 7 objection types flagged as addressed/unaddressed, 10 buyer intent signals mapped to BANT/MEDDIC, call outcome classification, next-best-action generation, and deal risk flags (no decision maker, no next step, budget unconfirmed, rep monologue). Runs on your infrastructure, no per-seat cost, no data leaving your network. Python 3.11+, no GPU required.

- **[ChurnGuard AI](https://github.com/ShreyasDasari/churnguard-ai)**  
  Free, open-source churn prediction for SaaS. Plug in customer data via universal CSV schema and know who's leaving before they do. Features XGBoost primary model with LightGBM alternative, SMOTEENN resampling, PR-AUC evaluation, customer risk scoring with Critical/High/Medium/Low tiers, and revenue-weighted priority ranking. Outputs projected retention value. Supports Stripe, PostHog, HubSpot, and CSV imports.

- **[lead-scoring-ai-mcp](https://www.npmjs.com/package/lead-scoring-ai-mcp)**  
  B2B lead scoring with engagement tracking and prioritization. Features `score_lead` based on firmographic data (company size, budget, engagement, decision maker contact, email verification, website traffic), `add_lead` tracking, `update_lead_activity` for email_open/click/demo_request/meeting_booked, `predict_conversion` probability, and `track_engagement_trend`. Free tier: 15 calls/day. MIT licensed.

- **[SalesIQ](https://github.com/badrr06/SalesIq)**  
  Modular Flask app for sales management and forecasting. Features CRUD for products, customers, and sales; dashboard with KPIs; monthly sales + 6-month forecast (ARIMA/SARIMAX or Linear Regression fallback); top products analysis; CSV export; MySQL or SQLite via SQLAlchemy; Bootstrap UI with Chart.js. Simple deployment for small businesses.

- **[afrikana-analytics](https://pypi.org/project/afrikana-analytics/)**  
  Production-ready analytics toolkit covering churn prediction, customer lifetime value, financial modeling, site deployment optimization, and demand forecasting. Built from real analytical work across African markets. ChurnScorer uses Gradient Boosting for subscription/usage-based businesses. LTVCalculator provides discounted survival-adjusted CLV with Bronze/Silver/Gold tiers. Includes Monte Carlo simulation for NPV probability and break-even analysis.

- **[Horilla CRM](https://github.com/horilla/horilla-crm)**  
  Free and open-source CRM under LGPL-2.1+. Features role-based access control, REST API with Swagger documentation, webhooks, CSV/Excel import/export, internationalization (20+ languages), and Docker Compose deployment. Enterprise-grade security with CSRF protection, SQL injection protection, and API rate limiting.

### Additional Strong Open-Source Options

- **[GitHub Topic: sales-forecasting](https://github.com/topics/sales-forecasting)** — 30+ public repositories covering sales prediction models, pipeline analytics, and revenue forecasting notebooks.
- **[GitHub Topic: win-rate-analysis](https://github.com/topics/win-rate)** — Community projects analyzing deal outcomes, competitive win rates, and sales performance metrics.
- **[GitHub Topic: conversation-intelligence](https://github.com/topics/conversation-intelligence)** — Open-source transcript analysis, sentiment detection, and sales call scoring tools.
- **Pipeline Analytics Libraries** — pandas-based pipeline inspection, cohort conversion analysis, and stage duration benchmarking.
- **Forecasting Models** — Prophet, ARIMA, and hierarchical time series libraries for revenue prediction.

**Frameworks for building custom systems**: Combine **b2b-revenue-forecasting** for quota and forecast reconciliation, **CallSense** for conversation intelligence and deal risk scoring, **ChurnGuard AI** for retention prediction, **CRMlytics** for customer health and RFM scoring, and **AI-Driven CRM Analytics** for lead classification to build a complete self-hosted sales pipeline intelligence stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Sales forecasting and pipeline analytics tools must comply with data protection regulations (GDPR, CCPA), call recording consent laws, and CRM data governance requirements.
- Self-hosted open-source solutions require proper security hardening, model monitoring, and CRM integration validation.

---

**Made for revenue operations teams, sales leaders, sales operations analysts, and developers building revenue intelligence platforms.**  
Let's make sales pipeline forecasting more open, accurate, and data-sovereign.
