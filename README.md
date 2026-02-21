# Revenue-Retention-Cohort-Analysis-for-B2B-FinTech-Investor-Reporting-
Investor-grade cohort analysis used to communicate revenue quality, retention strength, and long-term growth strategy in a B2B fintech environment.

# Revenue & Retention Cohort Analysis for B2B FinTech (Investor Reporting)

## Overview
This project focuses on building a **comprehensive revenue and retention cohort analysis** for a US-based B2B fintech platform with over one million users and multiple monetization models.

The analysis was **requested by the CFO** and designed primarily for **investor reporting and fundraising discussions**, helping leadership clearly articulate:
- Revenue quality
- Retention strength
- Long-term monetization potential
- Strategic focus areas for growth

All visuals and descriptions are anonymized to preserve confidentiality.

---

## Business Context
The platform serves B2B customers through multiple revenue streams, including:
- Subscription plans (Monthly, Yearly, Pay-as-you-go, Enterprise)
- Wallet-based balances and transactions
- Add-on services
- Credit and bank-related revenue (profit sharing, rails)

While overall user acquisition was strong, leadership needed a **cohort-based view** to understand:
- How long customers stay active
- How revenue evolves after acquisition
- Which customer segments drive disproportionate long-term value

This understanding was critical for **investor communication and strategic planning**.

---

## Problem Statement
Leadership required an investor-ready analysis to answer the following questions:
- How do customer and revenue retention trends differ across subscription plans?
- Are there cohorts where revenue grows despite lower customer retention?
- Which revenue streams generate higher-margin, long-term value?
- Where should retention and product efforts be focused to maximize ROI?

Traditional aggregate metrics were insufficient to explain these dynamics clearly to investors.

---

## Stakeholders
- **Primary:** Chief Financial Officer (CFO)
- **Secondary:** Leadership team, Finance, Investors
- **Usage:** Investor presentations, fundraising discussions, strategic planning

---

## Cohort Definition
Customers were grouped into cohorts based on the **month they first became paying customers**.

Cohorts were analyzed separately for:
- Monthly subscription users (monthly cohorts)
- Yearly subscription users (12-month cohorts)
- Pay-as-you-go users
- Enterprise customers (custom contracts)
- Wallet-based revenue users
- Credit and bank profit-share revenue users

---

## Metrics Analyzed
Two core dimensions were tracked across cohorts:

### 1. Customer Retention
- Active customers retained over time
- Retention percentage by cohort and period

### 2. Gross Revenue Retention
- Total revenue contributed by each cohort over time
- Revenue retention percentage relative to cohort start
- Cross-revenue contribution (subscriptions + wallet + add-ons + credit)

---

## Data & Tools
- **Data Source:** MySQL databases hosted on AWS
- **Tools:** Power BI, Excel
- **Data Domains:**
  - Subscription and billing
  - Payments and transactions
  - Wallet balances
  - Add-ons and credit revenue

Multiple databases and tables were consolidated into a single analytical model optimized for cohort analysis.

---

## Methodology
- Classified customers by subscription and revenue type
- Anchored cohorts on first paid month
- Built cohort matrices for:
  - Customer counts
  - Retention percentages
  - Absolute revenue
  - Revenue retention percentages
- Created separate cohort views for each revenue stream
- Designed executive-friendly Power BI dashboards with drill-down capability
- Delivered Excel exports for further financial and investor analysis

All calculations were validated to meet **finance and investor reporting standards**.

---

## Key Insights
- **Revenue retention increased even when customer retention declined**, revealing the presence of high-value customers within smaller cohorts
- A small percentage of retained customers contributed a disproportionately large share of revenue
- Certain subscription plans demonstrated significantly stronger long-term revenue retention
- Wallet-based revenue showed higher-margin characteristics compared to direct bank transfers
- Early cohort behavior was highly predictive of long-term revenue contribution
- Analysis indicated that a **10% improvement in retention could drive a 60–70% increase in revenue**, due to revenue concentration effects

---

## Business Impact
- Insights were directly used by the **CFO in investor presentations and fundraising pitches**
- Helped leadership clearly communicate **revenue quality and retention strength** to investors
- Influenced **subscription plan restructuring** and pricing strategy
- Shifted business strategy toward **maximizing wallet usage** due to higher-margin, interest-based revenue
- Enabled retention efforts to focus on **high-impact customer segments** rather than volume-based growth
- Established cohort analysis as a recurring input for financial and strategic decision-making

---

## Deliverables
- Investor-ready Power BI dashboards
- Excel cohort models for finance and investor deep dives
- Cohort insights integrated into CFO-led investor decks

---

## Key Takeaways
This project demonstrates how **cohort analysis can move beyond BI reporting** to become a core tool for:
- Investor storytelling
- Revenue quality assessment
- Strategic growth planning in B2B fintech

It highlights the importance of understanding not just how many customers churn, but **which customers and revenues truly matter**.

---

## Notes on Confidentiality
- All customer identifiers, revenue figures, and internal plan names are anonymized or rounded
- No proprietary business logic or sensitive data is disclosed
- Visuals shared publicly are sanitized and illustrative only
