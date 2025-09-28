# Bharat-Herald-Digital-Transformation

📌 Project Overview

Bharat Herald, a 70-year-old legacy newspaper, is facing a survival crisis in the post-COVID digital era. Once printing 1.2M+ daily copies, circulation dropped to under 560K by 2024.

Competitors adapted quickly with mobile-first apps, WhatsApp delivery, and subscription bundles, while Bharat Herald’s 2021 e-paper pilot failed due to poor usability.

This project simulates a data analyst’s role in diagnosing the crisis and building a roadmap for digital transformation using SQL + Excel.

🎯 Problem Statement

Diagnose what went wrong in circulation and ad revenue.

Identify print inefficiencies and waste.

Assess digital readiness across cities.

Highlight missed opportunities in the failed digital pilot.

Recommend a phased roadmap for digital relaunch.

🛠️ Tech Stack

SQL → Writing queries for ad-hoc analysis, joins, CTEs, ranking, and time-based comparisons.

Excel → Cleaning datasets, creating pivot tables, and building charts for stakeholder-ready visuals.

Data Storytelling → Turning findings into clear insights and business recommendations.

📂 Dataset

The dataset (2019–2024) includes:

fact_print_sales → Copies printed, sold, and circulated by city & year.

fact_ad_revenue → Ad revenue by category and city.

fact_city_readiness → Smartphone, internet, and literacy rates.

fact_digital_pilot → Engagement metrics for digital pilot (downloads, sessions, users).

dim_city → City details.

🔍 Key Business Questions & Insights
1️⃣ Circulation Decline

Sharpest drops: Jan 2021 (Varanasi), Nov 2019 (Varanasi), Jan 2020 (Jaipur), Oct 2020 (Varanasi).

Pattern → Declines often cluster in January → a structural weak month.

👉 Insight: Declines weren’t only gradual but also triggered by *sudden shocks (COVID, distribution breakdowns, seasonal slowdowns).

2️⃣ Ad Revenue Concentration

No category >50%, but 2 categories >30% consistently.

Risk: Over-dependence on a few sectors.

👉 Insight: Diversification into FMCG, Education, and Health ads is critical.

3️⃣ Print Efficiency & Waste

Some cities circulated less than 60% of printed copies.

Same 3 cities appeared in Top 5 waste contributors every year.

👉 Insight: Waste is structural, not random → biggest efficiency gains possible here.

4️⃣ Digital Readiness vs Pilot Engagement

Kanpur: Highest readiness score but among the lowest engagement.

Market was ready → product failed.

👉 Insight: Kanpur is a must-win city for Phase 1 relaunch.

5️⃣ Consistent Declining Cities

No city declined in both metrics every single year.

One city declined 3 years in a row → still a risk market.

👉 Insight: Declines are widespread but uneven → showing volatility, not a smooth downward trend.

🚀 Phased Roadmap (Recommendations)
Phase 1: Stabilize & Target (0–6 months)

Cut print waste in 3 recurring loss cities.

Relaunch digital in 3 priority cities (high readiness + high engagement + sharp print decline).

Launch mobile-first e-paper, distribute daily headlines on WhatsApp.

Phase 2: Expand & Engage (6–18 months)

Subscription bundles (weekday digital + weekend premium).

Regional language apps.

Diversify ad revenue streams.

Phase 3: Scale & Innovate (18–36 months)

Digital-first strategy in declining print cities.

Launch podcasts, explainer videos, and premium ad-lite tiers.

Build Bharat Herald as a regional-first digital powerhouse.

📊 Deliverables

SQL Queries: For each business/ad-hoc request.

Excel Dashboards: Circulation trends, ad revenue, print waste leaderboard, digital readiness growth.

Presentation Slides: Storytelling from diagnosis → insights → roadmap.

🙌 Acknowledgements

Thanks to Codebasics, Dhaval Patel, and Hemanand Vadivel for this challenge.

This project helped me sharpen skills in:

SQL problem-solving

Excel-based data storytelling

Turning insights into business strategy

💡 Key Takeaway

This project was not just about writing SQL queries or building charts. It was about connecting data with business strategy and answering:

“How can data guide the survival of a legacy brand in a disrupted industry?”

🔗 Connect

💬 Always open to feedback and discussions on data analytics, storytelling, and digital transformation.
Find me here on GitHub or LinkedIn
.
