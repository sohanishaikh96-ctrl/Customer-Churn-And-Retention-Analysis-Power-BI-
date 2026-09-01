# Nova Mart Retail — Customer Churn & Retention Analysis (Power BI)
<img width="1668" height="889" alt="image" src="https://github.com/sohanishaikh96-ctrl/Customer-Churn-And-Retention-Analysis-Power-BI-/blob/main/Effective-Customer-Acquisition-Examples.webp" />


---

## 📌 Introduction

This project analyses customer attrition and retention at **Nova Mart Retail** using **Power BI**. The analysis focuses on understanding customer loss trends, identifying the key reasons behind customer churn, evaluating the financial impact of that churn, and identifying high-value customers currently at risk. The insights generated are designed to help the business make data-driven decisions to improve customer retention and reduce future customer loss.

---

## ❗ Business Problem

The company has noticed a steadily increasing number of customers leaving the business. Management wants to:
- Understand the major causes of customer churn
- Identify high-value customers at risk of leaving
- Quantify the financial impact of churn
- Develop strategies to improve customer retention

---

## 🎯 Project Objective

The objective of this project is to analyse customer behaviour and identify the key factors contributing to customer attrition at Nova Mart Retail. The analysis aims to:
- Measure customer loss (churn) trends over time
- Identify the major reasons customers leave
- Understand attrition patterns across regions and customer segments
- Assess the financial impact of customer loss
- Identify high-value customers who are at risk of leaving

The insights from this analysis will help management develop targeted customer retention strategies and reduce future customer loss.

---

## 🗂️ Dataset Description

The dataset is a **synthetic customer analytics dataset** containing **10,000 customer records**, created for analysing customer attrition and retention patterns. It contains customer demographics, purchase behaviour, customer service interactions, customer value, attrition information, and risk indicators. The dataset is split into multiple related tables to simulate a real-world business database.

### Tables Included

| Table | Description |
|---|---|
| **Customer_Master** | Contains customer information, demographics, customer value, attrition status, attrition reason, and risk indicators. |
| **Sales_Data** | Contains customer purchase and product-level sales information. |
| **Customer_Interactions** | Contains customer service interactions such as complaints, support calls, response time, and resolution rate. |

📎 **Dataset Link:** 
- <a href="https://github.com/sohanishaikh96-ctrl/Customer-Churn-And-Retention-Analysis-Power-BI-/blob/main/Customer_Churn_Retention_Analysis_10000%20(1).xlsx">Dataset</a>

---

## 🔗 Data Model
<img width="1668" height="889" alt="Data Model" src="https://github.com/sohanishaikh96-ctrl/Customer-Churn-And-Retention-Analysis-Power-BI-/blob/main/Screenshot%202026-09-01%20185220.png" />

---

## 📊 Dashboard Pages
**Churn Analysis**
<img width="1668" height="889" alt="Dashboard1" src="https://github.com/sohanishaikh96-ctrl/Customer-Churn-And-Retention-Analysis-Power-BI-/blob/main/Screenshot%202026-09-01%20184955.png" />

**Customer Analysis**
<img width="1668" height="889" alt="Dashboard1" src="https://github.com/sohanishaikh96-ctrl/Customer-Churn-And-Retention-Analysis-Power-BI-/blob/main/Screenshot%202026-09-01%20185044.png" />

---

## 🔑 Key Findings

**Overall Churn**
- Of 10,000 total customers, **1,640 have churned**, giving an overall churn rate of **16.40%** (8,360 active).

**Churn Trend (2021–2026)**
- Churn has grown sharply year over year: **15 (2021) → 99 (2022) → 190 (2023) → 332 (2024) → 519 (2025) → 495 (2026)**.
- Churn peaked in 2025; 2026 shows a slight decline of ~4.6% versus 2025.

**Churn by Value Segment**
- Medium-value customers: **823 churned** (largest volume loss)
- High-value customers: **418 churned**
- Low-value customers: **399 churned**

**Risk Levels**
- **408 customers (4.08%)** are currently classified as **High Risk**.
- **33.01%** of the total base (3,301 customers) sits in **Medium Risk** — the largest at-risk pool.
- Among high-value customers specifically: **1,760 are Medium Risk** and **125 are High Risk**.

**Regional & Demographic Patterns**
- The **West region** has the highest number of churned customers.
- **Regular-tier** customers churn the most compared to other tiers.
- Female churn rate (**16.80%**) is marginally higher than male (**16.04%**).

**Service & Engagement Behavior**
- Higher support call volume correlates with **lower** churn.
- Lower complaint counts correlate with **higher** churn (silent disengagement before exit).
- Higher satisfaction scores and resolution rates generally correlate with lower churn — but a segment of highly satisfied customers still churns due to **competitor offers, high price, and product quality**.

**Top Reasons for Churn**
1. Competitor offers
2. High price
3. Poor customer service

**Product-Level Churn**
- Top 5 products driving churn: **Laptop, Headphone, Tablet, Household, Smartwatch**
- Top 3 products churning specifically due to **Product Quality**: **Tablet, Jacket, T-shirt**

**Financial Impact**
- Average discount offered to customers: **9.70%**
- Sales lost due to churn: **$222.24M** out of total sales of **$1.37B** (~16.2% of total sales)
- Profit lost due to churn: **$36.72M** out of total profit of **$225.92M** (~16.3% of total profit)

---

## 💡 Insights

1. **This is largely a competitive/pricing problem, not a service problem.** Even satisfied customers with high resolution rates are leaving — pointing to external pressure from competitor offers and pricing rather than internal service failures.
2. **Silence is a stronger churn signal than complaints.** Customers who stop reaching out (fewer calls, fewer complaints) are quietly disengaging before leaving, rather than escalating issues first.
3. **The biggest financial risk sits in the "Medium Risk" band, not "High Risk."** With 1,760 high-value customers at Medium Risk versus only 125 at High Risk, there is a large, time-sensitive window for intervention.
4. **Churn is accelerating as the business scales**, suggesting either a maturing customer base reaching natural churn points or an intensifying competitive/pricing issue.
5. **Product quality issues are a distinct, separate churn driver** — Tablet, Jacket, and T-shirt show quality-specific churn independent of the broader price/competitor trend.
6. **West region and "Regular" tier customers are concentration points**, suggesting a regional competitive threat or weaker loyalty incentives for that tier.

---

## ✅ Recommendations

- **Pricing & Competitive Response:** Run a competitive price-gap analysis for Laptop, Headphone, Tablet, Household, and Smartwatch categories; introduce price-match or win-back offers for at-risk customers in these categories.
- **Proactive Retention for Medium-Risk High-Value Customers:** Prioritize outreach to the 1,760 high-value/medium-risk customers before they escalate to high risk.
- **Re-engage Silent Customers:** Identify customers with declining engagement (fewer calls/complaints) and trigger proactive check-ins rather than waiting for inbound contact.
- **Product Quality Review:** Investigate quality issues specifically for Tablet, Jacket, and T-shirt lines.
- **Regional Strategy:** Investigate West region churn drivers (competitor presence, service performance, logistics) and pilot a region-specific retention program.
- **Tier-Based Loyalty Review:** Assess whether "Regular" tier customers are under-served by loyalty programs compared to premium tiers.
- **Enhance Risk Scoring:** Incorporate price-sensitivity and competitor-exposure signals into the risk model, since satisfaction/resolution scores alone don't fully predict churn.

---

## 💰 Financial Impact

Churn is not just a customer-count problem — it carries a direct, measurable revenue and profit cost:

| Metric | Lost (Churn) | Total | % Impact |
|---|---|---|---|
| **Sales** | $222.24M | $1.37B | ~16.2% of total sales |
| **Profit** | $36.72M | $225.92M | ~16.3% of total profit |

- The company currently offers an **average discount of 9.70%** to customers — yet despite this discounting, churn has continued to rise, reinforcing the earlier finding that **price alone is not retaining customers** and that competitor offers and product quality are stronger pulls than the current discount strategy can offset.
- The proportion of sales and profit lost (~16.2%–16.3%) tracks closely with the overall customer churn rate (16.40%), indicating churned customers are being lost **roughly in proportion to their value** rather than the business selectively losing only low-value customers — this reinforces the earlier finding that a meaningful share of losses (823 medium-value and 418 high-value customers) carries real revenue weight, not just headcount.
- With **125 high-value customers already at High Risk** and **1,760 high-value customers at Medium Risk**, unresolved churn in this segment could meaningfully extend both the sales and profit loss shown above if untreated.
- This suggests discounting in its current form is a **retention cost without a proportional retention return**, and spend may be better redirected toward the targeted, segment-specific interventions in the Recommendations section (medium-risk high-value outreach, competitive price-gap fixes, and product quality resolution) rather than broad, undifferentiated discounting.

---

## 🏁 Conclusion

The analysis shows that Nova Mart Retail's rising churn is driven less by service failures and more by **external competitive pressure, pricing, and select product quality issues**. While overall churn stands at 16.40%, the greatest business risk lies in the large pool of medium-risk, high-value customers who have not yet churned but show warning signs. Addressing pricing competitiveness, acting proactively on disengaged (rather than only complaining) customers, and resolving product-specific quality issues in categories like Tablets, Jackets, and T-shirts should be the company's near-term priorities. With a targeted, segment-specific retention strategy — particularly for high-value, medium-risk, and West-region customers — Nova Mart Retail can meaningfully slow churn growth and protect its most valuable customer relationships.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** — Data modeling, DAX measures, and dashboard visualization
- **Power Query** — Data cleaning and transformation




## 👤 Author

*[Your Name]*
📧 *[Your email / LinkedIn]*
