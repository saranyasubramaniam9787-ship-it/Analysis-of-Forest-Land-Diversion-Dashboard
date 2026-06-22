# 🌳 Forest Land Diversion Analysis Dashboard

*A data-driven analysis of forest land diversion trends across Indian states to understand environmental impact, key drivers, and policy implications.*

---

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools & Technologies](#tools--technologies)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [How to Use](#how-to-use)
- [Conclusion](#conclusion)

---

## Project Overview

This project analyzes forest land diversion across Indian states to understand environmental impact and development patterns.

The analysis helps in identifying:

- Total forest land diverted
- States with highest impact
- Type of forests affected
- Major drivers (Mining, Roads, etc.)
- Historical trends and future risks

The goal is to support **data-driven environmental decision-making**.

---

## Data Source

- Dataset contains **490 forest diversion projects**
- Covers **23 Indian states**
- Key attributes:
  - State name
  - Project type
  - Forest type (Protected / Reserved)
  - Area diverted (hectares)
  - Year of initiation
- Data used for academic/project analysis

---

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- Power BI (Dashboard Visualization)
- Excel / CSV for data handling

---

## Data Cleaning & Preparation

- Handled missing values
- Removed duplicates
- Standardized column names
- Converted date fields to datetime format
- Verified numerical consistency in area values

---

## Exploratory Data Analysis (EDA)

Key questions explored:

- Which states have highest forest diversion?
- Which forest types are most affected?
- What are the major drivers of diversion?
- How has diversion changed over time?

Visualizations used:

- State-wise comparison
- Year-wise trend analysis
- Forest type distribution
- Project type vs area analysis

---

## Key Insights

- Total **490 projects** across **23 states**
- Total **3,573.62 hectares** of forest land diverted
- **Punjab** has highest number of projects (133)
- **Andhra Pradesh** has highest land diversion (~929 hectares)
- **Protected Forest (~45%)** is most affected
- Main drivers: **Mining and Road construction**
- Peak activity: **2005–2012**
- Post-2012 shows stabilization in diversion trends
- Punjab → small fragmented projects
- Andhra Pradesh → large-scale high-impact projects
- High-risk future states: Odisha, Madhya Pradesh, Andhra Pradesh

---

## Recommendations

- Strengthen compensatory afforestation (1:1 or 1:2 ratio)
- Implement state-wise forest diversion limits
- Promote eco-friendly mining practices
- Use GIS & satellite monitoring for tracking
- Improve approval systems for high-impact projects
- Conduct audits in high-project states (Punjab, etc.)
- Increase transparency in environmental reporting
- Promote green infrastructure development

---

## How to Use

```bash
pip install pandas numpy matplotlib
jupyter notebook
import pandas as pd
df = pd.read_csv("forest_diversion_data.csv")
df.head()

---
