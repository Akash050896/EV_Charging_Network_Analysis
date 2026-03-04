# 🚗 EV Charging Network Performance & Revenue Optimization

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-EV%20Analytics-green)

------------------------------------------------------------------------

## 📌 Project Overview

The **EV Charging Network Performance & Revenue Optimization Project**
analyzes electric vehicle charging session data to evaluate network
performance, identify revenue drivers, and uncover demand patterns.

Using Python-based exploratory data analysis (EDA), this project
provides insights that help EV charging operators improve infrastructure
planning, optimize pricing strategies, and enhance operational
efficiency.

------------------------------------------------------------------------

# 📑 Table of Contents

## 📌 Project Overview

-   [Project Overview](#-project-overview)

## 🎯 Business Understanding

-   [Business Problem](#-business-problem)
-   [Project Objectives](#-project-objectives)
-   [Project Highlights](#-project-highlights)

## 📊 Data Preparation & KPIs

-   [Dataset Information](#-dataset-information)
-   [Data Cleaning](#-data-cleaning)
-   [Feature Engineering](#-feature-engineering)
-   [KPIs Developed](#-kpis-developed)

## 📊 Analysis & Insights

-   [Revenue Analysis](#-revenue-analysis)
-   [Session Analysis](#-session-analysis)
-   [Time-Based Analysis](#-time-based-analysis)
-   [Correlation Analysis](#-correlation-analysis)
-   [Key Insights](#-key-insights)

## 🧾 Conclusion

-   [Conclusion](#-conclusion)

## 🛠 Technical Details

-   [Tools & Technologies](#️-tools--technologies)
-   [How to Run the Project](#-how-to-run-the-project)
-   [Project Structure](#-project-structure)

## 👤 Author

-   [Author](#-author)

------------------------------------------------------------------------

# 🎯 Business Problem

EV charging operators must answer key operational questions:

-   Which cities generate the highest revenue?
-   Which charger types are most profitable?
-   When does peak demand occur?
-   What factors drive revenue?
-   How can pricing and infrastructure be optimized?

Without performance monitoring, operators may face:

-   Underutilized infrastructure
-   Missed revenue opportunities
-   Poor peak demand management
-   Inefficient investment decisions

------------------------------------------------------------------------

# 🎯 Project Objectives

-   Evaluate overall network performance
-   Identify top revenue-generating cities
-   Compare charger type efficiency
-   Analyze customer behavior patterns
-   Detect peak charging hours
-   Support revenue optimization decisions

------------------------------------------------------------------------

# ⭐ Project Highlights

-   Analyzed **25,000 charging sessions**
-   Generated comprehensive **network-level KPIs**
-   Identified **Mumbai as highest revenue city**
-   Detected **4 PM as peak charging hour**
-   Found very strong correlation (0.97) between revenue and energy
    consumption
-   Provided strategic business recommendations

------------------------------------------------------------------------

# 📊 Dataset Information

**File:** `EV_Charging_Analytics_Dataset.csv` 

**Total Records:** 25,000

### Key Columns:

| Column                    | Description                      |
|---------------------------|----------------------------------|
| City                      | Charging location                |
| Charger_Type              | Type of charger (DC Fast / Slow) |
| User_Type                 | Member / Non-Member              |
| Payment_Mode              | Payment method used              |
| Energy_Consumed_kWh       | Energy delivered per session     |
| Charging_Duration_Minutes | Duration of session              |
| Revenue                   | Revenue generated                |
| Session_Date              | Charging date and time           |

------------------------------------------------------------------------

# 🧹 Data Cleaning

-   Checked for missing values
-   Removed duplicate records
-   Converted `Session_Date` to datetime format
-   Verified numeric column consistency

------------------------------------------------------------------------

# 🛠 Feature Engineering

Extracted time-based features:

-   Year
-   Month
-   Hour
-   Day of Week

Created business metric:

-   Revenue per kWh

These transformations enabled time-based and efficiency analysis.

------------------------------------------------------------------------

# 📊 KPIs Developed

-   **Total Revenue**
-   **Total Energy Delivered**
-   **Total Charging Sessions**
-   **Average Charging Duration**
-   **Average Revenue per Session**
-   **Revenue per kWh**

These KPIs measure financial performance and operational efficiency.

------------------------------------------------------------------------

# 📊 Revenue Analysis

### Revenue by City

-   Mumbai generates the highest revenue.
-   Hyderabad and Bangalore follow closely.

### Revenue by Charger Type

-   DC Fast chargers generate the highest revenue.

### Revenue by User Type

-   Members contribute the majority of revenue.

### Revenue by Payment Mode

-   UPI generates the highest revenue.

------------------------------------------------------------------------

# 🔌 Session Analysis

### Sessions by City

-   Mumbai records the highest session volume.

### Sessions by Charger Type

-   Slow chargers have the highest number of sessions.

### Sessions by User Type

-   Members dominate total sessions.

### Sessions by Payment Mode

-   UPI is the most frequently used payment method.

------------------------------------------------------------------------

# 📈 Time-Based Analysis

### Monthly Revenue Trend

-   December records the highest monthly revenue.

### Peak Charging Hour

-   4 PM is the peak charging hour.

------------------------------------------------------------------------

# 🔗 Correlation Analysis

-   Revenue & Energy Correlation: **0.97 (Very Strong)**
-   Revenue & Duration Correlation: **0.91 (Strong)**

This confirms that revenue is primarily driven by energy consumption.

------------------------------------------------------------------------

# 🔎 Key Insights

-   Mumbai is the strongest performing city.
-   DC Fast chargers are more revenue-efficient.
-   Membership program drives the majority of business.
-   UPI dominates payment behavior.
-   Charging demand peaks at 4 PM.
-   Revenue strongly depends on energy consumption.

------------------------------------------------------------------------

# 🚀 Business Recommendations

-   Expand DC Fast chargers in high-revenue cities.
-   Implement dynamic pricing during peak hours.
-   Strengthen membership benefits.
-   Optimize digital payment systems.
-   Prepare operational scaling for seasonal demand spikes.

------------------------------------------------------------------------

# 🧾 Conclusion

This analysis demonstrates that EV charging revenue is influenced by:

-   Geographic demand concentration
-   Charger type efficiency
-   Loyal customer behavior
-   Energy-based pricing model
-   Time-of-day usage patterns

By leveraging these insights, EV charging operators can optimize pricing
strategies, strategically expand infrastructure, and improve overall
network profitability.

------------------------------------------------------------------------

# 🛠️ Tools & Technologies

### 🐍 Programming Language

-   **Python** --- Core language used for data analysis and
    visualization

### 📊 Data Analysis & Manipulation

-   **Pandas** --- Data cleaning, transformation, aggregation, and KPI
    calculation

### 📈 Data Visualization

-   **Matplotlib** --- Bar charts, line plots, pie charts, and trend
    analysis
-   **Seaborn** --- Statistical visualization and correlation heatmap

### 💻 Development Environment

-   **Jupyter Notebook** --- Interactive analysis and visualization

### 🗂️ Repository Management

-   **GitHub** --- Version control and project documentation

------------------------------------------------------------------------

# 📥 How to Run the Project

1.  Clone the repository
2.  Install dependencies:

``` bash
pip install pandas matplotlib seaborn
```

3.  Open Jupyter Notebook:

``` bash
jupyter notebook
```

4.  Run all cells in the notebook

------------------------------------------------------------------------

# 📂 Project Repository Structure

    EV_Charging_Network_Analysis
    │
    ├── Dataset
    │   └── EV_Charging_Analytics_Dataset.csv
    │
    ├── Notebook
    │   └── EV_Charging_Network_Performance_Optimization.ipynb
    │
    └── README.md

------------------------------------------------------------------------

# 👤 Author

**Akash Kindre**

Aspiring Data Analyst with hands-on experience in **Power BI, SQL, Excel & Python** specializing in **data visualization, KPI reporting, and dashboard development**. Skilled in **data cleaning, data modeling, and business performance analysis**, with a strong focus on transforming raw data into actionable insights to support data-driven decision-making.
