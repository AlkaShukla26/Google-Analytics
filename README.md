<p align="center">
  <img 
    src="https://github.com/AlkaShukla26/Google-Analytics/blob/main/ChatGPT%20Image%20Sep%2010%2C%202025%2C%2001_52_12%20PM.png" 
    alt="Google Analytics Project Cover" 
    width="567" 
    height="265"
  />
</p>

# Google Analytics E-commerce Analysis

This project analyzes the *Google Merchandise Store* dataset (sample GA4 e-commerce dataset available in BigQuery Public Datasets) to uncover user behavior, conversion patterns, and business insights.  
The analysis is SQL-driven and focuses on the e-commerce funnel, user engagement, and product performance.

---

## 📊 Dataset

- *Source*: bigquery-public-data.ga4_obfuscated_sample_ecommerce  
- *Period Covered*: Nov 1, 2020 – Jan 31, 2021  
- *Scope*: 4.29M events, 270K+ users, 92 days

---

## 🔎 Key Analyses Performed

1. *Overall Engagement*  
   - Total events, unique users, and unique active days.

2. *Conversion Funnel*  
   - Tracked drop-offs from view item → add to cart → checkout → purchase.

3. *Top Products*  
   - Identified most popular items added to cart by unique users.

4. *Purchaser Behavior*  
   - Compared average pageviews between purchasers and non-purchasers.

5. *Transactions*  
   - Analyzed average number of transactions per purchaser.

6. *New vs Returning Users*  
   - Measured user acquisition and retention.

---

## 📌 Key Insights

- *High Drop-off in Funnel*: Only 1.6% of users who viewed items ended up purchasing.  
- *Top Demand in Apparel*: Products like cotton caps, tees, and hoodies dominate cart additions.  
- *Purchasers Browse More*: Buyers average 51 pageviews vs. just 4 by non-purchasers.  
- *Low Repeat Purchases*: Average 1.29 transactions per customer — mostly one-time buyers.  
- *Heavy Acquisition, Weak Retention*: ~90% of Nov users were new, indicating poor repeat engagement.

---

## 💡 Recommendations

1. *Funnel Optimization*  
   - Simplify checkout, add cart reminders, and offer incentives (e.g., free shipping).

2. *Retention Strategy*  
   - Introduce loyalty programs and re-engagement campaigns for one-time buyers.

3. *Product Marketing Focus*  
   - Prioritize top apparel items in promotions and bundle offers to raise order values.

4. *Personalization & Targeting*  
   - Use browsing data for personalized recommendations and dynamic retargeting ads.

---

## 🛠️ Tech Stack

- *SQL*: BigQuery  
- *Google Analytics GA4 Dataset*  
- *Documentation & Visualization*: Markdown, Charts (planned for funnel, top products, retention)
