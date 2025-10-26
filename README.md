# Global-Trade-and-GDP-Correlation-Study
I created this project to investigate how international trade affects economic growth across countries using actual data from Kaggle. The study found a strong positive correlation (r = 0.62) between trade openness and GDP growth, indicating that export-driven economies outperform import-heavy ones.

### End-to-End Data Analytics & Visualization Project  
**Tools:** Python (Pandas, NumPy, Seaborn, Scikit-learn), Power BI, Excel  
**Dataset Source:** Kaggle – Global Trade and GDP Dataset (Cleaned & Summarized)

---

## Project Overview

This project explores the **relationship between international trade and GDP growth** across countries, identifying how trade openness impacts economic performance.

Using real-world macroeconomic indicators, the analysis investigates:
- How closely **exports, imports, and trade-to-GDP ratios** correlate with GDP and GDP growth.
- Which countries are **most trade-dependent** and whether that dependency translates to higher economic growth.
- Trends and anomalies — countries with **high trade but low growth**, and vice versa.

The project concludes with a fully interactive **Power BI dashboard**, demonstrating insights through advanced visuals, KPIs, and correlation storytelling.

---

## Project Workflow

### **1. Data Preparation (Python)**
- Imported and cleaned Kaggle dataset (`Countries.csv`)
- Engineered key metrics:
  - Trade Balance = Exports – Imports  
  - Trade-to-GDP Ratio (%)  
  - Log-transformed GDP and Trade  
- Aggregated data at **country level** for Power BI
- Exported correlation matrix & Power BI–ready dataset (`global_trade_gdp_summary.csv`)

### **2. Exploratory Data Analysis (EDA)**
- Explored GDP and trade distributions across regions
- Analyzed correlations between GDP Growth, Trade Ratio, and GDP Level
- Visualized relationships using heatmaps, scatter plots, and trend lines

### **3. Regression & Insights**
- Built regression models to quantify correlation:
  - **Linear Regression** (Trade-to-GDP vs GDP Growth)
  - **Ridge, Lasso, and RandomForest Regression** (for robustness)
- Extracted key coefficients and R² values for Power BI integration

### **4. Visualization (Power BI)**
Designed a 4-page interactive dashboard:
- **Overview:** Global KPIs and map visualization  
- **Correlation:** Scatter plot of Trade-to-GDP vs GDP Growth with regression line  
- **Trends:** GDP, Exports, Imports over time  
- **Country Explorer:** Drill-through page with detailed metrics and insights

---

## 📈 Power BI Dashboard Highlights

| Page                  | Purpose |                        Key Visuals |
|----------------------|----------|------------------------------------|
| 🌍 **Overview** | High-level global metrics | KPI cards, Map (GDP size & Trade Ratio color) |
| 📊 **Correlation** | Relationship between Trade-to-GDP & GDP Growth | Scatter with trendline, correlation card |
| 📉 **Trends** | Time-based growth and trade performance | Line & bar charts |

**Key Insights:**
- Countries with **higher trade-to-GDP ratios generally show higher growth**, though outliers exist.  
- **Emerging economies** exhibit stronger positive correlation than developed ones.  
- **Trade balance volatility** impacts GDP consistency — high surplus nations maintain stable growth.

---

## ⚙️ Tech Stack

| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy)** | Data Cleaning & Transformation |
| **Matplotlib, Seaborn** | Exploratory Visualizations |
| **Scikit-learn** | Regression & Correlation Modeling |
| **Power BI** | Dashboard Design & KPI Visualization |
| **Excel** | Quick Explorations & Summary Sheets |

---
