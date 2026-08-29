# E-Commerce Customer Analytics Project

## Project Overview
Analyzed 1M+ e-commerce transactions to segment customers and optimize checkout conversion through A/B testing.

## Business Problem
- Need to understand customer purchasing behavior
- Identify high-value customer segments  
- Test new checkout design to improve conversion rates

## Dataset
- **Source**: UCI Online Retail Dataset
- **Records**: 1,067,371 transactions
- **Time Period**: 2009-2011
- **Customers**: 5,878 unique customers

## Key Findings
1. **Customer Segmentation**: 22% Champions, 23% Loyal Customers, 25% Lost Customers
2. **A/B Testing**: New checkout design increased conversion by ~20% (statistically significant, p<0.05)
3. **Revenue Distribution**: Top 20 customers contribute significant portion of total revenue

## Analysis Performed
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- RFM (Recency, Frequency, Monetary) Analysis
- Customer Segmentation
- A/B Testing with Statistical Significance

## Tools & Technologies
- **Python**: pandas, numpy, matplotlib, seaborn, scipy
- **Analysis**: Jupyter Notebook
- **Statistical Methods**: Chi-square test, hypothesis testing

## Business Recommendations
1. Roll out new checkout design (proven conversion lift)
2. Launch win-back campaigns for Lost Customers (25% of base)
3. Create loyalty program for Champions and Loyal segments
4. Focus marketing on top-performing countries

## Files
- `notebooks/ecommerce_analysis.ipynb` - Complete analysis
- `data/online_retail_cleaned.csv` - Cleaned dataset
- `data/rfm_analysis.csv` - Customer segmentation results
- `images/` - Charts exported from the notebook

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/ecommerce_analysis.ipynb
```
Run all cells from the top. The notebook reads `../data/online_retail_II.csv` and writes its outputs back to `../data/` and `../images/`, so it must be run with its working directory set to `notebooks/` (the default when opened via Jupyter).

## Author
SURAJ SAW
Birla Institute Of Technology MESRA
