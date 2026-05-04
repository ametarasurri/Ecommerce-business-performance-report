# Olist E-Commerce Business Performance Report
### Power BI | 7 Joined Tables | ~99,000 Orders | Real Data | 2016–2018

---

Found a real e-commerce dataset on Kaggle and decided to go deep on it. Olist is Brazil's largest marketplace — connects small sellers to buyers across 27 states. The data covers 2 full years of real transactions. I wanted to understand not just what the numbers were, but what they meant for the business. So I built a 5-page analytical report and a full business case study to go with it.

---

## 🎥 Video Walkthrough

I put together a full video walkthrough of this report — covering every page, every chart, and the business insights I found. It's the fastest way to understand what's in here. Worth watching before you open the files.

👉 [Watch the Full Report Walkthrough](https://www.loom.com/share/6e120bc8d89a49a4af28072214cc5db5) 
---

## Report Details

**Business Overview**
Revenue trends, order volume, top categories, fulfillment funnel.
The headline: monthly revenue grew 700%+ year-on-year from 2017 to 2018.

**Customer & Geographic Intelligence**
Where customers are, how they pay, installment behavior.
São Paulo drives ~37% of revenue — geographic concentration risk identified.

**Operations & Retention**
Delivery performance by state, satisfaction scores, retention analysis.
The critical finding: 3.12% repeat rate vs 25–30% industry benchmark.

**Product & Freight Economics**
Freight cost as % of product price across all categories.
Home comfort category: customers pay ~53 cents shipping per $1 of product.

---

## Key Findings

- **3.12% repeat rate** — 97% of ~96,000 customers never returned. Industry benchmark: 25–30%
- **700%+ revenue growth** — January 2017 to January 2018. Platform was genuinely scaling
- **SP concentration risk** — São Paulo drives ~37% of GMV. Single-state dependency is a vulnerability
- **Delivery ≠ Satisfaction** — BA state delivers ~33 days early but scores the lowest satisfaction rating. Product quality matters more than speed
- **Cash flow lag** — 78% credit card + ~2.6 avg installments = 2–3 month payment collection delay after delivery
- **Freight problem** — Home comfort category: ~53% freight-to-price ratio. Conversion killer on cheap products

---

## Technical Details

**Tool:** Microsoft Power BI Desktop

**Data Model:** Star schema — 7 tables joined with olist_orders as central fact table

**Custom DAX Measures Built:**
- Avg Order Value
- Repeat Purchase Rate
- Delivery Delay Days
- Freight to Price Ratio
- New Customer Orders
- Repeat Customer Orders

**Dataset:** Brazilian E-Commerce Public Dataset by Olist —
Real transaction data downloaded via Kaggle. September 2016 to August 2018.

**Note:** ~$16M represents platform GMV not Olist's actual revenue.
Olist earns ~12–15% commission = estimated ~$1.9–2.4M actual revenue.

---

## Repo Structure

| Folder | Contents |
|--------|----------|
| [Report](./Report) | PBIX file + PDF export |
| [Data](./Dataset) | All 7 source CSV files |
| [Image Preview](./Image%20Preview) | Full stitched PNG preview |

---

*Jacinth Samuel CK | 2026*
