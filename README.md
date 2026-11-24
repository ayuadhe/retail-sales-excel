# Retail Sales Performance & Cancellation Analysis

<p align="center">
  <img width="1670" height="1080" alt="project_01" src="https://github.com/user-attachments/assets/60049df9-6437-43f9-9011-4d653ed9c9cc" />
</p>

### 1. Executive Summary
This project analyzes 464K cleaned retail transactions from a UK-based online retailer, reduced from an initial dataset of 541K records through data cleaning and preparation. Covering January to November 2011, the analysis uses Microsoft Excel, Power Query, Power Pivot, and DAX to evaluate sales performance, product and market contributions, and order cancellations.

The analysis found that sales growth was primarily driven by increasing order volume, while the UK accounted for 84% of total revenue. The top 10 products contributed only 8.1% of revenue, indicating a broad product revenue distribution. Meanwhile, cancellations represented 14.6% of orders but only 2.3% of revenue. These findings inform recommendations to sustain order growth, diversify market contributions, and investigate cancellation patterns for operational improvements.

<br>

### 2. Project Overview
This project evaluates the business performance of a UK-based online retailer through an interactive Excel dashboard. The dashboard consists of three pages covering sales performance, product and market contributions, and order cancellations. The analysis highlights key performance drivers and areas requiring attention, helping sales, marketing, and operations teams identify priorities for improvement.

<br>

### 3. Objective
The objective is to build an interactive Excel dashboard that turns transaction data into clear answers to three business questions:
1. How is the business performing overall?
2. What drives sales performance?
3. What reduces sales performance?

<br>

### 4. Key Areas of Analysis
1. **Sales Performance Analysis**: Monthly trends in Net Sales, total orders, Average Order Value (AOV), and units sold, and country-level Net Sales and AOV performance.

2. **Product & Market Performance**: Product sales distribution, top 10 products and top 5 countries by Net Sales, sales contribution by customer type (registered vs. guest), and performance comparison between bulk and non-bulk orders based on sales and AOV.

3. **Order Cancellation Analysis**: Cancelled sales, cancelled orders, and cancelled units, including monthly cancellation trends, top 10 products by cancellation volume, and order cancellation rates by country.

<br>

### 5. Dataset Overview
| Information | Before Cleaning | After Cleaning & Transformation |
|---|---|---|
| Records | 541,910 | 464,136 |
| Tables | 1 | 2 (Sales, Products) |
| Columns | 8 | 11 (Sales), 2 (Products) |
| Data Period | Dec 2010 – Dec 2011 | Jan – Nov 2011 |

**Data Source**: Dr. Daqing Chen, Course Director: MSc Data Science. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

<br>

### 6. Tools & Methodology
- **Microsoft Excel**: using Power Query for data preparation, Power Pivot and the Data Model for data modeling and DAX measures, and PivotTables, PivotCharts, and slicers for interactive dashboard development.

<br>

### 7. Visualization & Analysis
A. **Sales Performance Analysis**
<p align="center">
  <img width="1996" height="1040" alt="image" src="https://github.com/user-attachments/assets/7f0fca21-2a83-4424-bcb6-83186ab1977a" />
</p>

- Sales grew strongly toward year-end: September to November contributed about 41% of Net Sales, and November ($1.45M) was about 2.4x January ($593K).
- Growth was primarily driven by order volume, which rose from about 1,080 orders in January to about 2,750 in November (roughly 2.5x), while monthly AOV stayed relatively stable between £417 and £566.
- The United Kingdom was the largest contributor to Net Sales (£7.37M, about 84%). However, the Netherlands recorded the highest AOV (~£3.03K), followed by Australia (~£2.59K) and Singapore (~£2.28K).

<br>

B. **Product & Market Performance**
<p align="center">
  <img width="2032" height="1042" alt="image" src="https://github.com/user-attachments/assets/e88a9d27-6d2e-4214-b8f8-e1efb7820055" />
</p>

- The top 10 best-selling products contribute only 8.1% of total revenue, indicating a relatively broad revenue distribution across products rather than heavy reliance on a few top-selling items.
- Revenue is heavily concentrated in the UK, which contributes £7.37M out of £8.78M in total sales, accounting for approximately 84% of overall revenue.
- Registered customers account for 86.38% of total revenue, compared to 13.62% from Guest customers, making registered customers the primary revenue contributors.
- Sales are largely driven by Non-bulk transactions, contributing £8.66M compared to just £119K from Bulk transactions.
- Bulk transactions have an AOV of £2,162, approximately 4.3 times higher than Non-bulk transactions (£498).

<br>

C. **Order Cancellation Analysis**
<p align="center">
  <img width="2030" height="1042" alt="image" src="https://github.com/user-attachments/assets/249f252d-aa64-4f07-94a3-cb153420b73d" />
</p>

- Cancellations account for 14.6% of total order volume but only 2.3% of revenue, indicating that cancellations are more prevalent among lower-value transactions.
- Cancellation-related revenue peaked in April (~£33.3K) and October (~£41.6K).
- White Hanging Heart T-Light Holder recorded the highest cancellation volume at 2,049 units, nearly twice that of the second-highest product.
- Among countries with at least 30 orders, Italy (about 29%), Switzerland (about 27%), and Germany (about 23%) recorded the highest cancellation rates, compared with about 14% in the UK. The causes behind these higher rates warrant further investigation.

<br>

### 8. Key Findings
1. **Sales Growth Driven by Order Volume** <br>
Sales showed a positive growth trend, particularly from September to November, primarily driven by an increase in order volume while AOV remained relatively stable.

2. **Strong Revenue Concentration in the UK** <br>
The UK accounted for approximately 84% of total revenue (£7.37M out of £8.78M), indicating a high level of business dependence on a single market.

3. **Revenue Is Diversified Across Products** <br>
The top 10 best-selling products contribute only 8.1% of total revenue, indicating that sales are broadly distributed across the product portfolio rather than concentrated in a few top-selling items.

4. **Bulk Orders Have Higher AOV but Limited Revenue Contribution** <br>
Bulk orders have an AOV about 4.3 times higher than non-bulk orders ($2,162 vs $498), yet contribute only $119K, about 1.4% of Net Sales. Revenue is driven by the volume of regular orders, not by large purchases.

5. **Order Cancellations Disproportionately Affect Low-Value Transactions** <br>
Cancellations accounted for 14.6% of total orders but only 2.3% of revenue, suggesting that cancellations were concentrated in lower-value transactions. The spikes in April and October, along with product-level concentration, warrant further investigation.

<br>

### 9. Recommendations

1. **Sales Growth & Market Expansion**
   - Capitalize on the September–November sales momentum by identifying key growth drivers, such as promotional effectiveness, seasonal trends, and customer behavior, to refine marketing strategies and maintain adequate stock availability.
   - Drive order growth through customer acquisition and retention, while increasing AOV through cross-selling, upselling, and product bundling rather than relying heavily on discounts.
   - Strengthen customer retention in the UK through loyalty and retention programs, while optimizing stock availability to sustain performance in the company's primary market.
   - Target the Netherlands, Australia, and Singapore through customer retention initiatives and premium product offerings to increase revenue beyond the UK market.
   - Diversify revenue sources by expanding into other promising markets to reduce dependence on a single dominant market.

2. **Customer & Product Optimization**
   - Maintain product variety as a sales strategy by expanding product assortment and cross-selling opportunities, given that revenue is not heavily concentrated among the top 10 products.
   - Strengthen registered customer retention through loyalty programs, personalized offers, and repeat-purchase strategies to sustain the largest revenue-contributing segment.
   - Maintain Non-bulk transaction volume as the primary revenue driver while optimizing Bulk sales strategies to increase their revenue contribution.
   - Drive Bulk transaction growth through targeted offers for wholesale customers, volume-based pricing, and bulk-purchase incentives to capitalize on their 4.3 times higher AOV.

3. **Cancellation Analysis & Reduction**
   - Identify the key drivers of order cancellations by examining the purchase stages most frequently associated with cancellations, particularly among lower-value transactions.
   - Investigate the factors behind cancellation spikes in April and October to develop preventive measures for similar periods in the future.
   - Review stock availability, product quality, and customer expectations for White Hanging Heart T-Light Holder to identify potential causes of its high cancellation volume.
   - Investigate the higher cancellation rates in Italy, Switzerland, and Germany by analyzing order patterns, product mix, and customer behavior to identify what drives cancellations in these markets.

<br>

### 10. Limitations
- The absence of product category data limits category-level sales analysis.
- Missing customer IDs limit customer retention and repeat purchase analysis.
- The absence of cancellation reasons and order stages prevents deeper investigation into cancellation causes.
- Incomplete December records limit full-year performance and seasonal analysis.
- The absence of product cost and operational expense data prevents profitability and margin analysis.
- The absence of inventory and shipping data limits stock availability and delivery performance analysis.
- The bulk purchase threshold (quantity above 1,196) is based on a statistical method rather than a business-defined criterion.
- Country-level cancellation analysis is limited to countries with at least 30 orders, as rates based on smaller samples are unreliable.
