# Marketing Attribution & Budget Optimization

## Overview
This project analyzes marketing performance across paid channels, partners, campaigns, customer clicks, vehicle locks, final sales, and ad spend. The goal is to evaluate acquisition efficiency, campaign ROI, and recommend how to reallocate a 20% increase in marketing budget.

## Business Problem
We wants to understand which marketing partners and channels are driving efficient customer acquisition and profitable sales. The analysis focuses on CPC, CAC, ROI, first-touch attribution, customer journey behavior, and budget reallocation.

## Data Used
The analysis uses six datasets:
- Vehicles
- Ad channels
- Clicks
- Locks
- Sales
- Spend

Raw data is not included in this repository due to data-sharing restrictions.

## Methodology
- Cleaned and standardized marketing, sales, vehicle, and spend datasets
- Parsed ad channels into category, partner, and campaign
- Recovered missing sales user IDs using lock IDs
- Built first-touch attribution logic
- Calculated CPC, CAC, sales by campaign, ROI by category, and channel interactions before lock
- Developed budget reallocation recommendations based on CAC, ROI, sales volume, and spend share

## Key Insights
- Search Engine - Hooli Sedan had the lowest CPC at approximately $1.02 per click.
- Top attributed sales campaigns were Hooli Sedan, Debit Dharma, and Hooli Convertible.
- Debit Dharma had the lowest CAC at approximately $142.86.
- Finance Partnerships delivered the highest ROI at approximately 2.32.
- Third Party Listings had the weakest ROI at approximately 0.27.
- Customers interacted with an average of 4.1 marketing channels before locking a vehicle.
- Only 2.82% of sales had no recorded click within 90 days before conversion.

## Recommendation
Prioritize incremental budget toward Debit Dharma and Giving Vine because they show strong acquisition efficiency and are relatively underfunded. Maintain or cautiously increase spend on Hooli due to strong sales volume and healthy CAC. Reduce or closely monitor spend on RealTruck and ManualBarter due to weak sales performance and high CAC.

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
