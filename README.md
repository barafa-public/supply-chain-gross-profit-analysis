# SUPPLU CHAIN GROSS PROFIT ANALYSIS

## PROJECT BACKGROUND

The data used in this analysis was independently generated without involving any third-party company. This analysis was conducted in order to improve the analyst's data analysis skills, with a focus on calculating **Gross Profit** across several spesific use cases

Gross Profit is calculated by subtracting **COGS (Cost of Goods Sold)** from **Revenue**

1. COGS: Unit Cost \* Quantity Sold
2. Revenue: Unit Price \* Quantity Sold

Objectives:

1. Category 1: Monthly Gross Profit Visualization
2. Category 2: 1-Year Gross Profit Trend Visualization
3. Category 3: Top 5 Products by Gross Profit Contribution Visualization
4. Category 4: Gross Profit Visualization by Customer Region

**Raw Data** (Excel and CSV) is available here [(LINK)](https://drive.google.com/drive/folders/1Tfb9nDPniF8bADvsv0fRkvSJTqzzzYps?usp=sharing)
**Cleaned Data** (Excel and CSV) is available here [(LINK)](https://drive.google.com/drive/folders/1v8MCJ-cAzSCNamZ0mrRPKg0eYqYtcA9_?usp=sharing)
**Visualization** results across categories are available here [(LINK)](https://drive.google.com/drive/folders/1lo42qxECn8VKy0rmoGgwk6owYSS9o835?usp=sharing)

## DATA STRUCTURE & INITIAL CHECKS

This analysis utilizes several tables:

1. Table 1: Sales Orders [(LINK)](https://drive.google.com/file/d/1EnS-WvQFzSkcru21_Vb5DfI8j3vju1OO/view?usp=sharing)
2. Table 2: Purchase Orders [(LINK)](https://drive.google.com/file/d/1NH-S7GHL_F97kAhVYyLx6H9gfxZjFkHR/view?usp=sharing)
3. Table 3: Product Master [(LINK)](https://drive.google.com/file/d/1sm5ny6jxvv3ywoW7jmSxCdbViXwRz-hf/view?usp=sharing)
4. Table 4: Warehouse Master [(LINK)](https://drive.google.com/file/d/1jbrEaCpJcz3XqWH9NeGyyzjmp1N3Tr-r/view?usp=sharing)
5. Table 5: Supplier Master [(LINK)](https://drive.google.com/file/d/19wYWlxCR25oeFZEu4Ez11ccln_kmXN5E/view?usp=sharing)

### ERD (Entity Relationship Diagram)

![ERD](/ERD.png)

## INSIGHT DEEP DIVE

**CATEGORY 1**:
Main Insight:
This is a visualization result which represents the total of gross profit from every month. Based on this data, August contributed the highest gross profit, while June contributed the lowest

![CATEGORY_1](/visualization_results/gross_profit_per_month.png)

**CATEGORY 2**:
Main Insight:
This line chart shows that gross profit changes from January to April were only slightly different. However, the trend from June to August changed drastically, and this pattern continued into September, when gross profit dropped sharply from its peak in August.

![CATEGORY_2](/visualization_results/gross_profit_history.png)

**CATEGORY 3**:
Main Insight:
The gross profits from the top 5 products show that Cordless Drill 18V contributed the highest gross profit, while Bluetooth Speaker Mini contributed the lowest.

![CATEGORY_3](/visualization_results/gross_profit_per_product.png)

**CATEGORY 4**:
Main Insight:
East Java contributed the highest gross profit, and West Java contributed the lowest.

![CATEGORY_4](/visualization_results/gross_profit_customer_region.png)

## EXECUTIVE SUMMARY

These visualization show that the peak of gross profit is in August and the lowest is in June. Cordless Drill 18V also contributed the highest gross profit, while Bluetooth Speaker Mini contributed the lowest. Then Eash Java contributed the highest gross profit.
