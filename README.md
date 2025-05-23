# 📊 RFM & Cohort Analysis for Krotos Audio

This repository contains a complete customer segmentation and retention analysis project for **Krotos Audio**, using **RFM (Recency, Frequency, Monetary)** and **Cohort Analysis** methodologies.
---


## 🔍 Objective

To identify customer behavior patterns, segment users and visualize retention insights using Looker Studio and Excel.

---

## 🗃️ Dataset

The analysis is based on following transaction and user data:

- `transactions.csv`: Each row is a unique transaction with user ID and amount
- `users.csv`: Contains user acquisition information and creation date

---


## 📈 Analysis

### 1. RFM Segmentation
- SQL script: `sql/rfm_analysis.txt`
- Segments created: Champion, Loyal, At Risk, Lost, Hibernating,Recent but Low Freq,Others


### 2. Cohort Retention Analysis
- SQL script: `sql/cohort_analysis.txt`
- Retention matrix calculated month over month

---


## 📊 Visualizations

The results are visualized using:

- **Looker Studio Dashboards** (RFM Bar Charts, Cohort Heatmap)

View the dashboard here:  
🔗 [Looker Studio Report](https://lookerstudio.google.com/reporting/1fdd2cb3-8fcd-4336-933f-99b7f65931bb)

---

## 💡 Key Insights & Recommendations

| Segment | Action |
|---------|--------|
| 🧪 Recent but Low Freq | Trigger onboarding & offer 2nd-purchase incentives |
| 🛌 Hibernating | Re-engage with personalized win-back emails |
| ⚠️ At Risk | Offer time-sensitive discounts before churn |
| 🏆 Champion | Reward with loyalty perks or early-access |
| ❌ Lost | Avoid spending marketing budget — low return |
| 🔁 Loyal Customer |	Maintain relationship with consistent value & VIP treatment |

Cohort analysis revealed a steady drop-off after month 2.  
→ Lifecycle automations can be planned around this decay curve.

---

## ✅ Tools Used

- BigQuery SQL
- Excel Pivot Tables
- Looker Studio
- Google Sheets

---

## 🚀 Author

Prepared by: Evangelos Argyropoulos 

