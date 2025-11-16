
# Starbucks Customer Behavior Analysis

## Overview
Analysis of Starbucks customer purchase patterns and loyalty program effectiveness using Python. This project explores customer segmentation, spending behaviors, and offer performance to identify opportunities for revenue growth.

## Key Questions Explored
- Who are the highest value customers?
- Which customer segments should we focus on?
- How effective are different offer types?
- What drives customer engagement with the loyalty program?

## Dataset
- **Source**: Starbucks rewards program data (Kaggle)
- **Size**: 17,000 customers, 300K+ transactions
- **Time Period**: 2017-2018

## Analysis Performed

### 1. Customer Segmentation (RFM)
Used Recency, Frequency, and Monetary analysis to segment customers into 9 groups:
- Champions (high value, engaged)
- At Risk (high value, disengaging)  
- Lost (haven't purchased recently)
- New Customers
- Loyal Customers

### 2. Purchase Behavior Analysis
- Average customer spends $95
- Top 20% of customers generate 75% of revenue
- Customer lifetime value varies significantly by age and income

### 3. Loyalty Offer Performance
- BOGO offers have highest completion rate
- Discount offers work best for re-engaging dormant customers
- Informational offers have low engagement

## Key Findings
- **Revenue Concentration**: Small group of customers drives majority of sales
- **At-Risk Revenue**: Identified high-value customers showing signs of churn
- **Offer Optimization**: Different offers work for different segments
- **Demographics Matter**: 35-55 age group has highest lifetime value

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib/Seaborn for visualization
- Jupyter Notebook

## Files
- `customer_behavior_analysis.ipynb` - Main analysis notebook
- `README.md` - This file

## How to Run
1. Download the Starbucks dataset from Kaggle
2. Open the Jupyter notebook
3. Run all cells

## Next Steps
- Build predictive model for customer churn
- Create dashboard for monitoring metrics
- Test A/B testing framework for offers

## Contact
Javar Scott - [LinkedIn](https://linkedin.com/in/javar-scott)

---
*Project demonstrates customer analytics and segmentation skills applicable to retail/restaurant businesses.*
