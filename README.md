# Financial Advisory Subscription & Retention Performance

## Project Overview
This repository contains an executive-level data analysis and presentation framework investigating customer attrition (churn), subscription tier lifetime value (LTV), and support operations performance for a digital financial advisory subscription service. 

The analysis is based on a representative sample of **50,000 customer subscription records** covering digital newsletters, webinars, and expert investment recommendations.

---

## Key Business Questions Addressed
1. **What drives customer churn across different subscription varieties?** (Comparing annual commitments vs. digital monthly plans).
2. **Does customer support interaction volume signal severe product friction?** (Testing support ticket thresholds against cancellation behavior).
3. **How do demographic cohorts influence long-term retention?** 

---

## Key Findings Summary
* **Annual Plans Drive Higher LTV:** Annual subscriptions (`prd_1`) yield significantly longer retention periods and higher cumulative revenue compared to digital/monthly plans (`prd_2`).
* **Support Friction is Moderate (Hypothesis Refuted):** Contrary to the initial assumption that 3+ support tickets would drive a 40%+ surge in churn, data reveals only a mild increase (**25.07% vs. 22.06%**), demonstrating that daytime care team interventions successfully rescue engaged users.
* **Support Demands:** Over 60% of support cases focus on billing and account inquiries handled via email and web chat.
* **Demographic Risk:** Subscribers aged 18–30 exhibit higher cancellation rates, highlighting the need for targeted beginner-focused engagement.

---

## Repository Structure
* `/data` - Sampled dataset (50,000 records) and data dictionary.
* `/scripts` - Python data processing, Exploratory Data Analysis (EDA), and hypothesis testing scripts (including Hypothesis 2 evaluation).
* `/presentation` - 7-slide executive PowerPoint outline and dashboard documentation.
* `METHODOLOGY.md` - Detailed breakdown of analytical frameworks and metrics.

---

## Tech Stack & Tools
* **Data Analysis:** Python (Pandas, NumPy)
* **Visualization & BI:** Looker Studio Dashboard
* **Presentation:** PowerPoint
