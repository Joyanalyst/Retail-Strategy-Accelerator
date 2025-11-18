# RETAIL PROFITABILITY AND OPERATIONAL HEALTH ANALYSIS
### Toolset: Excel Power Pivot, DAX, Financial Modeling, Data Modeling
### Timeline: 2023–2025 (Synthetic Dataset from [Excel.com](https://excelx.com/practice-data/sales-retail/))
## Table of Contents
- [Project Overview](#project-overview)
- [Key Techniques](#key-techniques)
- [Executive Summary](#executive-summary)
- [Insight Deep Dive](#insight-deep-dive)
- [Recommendations](#recommendations)
- [Business Impact](#business-impact)
- [Limitations](#limitations)


## Project Overview
### This project provides a comprehensive financial and operational analysis of a multi-product retail business spanning three years. Built using Excel Power Pivot and DAX, this solution provides insights into sales seasonality, product return risks, promotional ROI, and regional fulfillment efficiency to empower retail leaders to optimize fulfillment, improve profitability, and enhance promotional effectiveness.
### The project aims at:
### - Identifying fulfillment bottlenecks and regional inefficiencies
### - Evaluating product-level profitability and return risks
### - Assessing the ROI of promotional campaigns
### - Uncovering seasonal sales patterns and growth volatility
### - Segmenting customer behavior to inform upselling strategies
<img width="1896" height="724" alt="excel dashboard" src="https://github.com/user-attachments/assets/d2ee4ad8-7762-4f93-858d-1faf872d36a5" />

## Key Techniques
### •	Advanced Time Intelligence: YoY and QoQ growth metrics using DAX
### •	Return Rate Calculation: SUMX logic to accurately quantify returned items
### •	Financial Modeling: Imputed unit cost based on a 35% markup to derive profit margins
### •	Data Modeling: Creation of dimension tables for time and order granularity
### •	Customer Segmentation: ATV analysis across retail vs wholesale customers

## Executive Summary
### The analysis shows a strong sales seasonality in the first quarter (Q1) of each year. YoY/QoQ growth is highly volatile, indicating inconsistent momentum outside of the peak periods.
<img width="1110" height="284" alt="sales growth" src="https://github.com/user-attachments/assets/4eed6bb5-50ab-4bb5-991f-eada7d670409" />

## Insight Deep Dive
### 1.	Sales and Seasonality
###     Sales are highly concentrated in Q1 with $502,717.80 in 2023, $450,312.98 in 2024, and 4921,476.50 in 2025 respectively, indicating a peak period over Q2, Q3 and Q4 with a slightly declined sales. QoQ sales growth is volatile, as the growth fluctuates between each quarter, as recorded in Q3 with a positive growth of 12.63% in 2023 and a negative growth of -13.23% in 2024. This serves as a necessary             indicator to assess momentum outside of peak periods 
### 2.	Return rate red flags
### The analysis recorded the top 3 products with the highest return rates. The Laptop had the highest return rate of 47.43% in the south region, while the monitor and chair had return rates of 44.49% and 35.71% in the west region, respectively. These figures exceed the industry benchmark and directly indicate either a systematic product quality issue or a significant discrepancy between the product description/expectation setting.
### 3. Lead Time Gap
### The Northern region lags with an average lead time of 6.39 days vs Central’s 5.88 days, signaling a key opportunity for supply chain optimization to improve customer experience and reduce regional operational cost.
### 4. Promotion ROI
### FREESHIP outperforms other campaigns with an effectiveness score of 13.28, indicating the need to shift budget to promotions that deliver the highest return per dollar discounted, ensuring market spend contributes optimally to the bottom line, rather than just the top line.
### 5. Customer Spend Behaviour
### Retail customers show higher ATV ($2,950.95) than wholesale customers with ($2,889.51), indicating potential for bundling and loyalty strategies
### 6. Margin Stability
###  Profit margins are tightly clustered (29–30.4%), suggesting pricing consistency but limited optimization

## Recommendations
### 	Investigate High Return Products: Conduct root-cause analysis on chairs, laptops, and monitors in high-return regions, considering a product redesign, better packaging, or clearer product descriptions.
### 	Optimize Promotions: Focus future campaigns on proven performers like FREESHIP.
### 	 Improve Lead Time in Northern Region: Audit logistics and fulfillment processes in the North. Partner with faster carriers or optimize warehouse dispatch schedules.
### 	Target Retail Customers for Upselling: Launch premium bundles or loyalty programs for retail customers. Utilize personalized offers to increase average transaction value.
### 	Balance Quarterly Campaigns: Analyze low-growth quarters and align promotions or product launches to boost performance. Consider seasonal bundling or flash sales during historically slow periods.
### 	Explore Margin Expansion: Identify products with stable demand and test price elasticity to increase margins. Negotiate better supplier terms for high-volume items.
## Business Impact
### This dashboard serves as a retail strategy accelerator, not just a reporting tool. It enables data-driven decisions across marketing, supply chain, and product development, helping businesses shift from reactive operations to proactive growth planning.
## Limitations
### A key limitation of this analysis is the absence of unit cost data for individual products. To address this gap, a standardized markup of 35% was applied as a proxy for retail pricing. This assumption is supported by industry benchmarks reported by [Vena Solutions](https://www.venasolutions.com/), which indicate that gross, net, and operating profit margins in retail typically range between 30% and 50%. The chosen markup aligns with competitive sub-sectors such as Computer Hardware (average 34.1%), Specialty Business Services (average 35.1%), and Specialty Retail (average 36.6%). While this approach provides a reasonable basis for estimating profitability, it may not fully capture product-specific variations in cost structures.










