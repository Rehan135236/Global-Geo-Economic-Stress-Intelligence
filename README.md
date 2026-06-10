# Global-Geo-Economic-Stress-Intelligence
A comprehensive data analytics platform for monitoring and analyzing global geo-economic stress indicators across 200+ countries spanning 1960-2025.

## 📌 Overview

A comprehensive data analytics platform for monitoring and analyzing global geo-economic stress indicators across **200+ countries** spanning **1960-2025**. The platform processes World Bank and FAOSTAT data to calculate composite stress scores (inflation, unemployment, GDP growth, income vulnerability, food pressure) and provides interactive dashboards for real-time economic vulnerability assessment.

## 📊 Dashboard Visuals (12 Components)

| Visual | Type | Purpose |
|--------|------|---------|
| Global Stress Trend | Line Chart | Track worldwide stress over time |
| Regional Stress | Horizontal Bar | Compare stress across regions |
| Regional Heatmap | Heatmap | Stress patterns over time 2000-2024 |
| Top Stressed Countries | Table | Identify high-risk nations |
| Income Group Trends | Multi-line | Compare by income level |
| Geographic Map | Choropleth Map | Global stress distribution |
| Crisis Timeline | Scatter Plot | Historical events (stress >70) |
| Stress Components | Stacked Bar | What drives stress |
| YoY Change by Region | Bar Chart | Improving vs worsening |
| Data Quality | Donut Chart | Coverage assessment |
| Correlation Matrix | Heatmap | Indicator relationships |
| KPI Metrics | Counter Tiles | Real-time monitoring |

## 📈 Key Insights

| Finding | Implication |
|---------|-------------|
| Low income countries show highest stress | Targeted intervention needed |
| Food pressure correlates strongly with stress | Food security = economic stability |
| Afghanistan consistently >70 stress | Ongoing crisis monitoring required |
| Stress peaked globally in 2020-2021 | COVID-19 impact quantified |
| Inflation and unemployment are top stress drivers | Policy focus areas identified |

## 🏗️ Architecture

CSV Files → Databricks Volume → Spark DataFrames → Delta Tables → SQL → Dashboard
