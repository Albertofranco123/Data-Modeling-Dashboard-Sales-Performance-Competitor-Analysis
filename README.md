# Data-Modeling-Dashboard-Sales-Performance-Competitor-Analysis

## Overview
This project delivers an executive Power BI dashboard for sales performance and competitor analysis. The report follows a full Business Intelligence workflow including data integration, data cleaning, data modeling, DAX calculations, and visual storytelling.  
The main objective is to help executives evaluate commercial performance, identify growth opportunities by region and category, and compare results against key competitors across international markets. :contentReference[oaicite:1]{index=1}

---

## Business Questions (SOAR – Specify)
The dashboard was designed to answer the following questions: :contentReference[oaicite:2]{index=2}

- What is our market share by country and category?
- Which competitors dominate each region?
- How has revenue evolved over recent years?
- Which segments, products, and markets show the highest growth?
- Where do short-term risks or opportunities exist?

Analytical focus:
- **Descriptive:** Historical and current performance.
- **Diagnostic:** Drivers of performance differences by product, country, and segment.
- **Predictive:** Future revenue/order trends.
- **Prescriptive:** Recommended actions based on insights. :contentReference[oaicite:3]{index=3}

---

## Data Preparation (SOAR – Obtain)
Data was integrated from multiple internal sales sources (domestic and international). Power Query was used to ensure consistency and quality through: :contentReference[oaicite:4]{index=4}

- Standardizing data types (dates, text, currency)
- Cleaning null values using **Fill Down** and **Replace Values**
- Correcting inconsistencies across tables (names, categories)
- Splitting columns using **Column From Examples**

-- Key Insights
Main findings from the analysis: 
Competitor_Analysis_ESummary
-Market Share by Region
The company leads the U.S. market with 38.22% market share, outperforming four major competitors.
-International Competitive Pressure
In Germany, Artisans holds more than 50% market share, indicating strong competitive pressure.
Sintec maintains a 21.15% global market share with solid YoY growth.
-Segments and Categories
Premium segments and high-margin categories showed the strongest annual performance.
-Revenue Trends
Q1 2021 recorded the highest YoY growth at 18.8%, driven by high-value products.
-Drill-Down Drivers
Decomposition Tree analysis highlights which categories and products most influence revenue in each country.
Author

Alberto Franco
Sales Performance & Competitor Analysis Dashboard
Power BI Case Study

