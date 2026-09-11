# Zomato Bangalore Data Analysis & Growth Playbook

**VirtuBox Data Analyst Assessment | Response Document**

---

### Candidate & Assessment Details
* **Candidate Name:** Ansh Agarwal
* **University:** Meerut Institute of Technology, Meerut
* **Contact:** 9258687121
* **Degree / Program:** B.Tech in Computer Science and Engineering (Data Science)
* **Assessment Role:** Data Analyst Assessment Test
* **Company:** VirtuBox Infotech Private Limited
* **Dataset:** Zomato Bangalore Restaurant Dataset (~51k raw records → 12,518 unique outlets)
* **Interactive Dashboard:** [Looker Studio Live Dashboard](https://lookerstudio.google.com/reporting/e063bac4-01f1-4247-86d6-bc766fa17123)

---

## Executive Summary
This project analyzes the Zomato Bangalore restaurant ecosystem to uncover drivers of customer ratings, vote engagement, and micro-market demand density. Using Python (Pandas & NumPy) in Google Colab, raw unstructured data was cleaned, feature-engineered, and deduplicated down to 12,518 unique physical restaurant outlets to inform platform growth strategies for VirtuBox management.

---

## Key Analytical Insights
1. **Online Delivery Lift:** Outlets offering online delivery capture **3.5x higher vote volume** and achieve superior average customer satisfaction scores compared to offline-only outlets.
2. **Price Tier Sweet Spot:** Mid-tier outlets (**₹300 – ₹700**) achieve the highest satisfaction rating (**3.95 / 5**), driving >60% of all positive platform reviews ($\ge 4.0$).
3. **High-Demand Micro-Markets:** Indiranagar and Koramangala dominate customer engagement, generating over **35% of total platform vote volume**.

---

## Strategic Recommendations
* **Merchant Onboarding:** Target top-rated offline outlets in high-density hubs (Koramangala, Indiranagar) with 30-day zero-commission trial campaigns.
* **App Feed Optimization:** Feature high-converting mid-tier meal combos on the app home screen to optimize checkout conversion.
* **Supply Expansion:** Share demand-density analytics with cloud kitchen networks to open fulfillment units in top demand clusters.

---

## Project Repository Structure
```text
zomato-bangalore-data-analysis/
├── README.md                                          # Primary documentation & submission metadata
├── Processed_Zomato_Data_Clean.csv                    # Final deduplicated dataset (12,518 records)
├── Zomato_Analysis_Notebook.ipynb                     # Jupyter Notebook (Data cleaning, feature engineering & EDA)
├── Zomato-Bangalore-Data-Analysis-and-Growth-Strategy.pdf # 6-Slide Executive Presentation
└── VirtuBox_Data_Analyst_Assessment_Ansh.xlsx         # Google Sheets workbook containing all 10 assessment tabs (Q1–Q10)
