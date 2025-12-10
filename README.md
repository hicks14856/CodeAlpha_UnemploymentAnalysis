# CodeAlpha_UnemploymentAnalysis
This is my data science project for my internship at data science. In this project I employ data cleaning, EDA and visualisation skills on unemployment data in India to iinvestigate the impact that covid-19 has had on the indian economy. 
# 📉 Unemployment Analysis in India: A Covid-19 Case Study

### **CodeAlpha Data Science Internship - Task 2**

## 📋 Project Overview
This project is a comprehensive data analysis of India's unemployment trends during the Covid-19 pandemic (2019-2020). Acting as a Macro-Economic Analyst, the goal was to investigate the economic shock of the lockdown, quantify its severity across different regions, and identify specific sectors that were most vulnerable.

By utilizing a **Drill-Down Analysis Framework**, this project moves from national macro-trends to granular state-level and sectoral insights.

## 🎯 Objectives
* **Macro-Analysis:** Visualize the sudden spike in unemployment rates coinciding with the national lockdown.
* **Regional Segmentation:** Identify which Indian states were the "hotspots" of the economic crisis.
* **Sectoral Impact:** Compare the volatility between **Urban** (Industrial/Services) and **Rural** (Agrarian) economies.
* **Correlation Analysis:** Investigate the relationship between Labour Participation Rate and Unemployment (The "Discouraged Worker" Effect).
* **Geospatial Intelligence:** Map the severity of the crisis using coordinate-based visualization.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `Pandas`: Data Cleaning, Time-Series manipulation, and Aggregation.
    * `Matplotlib` & `Seaborn`: Static statistical visualizations (Box Plots, Trend Lines).
    * `Plotly Express`: Interactive geospatial scatter maps.
    * `SciPy` / `NumPy`: Trendline calculation and statistical operations.

## 📊 Key Insights & Findings

### 1. The "Lockdown Shock" (Structural Break)
Time-series analysis revealed a massive vertical spike in the national unemployment rate starting in **April 2020**. This structural break confirms that the crisis was driven by an external shock (Lockdown policy) rather than gradual economic decline.

### 2. Urban vs. Rural Volatility
A comparative Box-Plot analysis showed that **Urban areas** experienced significantly higher volatility and median unemployment compared to Rural areas.
* *Insight:* The lockdown disproportionately paralyzed urban-centric sectors (Retail, Transport, Manufacturing), while the rural agrarian economy remained relatively more resilient.

### 3. Regional Hotspots
The crisis was not uniform. States like **Puducherry** and **Jharkhand** recorded unemployment rates exceeding 50%, highlighting severe localized economic collapses.

### 4. The "Discouraged Worker" Effect
A negative correlation was observed between Unemployment Rate and Labour Participation Rate.
* *Insight:* As job opportunities vanished, a significant portion of the workforce exited the market entirely, effectively shrinking the labor supply.

## 📂 Project Structure
```bash
├── data/
│   ├── Unemployment in India.csv          # Raw Dataset
│   └── Unemployment_in_India_Cleaned.csv  # Processed Dataset (Cleaned)
├── visualizations/
│   ├── q1_trend_over_time.png             # Macro Trend Line Chart
│   ├── q2_state_disparity.png             # State-wise Bar Chart
│   ├── q3_urban_vs_rural.png              # Volatility Box Plot
│   └── q5_geo_scatter.html                # Interactive Plotly Map
├── Unemployment_Analysis.ipynb            # Jupyter Notebook (Main Code)
└── README.md                              # Project Documentation
