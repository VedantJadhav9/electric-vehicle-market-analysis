# 🚗 Electric Vehicle Market Analysis (Python)

## Project Overview
This project focuses on analyzing a large-scale **Electric Vehicle (EV) dataset** to extract insights related to pricing, range, battery capacity, energy efficiency, and manufacturer comparison. The analysis supports **customer decision-making** as well as **strategic insights for EV manufacturers**.

---

## Problem Statement
With the rapid growth of electric vehicles, customers and manufacturers face challenges in understanding which EVs provide the best balance between **price, range, battery capacity, and performance**. Raw EV data does not directly answer key questions related to affordability, efficiency, and comparative performance across manufacturers.

The goal is to analyze EV market data and convert it into actionable insights that support **purchase decisions, product optimization, and market strategy**.

---

## Business Objectives
- Identify EVs that offer the best value based on **budget and driving range**
- Compare manufacturers based on **battery capacity and performance**
- Analyze **energy consumption patterns** to identify efficiency trends
- Understand the relationship between **battery capacity and vehicle range**
- Build a **recommendation system** to suggest optimal EVs based on user requirements
- Perform statistical testing to compare performance metrics across brands

---

## Dataset Overview
- **Total Records:** Lakh+ rows  
- **Total Features:** 22 columns  
- **Key Attributes:**  
  - Price (PLN)  
  - Range (WLTP)  
  - Battery Capacity (kWh)  
  - Energy Consumption (kWh/100 km)  
  - Engine Power (KM)  
  - Manufacturer (Make)  

---

## Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- SciPy (Statistical Testing)  

---

## Key Analysis Tasks Performed

### Task 1: Budget & Range-Based Filtering
- Filtered EVs with **price ≤ 350,000 PLN** and **range ≥ 400 km**
- Identified **12 EVs** meeting customer constraints
- Grouped results by manufacturer
- Calculated **average battery capacity** per manufacturer

**Key Insight:**  
Audi showed the highest average battery capacity within the filtered segment, while Tesla and Volkswagen offered the highest number of affordable long-range EVs.

---

### Task 2: Energy Consumption Outlier Detection
- Analyzed mean energy consumption using **boxplot visualization**
- Identified **no significant outliers**, indicating consistent energy usage across EV models

---

### Task 3: Battery Capacity vs Range Analysis
- Performed correlation analysis using scatter and regression plots
- Observed a **positive correlation** between battery capacity and driving range

**Key Insight:**  
Higher battery capacity generally results in longer range, but efficiency varies across manufacturers.

---

### Task 4: EV Recommendation System
- Built a **Python-based EV recommender class**
- Recommended top EVs based on:
  - Budget
  - Minimum range
  - Minimum battery capacity
- Returned **top 3 optimal EVs** per user input

**Business Value:**  
Helps customers make faster, data-driven purchase decisions.

---

### Task 5: Statistical Comparison (Hypothesis Testing)
- Conducted **Welch’s t-test** to compare engine power between Tesla and Audi
- Result showed **no statistically significant difference** in engine power

**Business Insight:**  
Manufacturers should differentiate on features like range, charging speed, and efficiency rather than engine power alone.

---

## Key Insights Summary
- Affordable long-range EVs are dominated by Tesla and Volkswagen
- Battery capacity strongly influences range but does not guarantee efficiency
- Energy consumption is consistent across most EVs
- Statistical analysis shows similar engine power across premium brands

---

## Business Value Delivered
- Supports customers in selecting EVs based on real constraints
- Helps manufacturers identify competitive gaps
- Demonstrates data-driven product and pricing insights
- Combines analysis, visualization, statistics, and recommendation logic

---

## How to Use
1. Clone this repository  
2. Open the Python scripts or notebook  
3. Update input parameters (budget, range, battery capacity)  
4. Run the analysis to view results and recommendations  

---

## Conclusion
This project demonstrates strong skills in **data analysis, visualization, statistical testing, and business-driven insights** using Python. It reflects real-world analytical thinking applied to the EV market.

