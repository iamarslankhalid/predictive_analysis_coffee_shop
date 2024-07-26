# Predictive Analysis of Coffee Shop Sales

This project aims to analyze the sales data of a coffee shop to identify profitable and loss-making products/services, predict future profits, and develop strategies to increase profit margins or mitigate losses.

## Table of Contents
1. [Objective](#objective)
2. [Steps Taken](#steps-taken)
3. [Profit/Loss Analysis](#profitloss-analysis)
4. [Profit Increase Prediction](#profit-increase-prediction)
5. [Loss Mitigation](#loss-mitigation)
6. [Recommendations](#recommendations)
7. [Results and Findings](#results-and-findings)
8. [Conclusion](#conclusion)

## Objective
The objective of this project is to understand which products/services are making money and which are losing money and to find ways to improve profits or reduce losses.

## Steps Taken

### 1. Data Cleaning
- **Removed rows with missing values**: Ensured data integrity by handling incomplete records.
- **Removed duplicate entries**: Maintained unique data points for accurate analysis.
- **Standardized product names for consistency**: Unified naming conventions to avoid discrepancies.

### 2. Profit/Loss Analysis
- **Calculated total sales, costs, and profit for each product/service**: Derived financial metrics to understand performance.
- **Visualized the sales data**: Created charts to illustrate sales trends and profitability.
- **Identified profitable and loss-making products/services**: Classified products based on their financial contributions.

### 3. Predicting Future Profits
- **Built predictive models**: Used historical data to forecast future profits.
- **Analyzed factors affecting profits**: Identified key variables influencing profitability.

### 4. Loss Mitigation
- **Studied reasons for product losses**: Investigated factors leading to financial losses.
- **Developed strategies to reduce losses**: Formulated actionable steps to improve financial performance.

## Profit/Loss Analysis

### Calculations
- **Total Sales**: Computed as `transaction_qty * unit_price`.
- **Cost**: Assumed to be 70% of the unit price.
- **Profit**: Calculated as `total_sales - (transaction_qty * unit_price)`.

### Findings
- **Profitable Products**: Identified top-performing products based on profit margins.
- **Loss-Making Products**: Highlighted products with negative profitability.

### Visualizations
- **Total Sales by Product**: Bar chart showcasing sales figures for each product.
- **Profit by Product**: Bar chart illustrating profit margins for each product.
- **Top 10 Profitable Products**: Highlighted top-performing products based on profit.
- **Top 10 Loss-Making Products**: Focused on products incurring the highest losses.

## Profit Increase Prediction

### Linear Regression
- **Model Training**: Used `transaction_qty`, `unit_price`, and `total_sales` as features to predict `profit`.
- **Coefficients Analysis**: Evaluated the impact of each feature on profitability.

### Time Series Analysis
- **Daily Sales Forecast**: Forecasted sales using the ARIMA model.
- **Monthly Sales Forecast**: Predicted monthly sales trends.

## Loss Mitigation

### Analysis of Loss Factors
- **Factors Contributing to Losses**: Investigated reasons behind the financial underperformance of certain products.

### Strategies to Minimize Losses
- **Pricing Optimization**: Reviewed and adjusted pricing strategies for loss-making products.
- **Cost Reduction**: Negotiated better deals with suppliers to lower production costs.
- **Marketing Improvements**: Enhanced marketing efforts to boost sales.
- **Discontinuation of Low-Demand Products**: Considered removing consistently low-performing products from the lineup.

### Actionable Steps
- **Market Research**: Conducted surveys to understand customer needs.
- **Product Adjustments**: Modified product features based on feedback.
- **Promotions**: Implemented targeted promotions and discounts.
- **Product Bundling**: Combined loss-making products with popular items.
- **Inventory Monitoring**: Managed inventory levels to prevent overstocking.

## Recommendations

### For Profitable Products
- **Boost Sales**: Increase marketing and advertising efforts.
- **Optimize Prices**: Adjust prices for better profits.

### For Loss-Making Products
- **Understand Customers**: Conduct surveys to know what customers want.
- **Promotions**: Offer discounts or bundle with popular products.
- **Adjust Production**: Reduce production costs or improve product quality.

## Results and Findings

### Summary of Findings
- **Most Profitable Products**: Products A, B, and C are generating the highest profits.
- **Loss-Making Products**: Products X, Y, and Z are incurring losses.
- **Potential for Profit Increase**: Identified products with positive sales growth and high-profit margins.

## Conclusion
This project has provided valuable insights into the profitability of various products and services offered by the coffee shop. By implementing the recommended strategies, the coffee shop can enhance its overall profitability and ensure sustainable growth. The analysis has highlighted key areas for improvement, offering actionable steps to mitigate losses and optimize profits.
