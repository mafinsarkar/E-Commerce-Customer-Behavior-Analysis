# 🧮 Customer Segmentation & Churn Analysis

Understanding customer behavior is crucial for targeted marketing and retention strategies.  
This project applies **RFM (Recency, Frequency, Monetary)** analysis to segment customers and evaluate churn risk.  
It provides data-driven insights to optimize customer engagement, loyalty programs, and retention efforts.

---

## 📊 Project Overview

This project focuses on analyzing customer purchase behavior to:

- Segment customers using **RFM metrics**.  
- Identify **key customer groups** based on value and engagement.  
- Define and measure **customer churn**.  
- Visualize insights for **marketing and retention strategies**.

---

## 🧠 RFM Model Overview

| Metric | Description | Ideal Trend |
|:-------:|:-------------|:-------------|
| **Recency (R)** | Days since last purchase | Lower is better |
| **Frequency (F)** | Number of purchases | Higher is better |
| **Monetary (M)** | Total spending | Higher is better |

These three metrics are combined to rank and group customers into meaningful segments.

---

## 🧩 Customer Segments

| Segment | Description | Avg. Recency (Days) | Avg. Frequency | Avg. Monetary ($) |
|----------|--------------|--------------------:|----------------:|------------------:|
| **Champion** | Highest value, most engaged | 107.38 | 2.73 | 1839.57 |
| **Loyal** | Consistent, frequent buyers | 228.02 | 1.89 | 1016.37 |
| **Potential** | New or low-frequency customers | 323.76 | 1.18 | 548.25 |
| **At-Risk** | Low engagement, high churn risk | 492.55 | 1.01 | 197.45 |
| **Lost** | Inactive, very low value | 626.13 | 1.00 | 75.99 |

**Insight:**  
Monetary value decreases sharply across the segments, emphasizing the need to retain *Champions* and *Loyal* customers.

---

## 🔄 Churn Analysis

A **customer is considered “churned”** if they have not made a purchase in **over 180 days**.

| Status | Avg. Recency (Days) | Avg. Frequency | Avg. Monetary ($) |
|:--------|:--------------------:|:----------------:|:----------------:|
| **Active** | 86.8 | 1.88 | 955.70 |
| **Churned** | 421.9 | 1.43 | 713.52 |

**Key Finding:**  
Recency is the strongest indicator of churn risk — churned customers have much longer inactivity periods.

---

## 🎯 Actionable Insights

- **Prioritize At-Risk customers:** Re-engage users around 490 days of inactivity.  
- **Boost Recency:** Run time-sensitive promotions to encourage repeat purchases.  
- **Increase Frequency:** Offer loyalty rewards or bundles to drive repeat orders.  
- **Maintain Champions:** Provide exclusive perks or early access to new products.  
- **Upskill Potential customers:** Use educational or personalized marketing content.

---

## 🚀 Next Steps

- Integrate segmentation with CRM tools for real-time updates.  
- Automate churn prediction and retention campaigns.  
- Incorporate **K-Means clustering** or **machine learning models** for deeper segmentation.  
- Analyze **product preferences** by segment to optimize recommendations.

---

## 🧰 Tech Stack

- **Python 3.x**  
- **Pandas** – data analysis  
- **NumPy** – numerical operations  
- **Matplotlib / Seaborn** – visualization  
- **Jupyter Notebook** – for exploration and reporting  

---
