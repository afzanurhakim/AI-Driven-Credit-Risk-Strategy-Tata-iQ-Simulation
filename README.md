# AI-Driven Credit Risk Strategy | Tata iQ Simulation

Objective: Transforming Geldium Finance from reactive debt collection to a proactive "Financial Wellness" framework using Machine Learning and Agentic AI.

## Project Overview

In this job simulation, I acted as an AI Transformation Consultant to address high delinquency rates at Geldium Finance. The goal was to design an "Early Warning System" that identifies at-risk customers before they default, moving away from traditional collection methods.

## Technical Approach & Methodology

Although this repository focuses on the strategic framework, the methodology is grounded in advanced data science principles:

Feature Engineering: Focused on "Trended Data" (Utilization Velocity and DTI Pressure) rather than static snapshots.

Exploratory Data Analysis (EDA): Audited customer datasets to identify key risk triggers, specifically finding that Credit Utilization > 80% and DTI ratios > 30% are primary predictors of delinquency.

Model Logic: Designed a Random Forest Classifier framework to handle non-linear relationships in financial behavior.

Agentic Framework: A Hybrid Intelligence system that uses GenAI (SQL RAG & Vector RAG) as a translation layer between raw data insights and stakeholder-ready strategy.

## Dismantling the "Black Box" (Explainable AI)
In the financial sector, "Black Box" models are a regulatory liability. This project prioritizes **Model Interpretability** over mere accuracy.

* **Beyond Opaque Predictions:** Instead of uninterpretable outputs, I integrated **SHapley Additive exPlanations (SHAP)** logic. This ensures every flagged account comes with a "Feature Importance" audit (e.g., *“Account flagged due to a 25% spike in Credit Utilization + DTI > 30%”*).
* **The "Hidden Risk" Discovery:** By analyzing behavioral trends, the system identified **89 customers** who are currently "on-time" but possess high-probability risk markers—allowing for intervention *before* the first missed payment.


## Key Business Insights

The "Hidden Risk" Segment: Identified a specific cohort of 89 customers with low credit scores who are currently on-time but show behavioral patterns signaling imminent default within 30-60 days.

Strategic Pivot: Proposed shifting the collections narrative from "Debt Recovery" to "Financial Wellness," offering restructured payment plans to high-risk customers to preserve capital and customer loyalty hence increasing the customer LTV (Lifetime Value).

Ethical Guardrails: Impelementation of a "Human-in-the-Loop" protocol to prevent algorithmic bias and ensure compliance with Fair Lending standards.

## Deliverables

[EDA Summary Report](https://github.com/afzanurhakim/AI-Driven-Credit-Risk-Strategy-Tata-iQ-Simulation/blob/main/Documentation/EDA_SummaryReport.pdf)

[Predictive Model Plan](https://github.com/afzanurhakim/AI-Driven-Credit-Risk-Strategy-Tata-iQ-Simulation/blob/main/Documentation/Task%202_ModelPlan.pdf)

[Business Summary Report](https://github.com/afzanurhakim/AI-Driven-Credit-Risk-Strategy-Tata-iQ-Simulation/blob/main/Documentation/Updated_Business_Summary_Report.pdf)

[Final Business Presentation](https://github.com/afzanurhakim/AI-Driven-Credit-Risk-Strategy-Tata-iQ-Simulation/blob/main/Presentation/Presentation.pdf)

