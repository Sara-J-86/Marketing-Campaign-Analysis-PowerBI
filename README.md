# Marketing Campaign Analytics Dashboard

This repository contains a Power BI project that analyzes marketing campaign performance using interactive dashboards. It leverages a rich dataset covering acquisition costs, conversion rates, ROI, engagement, and channel effectiveness.

---

## Project Overview

The goal of this project is to provide **actionable insights** into marketing efforts by visualizing performance across multiple dimensions:
- Campaign types & performance
- Channel efficiency
- Customer segments
- Financial metrics
- Geographic insights

---

## 📁 Dataset Details

| Column Name        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `Campaign_ID`      | Unique identifier for each marketing campaign                               |
| `Company`          | Name of the company running the campaign                                    |
| `Campaign_Type`    | Type of campaign (e.g., Email, Social Media, Paid Ads)                      |
| `Target_Audience`  | Demographics or attributes of the intended audience                         |
| `Duration`         | Length of the campaign in days                                              |
| `Channel_Used`     | Marketing channel used (e.g., Email, Social Media, TV)                      |
| `Conversion_Rate`  | Percentage of users who completed the desired action                        |
| `Acquisition_Cost` | Cost of acquiring a single customer                                         |
| `ROI`              | Return on investment for the campaign                                       |
| `Location`         | Geographic location where the campaign was run                              |
| `Language`         | Language used in the campaign                                               |
| `Clicks`           | Number of user clicks received                                              |
| `Impressions`      | Number of times the campaign was displayed                                  |
| `Engagement_Score` | Custom metric showing user interaction level                                |
| `Customer_Segment` | Category of users targeted (e.g., New, Returning, Premium)                  |
| `Date`             | Date of campaign launch or measurement                                      |

---

## Dashboards Included

| Dashboard Name             | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
|  **Campaign Overview**        | Visualizes types, durations, clicks, impressions, and top-performing campaigns |
|  **Audience Insights**        | Analyzes audience behavior by segment, language, and location                |
|  **Channel Effectiveness**    | Compares performance by channel: clicks, ROI, and cost-efficiency            |
|  **Customer Journey Analysis**| Shows how different attributes contribute to conversion success              |
|  **Financial Overview**       | Displays ROI trends, acquisition cost patterns, and revenue impacts         |
|  **Competitive Analysis**     | Benchmarks performance across companies, campaigns, and regions             |

---

## Key Visualizations

| Visualization Type                  | Purpose                                                          |
|-------------------------------------|------------------------------------------------------------------|
| Treemap                             | Cost per Conversion by Channel                                   |
| Filled Map                          | Location-wise Performance (Conversion Rate, Engagement Score)    |
| Decomposition Tree                  | Conversion Rate Drivers by Campaign Attributes                   |
| Waterfall Chart                     | ROI or Conversion Rate Change Over Time                          |
| Gauge                               | Average Conversion Rate Compared to Target                       |
| Line & Clustered Column Chart       | Clicks vs Impressions Over Time                                  |
| Donut Chart                         | Customer Segment Distribution                                    |
| Azure Map                           | Global Campaign Impact Visualization                             |
| Card                                | Total Campaigns, Avg ROI, Max Conversion Rate                    |
| Bar Chart                           | Top Campaigns by Engagement Score                                |
| Matrix Table                        | Company vs Channel ROI Comparison                                |

---

## How to Use

1. Open **Power BI Desktop**
2. Load the dataset from the `/Data` folder
3. Open the `.pbix` report file
4. Explore dashboards using filters, slicers, and interactivity

---

## Insights Derived

- Identify the **most cost-efficient channels**
- Discover **top-performing customer segments**
- Understand **what drives conversion rates**
- Track **ROI trends over time**
- Benchmark **campaign success across locations and competitors**

---

## Contributors
- Sara Joshi
- Nishita Jain

