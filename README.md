### Retail Analytics: Superstore Profitability Analysis

**Analyzing 9,994 transactions to identify $127K+ in profit recovery opportunities**

#Project Overview

I analyzed 4 years of retail transaction data (2015-2018) to answer critical business questions about profitability, discount strategies, and regional performance. This project demonstrates my ability to turn raw data into actionable business insights.

#Key Achievement:* Identified that 97.8% of heavily discounted transactions generate losses, costing $127,738 annually.

#Key Findings

1. Discount crisis - 97.8% of orders with >30% discount lose money, cap discounts at 30 %->recover $127K
2. Category Gap - Furniture (2.5% margin) vs Technology (17.4% margin), Restructure Furniture pricing 
3. Regional Imbalance - West ($108K profit) vs Central ($40K profit), Replicate West's success
4. High-Value Customers - 0.2% of customers drive 7.8% of revenue, VIP retention program
5. Q4 Dependency - November-December = 30% of annual sales, Optimize holiday inventory

### Visualizations
1. Category Profitability
![Category (https://drive.google.com/file/d/1BL6gPQyL0q7CmjrDyfrmmLRUDFa4P3FH/view?usp=drivesdk)

Insight: Technology leads with 17.4% margin while Furniture severely underperforms at 2.5%

3. Regional Sales Trends
![Regional Trends](https://drive.google.com/file/d/1BOXaGFDjyGdnAWAvhhKEiUUQLSVSlQkJ/view?usp=drivesdk)
Insight: Clear Q4 seasonality - November and December drive 30% of annual revenue

4. Discount Impact on Profit
![Discount Analysis](https://drive.google.com/file/d/1BTEE1eeY-121bGGbnUet7UpUG6b_Jwlc/view?usp=drivesdk)
Insight: Strong negative correlation - discounts above 30% almost guarantee losses

6. Sales Distribution
![Distribution](https://drive.google.com/file/d/1BUePbbuFfSLgM5Rg-zVYzt0oMUjQHfgN/view?usp=drivesdk)
Insight: Highly skewed - median order is $54 but mean is $230 due to high-value outliers

7. Category × Region Performance
![Heatmap](https://drive.google.com/file/d/1BraSAgHHBUC9holHIuvnT4NhjauWQKCE/view?usp=drivesdk)
Insight: West + Office Supplies = $52K profit (best), Central + Furniture = -$2,871 (only loss)


### Analysis Approach

Tools Used: Python, Pandas, Matplotlib, Seaborn, Google Colab

Methodology:
1. Data Cleaning - Validated 9,994 transactions, checked for nulls and duplicates
2. Feature Engineering - Created profit margin, time-based features
3. Exploratory Analysis - Identified patterns, outliers, correlations
4. Statistical Analysis - Calculated distributions, thresholds, segment performance
5. Visualization - Created 6 charts with business annotations
6. Business Recommendations - Translated findings into actionable strategies

### Business Recommendations
1. Immediate Actions (0-30 days)
- Cap discounts at 30% - Stops $127K annual profit leak
- Review Central region Furniture - Eliminate $2,871 loss
- Protect high-value customers - 19 customers drive 7.8% of revenue

2. Strategic Initiatives (30-90 days)
- Build customer lifetime value (CLV) tracking
- Replicate West region's Office Supplies success
- Optimize Q4 inventory for holiday peak

### Dataset

Source:Sample Superstore (retail transactions)  
Period: 2015-2018  
Records: 9,994 transactions  
Columns: Order Date, Region, Category, Sales, Discount, Profit, Customer Segment, Ship Mode

### Technical Skills Demonstrated

- Python Programming - Pandas, NumPy for data manipulation
- Data Analysis - Statistical analysis, correlation, segmentation
- Data Visualization - Matplotlib, Seaborn for professional charts
- Business Intelligence - Translating data into strategy
- Communication - Executive summaries, annotations, insights

