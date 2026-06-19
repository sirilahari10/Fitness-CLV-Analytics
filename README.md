# The One-Slide Strategy: Optimizing Boutique Fitness CLV

*(Built as a PoW for the BI Analyst II role at Purpose Brands)*

I saw your recent post sharing the HBR "One-Slide Strategy" article. It’s a great philosophy. Dashboards are useless if they don't drive a business decision. 

Coming from a background in AI/ML and applied statistics, I wanted to demonstrate how I approach the "simple deterministic models" mentioned in the Purpose Brands job description, specifically focusing on **Customer Lifetime Value (CLV)** and **Experimentation**.

### 1. The Business Problem (Churn & Break-Even)
Boutique fitness thrives on utilization. If a member stops booking classes, they will cancel within 60 days. The goal of a BI Analyst isn't just to report the churn—it's to identify the break-even point and flag the leading indicators *before* the cancellation happens.

### 2. The Deterministic Model
Using simulated studio data (2,000 members), I built a logical model to calculate unit economics:
* **Customer Acquisition Cost (CAC):** $150
* **Studio Margin:** 35% on a $169 unlimited membership.
* **Break-Even Point:** 2.5 Months. Any member who churns before month 3 is a net loss to the studio.

### 3. The Loyalty Insight (The dunnhumby approach)
I analyzed behavioral indicators and found a massive loyalty hook: **Wearable Tech**. Members who purchase the proprietary heart-rate monitor stay active significantly longer. 

### 4. The Experimentation Action Plan
**The Target:** Identified 184 active members who passed the break-even point but have dropped below 4 classes/month (High Churn Risk).
**The Action:** Launch an A/B test (Experimentation) pushing a "burnout recovery" promo to this exact segment via the studio app to re-engage them before billing hits.

*Python code replicating SQL/BI logic is attached in the repository.*
