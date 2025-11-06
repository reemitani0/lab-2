# lab-2
This lab applies an end-to-end data science process using Python to analyze household electricity consumption. It focuses on predicting Global Active Power through data cleaning, time-series conversion, and visualization. To do so it uses Pandas, Seaborn, and Matplotlib.
# ⚡ Household Power Consumption Analysis — Lab 2 (Part B)

## 📘 Overview
This lab focuses on analyzing time-series household energy data using **Python**.  
The goal is to understand power usage behavior and prepare the dataset for predictive modeling.

---

## ⚙️ Tools and Libraries
- Python 3  
- Pandas  
- NumPy  
- Seaborn & Matplotlib  
- Scikit-learn  

---

## 🧩 Steps Performed
1. **Data Loading** — Imported dataset and examined its structure.  
2. **Data Cleaning** — Removed missing values using forward/backward fill and rolling median.  
3. **DateTime Conversion** — Combined date and time columns for time-series analysis.  
4. **Exploratory Data Analysis (EDA)** — Visualized trends using line, histogram, and box plots.  
5. **Resampling & Aggregation** — Calculated daily averages for energy trends.  

---

## 📊 Results (Insert Screenshots Below)
- Line Plot: Global Active Power Over Time  
  > ![Line Plot](path/to/lineplot.png)

- Histogram: Distribution of Global Active Power  
  > ![Histogram](path/to/histogram.png)

- Boxplot: Voltage Variation  
  > ![Boxplot](path/to/boxplot.png)

- Daily Average Trend  
  > ![Trend](path/to/trend.png)

---

## 🧠 Insights
- Energy consumption varies significantly throughout the day.  
- Voltage remains relatively stable, but small drops align with peak usage hours.  
- Cleaning and time-indexing improve the accuracy of trend detection.

---

## 🏁 Conclusion
This lab illustrates the complete data preprocessing and visualization process for time-series energy data, preparing it for advanced modeling and forecasting tasks.
