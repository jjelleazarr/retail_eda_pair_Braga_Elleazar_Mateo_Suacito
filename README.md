# UK Online Retail Exploratory Data Analysis

This repository contains an exploratory data analysis (EDA) of a UK-based online gift retailer's transaction data spanning from 2009 to 2011. The primary goal is to uncover key drivers of revenue and returns to inform business strategy.

This analysis was prepared by Kirk T. Braga, Jan Vincent G. Elleazar, Michael Suacito, and Carl Jacob Mateo.

## Analysis Overview

The analysis, detailed in the [`notebooks/Retail-EDA.ipynb`](retail_eda_pair_Braga_Elleazar_Mateo_Suacito/notebooks/Retail-EDA.ipynb) notebook, covers several key areas:

1.  **Data Cleaning and Preparation**: Merging two years of data, handling missing values, removing duplicates, and flagging returns.
2.  **Feature Engineering**: Creating new columns for `Revenue`, time-based features (`Year`, `Month`, `Hour`), and customer types (`New` vs. `Repeat`).
3.  **Order and Customer Analysis**: Calculating metrics like Average Order Value (AOV) and classifying customers.
4.  **Product and Country Profiling**: Identifying top-selling products and top revenue-generating countries.
5.  **Time-Series Analysis**: Examining monthly revenue trends, seasonality, and intra-day purchasing patterns.
6.  **Returns Analysis**: Quantifying the rate and revenue impact of returns by country and product.
7.  **Customer Segmentation**: A brief RFM (Recency, Frequency, Monetary) analysis to understand customer behavior.

## Key Insights

- **Revenue is highly concentrated in the UK**, which accounts for the vast majority of sales.
- **Sales show strong seasonality**, with a significant peak in the months leading up to Christmas (Q4).
- **Peak purchasing hours** are concentrated in the early afternoon, suggesting optimal times for promotions.
- A small number of **top-selling products** contribute a significant portion of the total revenue.
- **Returns have a notable impact on profitability**, with certain products and countries showing higher return rates.
- The customer base includes a large number of **one-time buyers**, highlighting an opportunity to improve customer retention.

## How to Run

To replicate the analysis, you can run the Jupyter Notebook located at [`retail_eda_pair_Braga_Elleazar_Mateo_Suacito/notebooks/Retail-EDA.ipynb`](retail_eda_pair_Braga_Elleazar_Mateo_Suacito/notebooks/Retail-EDA.ipynb). Ensure you have the required Python libraries such as `pandas`, `numpy`, and `matplotlib` installed.