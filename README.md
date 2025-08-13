# Vendor Performance Analysis: Strategic Insights for Optimizing Procurement & Sales
This project analyzes vendor performance and procurement efficiency to identify opportunities for improving sales, pricing strategies, and inventory management.

The analysis focuses on:
- Understanding sales and profit drivers.
- Detecting slow-moving or excess stock.
- Assessing dependency on top vendors.
- Evaluating the impact of bulk purchasing on unit prices.
- Providing actionable recommendations to optimize procurement and vendor relationships.



**Objectives**
- Identify brands that require promotional or pricing adjustments — specifically those with low sales performance but high profit margins.
- Highlight vendors and brands demonstrating highest sales performance.
- Determine top vendors contributing the most to total purchases.
- Assess dependency on top vendors for total procurement.
- Analyze whether bulk purchasing reduces unit price and find the optimal purchase volume for cost savings.
- Identify vendors with low inventory turnover (slow-moving or excess stock).
- Quantify capital locked in unsold inventory per vendor and identify those contributing the most to it.



**Methodology**

Step 1:
- Data Cleaning & Preparation
- Merged data from multiple tables into a unified summary table.
- Removed irrelevant columns, standardized column names, handled missing values.
- Validated uniqueness for vendor–brand and vendor–PO combinations.

Step 2:
- Exploratory Data Analysis (EDA)
- Descriptive statistics for each variable.
- Identification of outliers and data anomalies.
- Correlation analysis to detect relationships between pricing, sales, and profitability.
- KPI calculations: sales rankings, purchase dependency, inventory turnover.



<img width="883" height="492" alt="Vendor Sales Summary" src="https://github.com/user-attachments/assets/e9d5e1f4-448f-4762-b142-5ef137607614" />



**Key Statistical Insights**

<img width="744" height="489" alt="Distribution Plot for Numerical Columns" src="https://github.com/user-attachments/assets/8fcc1e42-67c2-47c7-a726-cdf82240f558" />

Negative & Zero Values
- Gross Profit: Minimum -52,002.78 → indicates losses, possibly due to high costs or deep discounts.
- Profit Margin: Max of -∞ → occurs when revenue is zero or less than costs.
- Sales Quantity/Dollars: Minimum of 0 → suggests unsold or obsolete stock.

<img width="740" height="491" alt="Outliers" src="https://github.com/user-attachments/assets/471287f1-637c-4426-9fea-d8ac87874685" />

Outliers
- Purchase Price: Max 5,681.81 vs mean 24.39 → premium products present.
- Actual Price: Max 7,499.99 vs mean 35.64 → significant price disparity.
- Freight Cost: Ranges 0.09 – 257,032.07 → indicates possible logistics inefficiencies.
- Stock Turnover: 0 – 274.5 → some products sell extremely fast, others remain indefinitely.

<img width="696" height="543" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/9b3f49ce-1e1a-45f3-92d3-4e6c2ef4fb7d" />

Correlation Highlights
- Purchase Price vs Sales/Profit: Weak correlation (-0.012 / -0.016) → price changes do not strongly affect revenue or profit.
- Purchase Quantity vs Sales Quantity: Strong positive correlation (0.999) → efficient inventory turnover.
- Profit Margin vs Sales Price: Negative correlation (-0.179) → higher sales prices may reduce margins.
- Stock Turnover vs Profitability: Weak negative correlation → faster turnover doesn’t always mean higher profit.



**Visual Insights**

 Pareto Chart

 
  <img width="593" height="499" alt="Pareto Chart" src="https://github.com/user-attachments/assets/88f8d0ed-247e-4be8-be3a-b923f1f4dcf8" />


 Confidence Interval

 
  <img width="900" height="488" alt="Confidence Intervals" src="https://github.com/user-attachments/assets/598b0506-cac7-445e-97a5-47bad0a5cc80" />




**Power BI Dashboard**


  <img width="894" height="502" alt="Dashboard" src="https://github.com/user-attachments/assets/d55190e1-9704-44c5-9a4d-4d833902e9f2" />



**Recommendations**
- Re-price high-margin, low-sales brands → stimulate sales without eroding profitability.
- Diversify vendor base → reduce procurement dependency risks.
- Leverage bulk purchasing → optimize costs while maintaining healthy inventory levels.
- Clear slow-moving stock → adjust purchase volumes, run clearance sales, or optimize storage.
- Improve marketing/distribution → boost performance for low-performing vendors without sacrificing margins.



**Expected Impact**
- By implementing these recommendations, the company can:
- Increase sales volume while preserving margins.
- Reduce capital tied in unsold stock.
- Enhance procurement efficiency.
- Minimize supply chain risks.



Due to file size limits, the raw dataset is hosted externally: https://drive.google.com/drive/folders/1tXFRO3paEl4vvc9yzO-hxxb-neZgkwFC?usp=drive_link
