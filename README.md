# 🚗 Automotive Market Analytics – Price Optimization Study

## 📌 Project Overview
This project focused on analyzing a car dataset to uncover patterns in pricing, performance, fuel efficiency, and market segmentation. The goal was to provide automotive manufacturers with actionable insights to optimize product pricing and feature development.

## 🎯 Objectives
- Identify predictors of car price and fuel efficiency
- Analyze popularity trends across models
- Understand the impact of engine specs on pricing
- Compare pricing tiers across car brands
- Support segmentation and strategic pricing

## 🛠 Tools & Techniques
- Microsoft Excel 2019
- Data cleaning and brand-wise imputation
- Correlation and regression analysis (Linear)
- Charts: Histograms, scatter plots, dashboards

## 🧹 Data Cleaning
- Removed 715 duplicates (Make + Model + Year)
- Imputed missing values:
  - Transmission: Filled with mode
  - Market Category: Brand-wise imputation using INDEX + MATCH
- Handled missing engine horsepower values
- Standardized all categorical and numeric entries

## 📊 Key Findings
- 🚀 Popularity Boosters: Crossovers and performance cars gained high interest
- 💸 Price Drivers:
  - Engine horsepower and cylinder count showed exponential price increase
  - More doors tend to reduce price
- 🏭 Manufacturer Pricing:
  - Bugatti topped at ~$1.76M
  - Tesla priced competitively with legacy luxury brands
  - Toyota, Ford, and Honda led mid-to-low tier segments
- ⛽ Fuel Efficiency:
  - Negative correlation (-0.60) between cylinders and highway MPG
  - Post-2010 models showed rising MPG trends (up to 45 MPG)

## 🔬 Regression Insight
- Linear regression predicted MSRP with R² = 0.46 using HP and cylinders

## 🧠 Conclusion
This project shows how performance specs and brand strategy influence pricing. Excel regression analysis and visual dashboards made it easier to spot relationships and support smarter product positioning decisions in the automotive industry.
