# Car Insurance Claims Analytics Dashboard

A comprehensive Power BI dashboard designed to analyze and visualize car insurance claims data. This project transforms raw policy and claims data into actionable insights, enabling risk assessment, trend identification, and data-driven decision-making for an insurance company.

![Dashboard Screenshot](/Images/Overview.png)
*The main overview dashboard showing key metrics and visualizations.*

---

## 📊 Project Overview

This interactive dashboard provides a 360-degree view of an insurance portfolio's claims activity. By dissecting claims across various dimensions like demographics, vehicle attributes, and driver behavior, it helps answer critical business questions:
*   Who is most likely to file a claim?
*   What types of vehicles are associated with higher risk?
*   How do driving history and annual mileage impact claims frequency?

**Key Business Value:** Identify high-risk customer segments and vehicle profiles to refine underwriting policies, optimize premium pricing, and improve loss ratios.

## 🛠️ Tools & Technologies

*   **BI Platform:** Microsoft Power BI
*   **Data Processing:** Power Query
*   **Visualization:** Interactive Charts and KPI Cards
*   **Analysis:** DAX (Data Analysis Expressions)

## 📈 Key Insights & Quantitative Analysis

The analysis of 10,000 policies and 3,133 claims revealed the following:

| Metric | Value | Insight |
| :--- | :--- | :--- |
| **Total Policies** | 10,000 | Size of the insurance portfolio. |
| **Total Claims** | 3,133 | Total number of claims filed. |
| **Overall Claims Rate** | **31.33%** | A high claims rate, indicating a risky portfolio. |
| **Claims by Gender** | Male: **57.84%**<br>Female: **42.16%** | Male policyholders file a disproportionately higher number of claims. |
| **Claims by Vehicle Age** | Before 2015: **97%**<br>After 2015: **3%** | Older vehicles are a dominant factor in claims, being involved in over 97% of incidents. |
| **High-Risk Vehicle Types** | Sports Cars & Sedan | These two categories alone account for a very large combined percentage of all claims. |
| **Risk & Mileage** | Positive Correlation | Claims frequency demonstrably increases with higher annual mileage. |

## 🗂️ Dashboard Features

The report consists of two main pages:

### 1. Main Dashboard - Claims Overview
The primary page for high-level analysis and trend spotting.
*   **Executive Summary:** High-level KPIs for Total Policies, Total Claims, and Claims Rate.
*   **Demographic Analysis:** Claims distribution by **Gender**, **Education Level**, and **Age Group**.
*   **Vehicle Analysis:** Claims by **Vehicle Type** and **Vehicle Year**.
*   **Driver Behavior Analysis:** Claims by **Years of Driving Experience** and overall **Risk Segmentation**.
*   **Mileage Analysis:** A histogram showing the distribution of claims across different **Annual Mileage** ranges.

### 2. Drill-Through Page - Claims Details
A detailed, tabular view of the underlying data for deep-dive analysis.
![Drill-Through Screenshot](/Images/Claims%20Details.png)
*The detailed drill-through page showing individual policyholder records.*

*   **Purpose:** To inspect the individual records that make up any aggregated visual on the main report.
*   **Key Data Points:**
    *   **Policyholder Profile:** `ID`, `Age Group`, `Gender`, `Education`, `Income`, `Race`.
    *   **Risk Assessment:** `Driving Risk Category`.
    *   **Vehicle Info:** `Vehicle Type`, `Vehicle Year`.
    *   **Core Metric:** `Claims Outcome` (Yes/No).
*   **How to Use:** Right-click on any data point in the main dashboard (e.g., a segment of a bar chart) and select **"Drill Through > Claims Details"**. The page will filter to show only the records relevant to your selection.


### Conclusion
This Car Insurance Claims Dashboard successfully transforms complex data into clear, actionable business intelligence. It identifies key risk drivers - notably vehicle age and type - empowering strategic decisions in underwriting and risk management. The project demonstrates the power of data visualization to uncover critical insights that directly impact profitability.