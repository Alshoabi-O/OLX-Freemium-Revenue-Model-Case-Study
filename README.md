# OLX Freemium Revenue Model – Case Study

## 1. Background
By early 2019, OLX Egypt’s **Value-Added Services (VAS)** — paid tools that boosted ad visibility — were losing their edge. Premium listing adoption plateaued, and new competitors like **Facebook Marketplace** were gaining traction.  

I was tasked as **Business Strategy Analyst** with identifying and validating a new monetization model that would:
- Protect revenue growth targets for 2020.
- Maintain (or grow) market share.
- Avoid driving away key customer segments.

We decided to explore a **Freemium Model**: offering limited free ad postings, with fees for additional listings.

---

## 2. Problem Analysis
The shift wasn’t as simple as “allow X free ads per month.”  
We first had to address **three core issues**:

### a. Fraud & Duplication
- Sellers could post **hundreds of duplicate ads** to dominate search results.
- Loophole allowed **free “bump-ups”** by re-posting expired or deactivated ads, bypassing VAS fees.
- Fraud inflated free ad volume and reduced the value of paid listings.

### b. Distorted Metrics
- No **Net Ads KPI** existed to filter out duplicates and fraud.
- Market share and performance analytics were unreliable.
- Competitor tracking suffered due to dirty data.

### c. Customer Churn Risk
- Monetizing all ads risked losing casual sellers (C2C) to free competitors.
- Needed to differentiate between **high-value business users** and **occasional sellers**.

---

## 3. Approach
I designed a **multi-phase analytical and strategic plan**:

### Step 1 – Deep Data Investigation
- Queried OLX’s ad database using **SQL (DataGrip IDE)**.
- Performed **user journey testing** to map how listers interacted with the platform.
- Identified specific behaviours that exploited platform loopholes.

### Step 2 – Customer Segmentation
Created **4 distinct lister segments**:
1. **C2C** (Consumer-to-Consumer)
2. **Small B2C**
3. **Medium B2C**
4. **Large B2C**

Segmentation was based on:
- Number of ads posted.
- Product categories.
- Engagement with VAS.
- Duplication/fraud patterns.

### Step 3 – Net Listings KPI
- Defined as *unique listings after removing duplicates/fraud*.
- Calculated by grouping by seller ID, location, and product, ignoring changes in title/wording used to bypass filters.
- Enabled **true measurement** of inventory health and paid/free ad performance.

### Step 4 – Policy Simulation
- Modelled multiple “free ad limit” scenarios per segment.
- Simulated churn rates and competitor impact.
- Recommended **C2C remain free** (up to 5 ads/month) to avoid market share loss.
- Introduced **tiered ad credits** and **pricing packages** for business segments.

---

## 4. Implementation
- Worked with **Head of Strategy** and **General Manager** to finalise pricing structure.
- Collaborated with **global product teams** to patch loopholes (e.g., free bump-up behaviour).
- Built financial projection models for multiple adoption/churn scenarios.
- Prepared competitor forecast with Facebook Marketplace factored in.

---

## 5. Results
- **+35% Revenue Growth** in post-launch period.
- **+70% Increase** in paid ad replies and leads.
- **+20% Increase** in free ads (healthy, non-duplicate inventory).
- Improved **days-to-first-reply**:  
  - Ads received first 3 replies **faster** (within 3–7 days).
- Market share analysis became **accurate for the first time**, enabling better competitive positioning.

---

## 6. Lessons Learned
1. **Policy & Data Must Evolve Together** – Without fixing fraud/duplication, freemium revenue would have been undermined.
2. **Segmentation Protects Core Users** – Keeping C2C fully free retained engagement while still monetizing high-value segments.
3. **Cross-Team Collaboration is Key** – Product, strategy, and analytics had to work together to close loopholes and implement changes.

---

## 7. Skills Demonstrated
- Advanced SQL data investigation.
- KPI design and metric governance.
- Customer segmentation and market modelling.
- Policy simulation and financial forecasting.
- Strategic collaboration with C-level and global product teams.

---

## Disclaimer
All data has been anonymised and simplified for portfolio purposes.  
Figures and examples are representative of real outcomes.
