# ☕ Sunrise Coffee Chain Analytics

October 2026 DataDNA Challenge Submission | Onyx Data

## 📌 Project Overview

This project analyses the commercial performance of Sunrise Coffee Chain, a 60-store UK coffee business, using data covering 2023–2024.

The objective was to evaluate store profitability, loyalty programme performance, revenue mix, and monthly trading trends from a commercial analyst’s perspective. The analysis is designed to support evidence-based decisions around regional performance reviews, loyalty investment, and future expansion planning.

## 🛠️ Tools & Skills

- **Tool:** Microsoft Power BI
- **Data Modelling:** Relationships between dimension and fact tables in a fact constellation model
- **DAX:** Measures for revenue, net profit, profit margin, loyalty spend, redemption costs, and revenue shares
- **Visualisation:** KPI cards, regional and store-format comparisons, stacked columns, and monthly trend analysis
- **Analytical Approach:** Descriptive and diagnostic analytics, data validation, and business-focused reporting

## 📊 Key Findings & Business Implications

### 1. Regional Profitability

**Finding:** Northern Ireland displayed the highest net profit margin in the regional comparison, at approximately 28%, while London was below 10% in the dashboard.

**Business implication:** Regional performance varies substantially. The lower margin in London warrants further investigation into revenue, rent, staffing costs, and store-level profitability before operational or expansion decisions are made.

**Recommended next step:** Compare individual stores’ profitability status, revenue per square foot, and cost structure across regions before selecting expansion locations.

### 2. Loyalty Programme Performance

**Finding:** Loyalty members accounted for 33.19% of total monthly revenue, representing approximately £29.77M in member spend. Reported loyalty redemption costs totalled approximately £1.73M.

**Business implication:** Loyalty members represent a meaningful share of revenue, but these figures alone do not establish whether the programme generates incremental revenue or a positive return on investment.

**Recommended next step:** Evaluate member and non-member spending patterns alongside redemption costs, store-level margins, and evidence of incremental customer spend before recommending changes to the programme.

### 3. Revenue Mix & Product Margins

**Finding:** In the daily-sales dataset, food accounted for 26.07% of recorded revenue and retail beans accounted for 9.05%. The product-category comparison also highlights differences in catalogue gross margin percentages.

**Business implication:** Revenue composition and product margins can inform product-mix decisions, but high catalogue margins do not necessarily mean a category contributes the most total gross profit.

**Recommended next step:** Track category revenue shares over time and combine sales performance with product-level margin data before prioritising promotions or product bundles.

### 4. Monthly Revenue Trends

**Finding:** The monthly revenue trend visual compares 2023 and 2024, highlighting month-to-month fluctuations and differences between the two years.

**Business implication:** These patterns provide a starting point for investigating seasonality and planning trading activity.

**Recommended next step:** Validate peak and low-profit months using the monthly profitability fact table, then examine weekday, weekend, and UK bank-holiday performance by store format before adjusting staffing or stock plans.

## 🔍 Data Validation: Missing Store Format

The challenge brief describes three store formats: **High-Street, Retail-Park, and Transport-Hub**.

However, inspection of the supplied `dim_store` table found records for High-Street and Transport-Hub, but no records for Retail-Park.

**Analyst note:** This limitation was identified during data validation and reflected in the dashboard. The missing category was not fabricated or silently treated as available.

The absence of Retail-Park records in the supplied table does not establish whether the business has no such stores in reality; it establishes that the provided dataset does not support analysing that format.

## 🚧 Future Improvements

The DataDNA feedback rated the submission as **Intermediate**, with the following scores:

- **Storytelling:** 3/5
- **Design:** 2/5
- **Technical:** 3/5
- **Insights:** 3/5

Based on this feedback, potential improvements include:

- Implementing functional page-navigation buttons or bookmarks.
- Refining the visual theme with a consistent colour palette, lighter borders, and improved visual hierarchy.
- Adding an executive summary with two to three evidence-based headline findings.
- Extending the analysis to store-level profitability status, weekday/weekend comparisons, bank-holiday performance, and loyalty programme incremental value.

## 📂 Repository Contents

- `Sunrise_Coffee_Chain.pbix` — Power BI project file; requires Power BI Desktop.
-  3 Page PNG Dashboard files

## 🙏 Acknowledgements

Completed as part of the **October 2026 Onyx Data DataDNA Challenge**.

Thanks to Leon Gordon and the Onyx Data team for providing the challenge and feedback.

