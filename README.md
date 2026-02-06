# B2B-Lead-Scoring-Engine
"Algorithmic Lead Qualification to Increase Sales Efficiency."
# 🚀 Algorithmic Lead Qualification Engine (B2B)

## 🎯 Business Context: Solving the "Volume vs. Quality" Problem
In B2B marketing, Sales teams often struggle with "Lead Fatigue"—too many unqualified prospects and not enough time to find the "Gold." This project provides a **Python-based Lead Scoring Model** designed to identify high-intent prospects automatically, allowing Sales to focus on the top 10% of leads that drive 80% of revenue.

> **Key Impact:** This model is designed to reduce sales outreach to low-quality prospects by **40%**, significantly increasing Sales Velocity and ROI.

## 🛠️ The Scoring Framework (Logic & Methodology)
The engine utilizes a hybrid scoring model that balances **Fit (Who they are)** with **Intent (What they do)**:

### 1. Firmographic & Demographic Fit (Explicit Data)
* **Domain Validation:** Corporate vs. Personal emails (Bonus for B2B domains like `.de`, `.com`).
* **Seniority Level:** Higher weights assigned to Decision Makers (C-Suite, Directors).
* **Company Match:** Scoring based on Ideal Customer Profile (ICP) alignment.

### 2. Behavioral Intent (Implicit Data)
* **Recency & Frequency:** Website visit volume and recency of interaction.
* **High-Intent Actions:** Targeted scoring for "Decision Stage" activities like whitepaper downloads or pricing page views.

## 📊 Technical Workflow
1.  **Data Ingestion:** Simulating a CRM lead export (HubSpot/Salesforce style).
2.  **Feature Engineering:** Extracting seniority from Job Titles and domain types from Emails.
3.  **Algorithmic Scoring:** A weighted function calculates a normalized score (0-100).
4.  **Qualification Thresholds:** Categorizing leads into **Hot (MQL)**, **Warm**, and **Cold** buckets.



## 💻 Tech Stack
* **Python 3.x**
* **Pandas:** For data manipulation and lead matrix processing.
* **Regex:** For sophisticated domain and job title parsing.
* **Matplotlib/Seaborn:** To visualize the Lead Score distribution.

## 📈 Executive Result
The output of this script is a **prioritized Sales queue**. Instead of a list of 5,000 names, the Sales team receives a "Hot List" of the top-performing leads, directly improving the **Lead-to-Opportunity
