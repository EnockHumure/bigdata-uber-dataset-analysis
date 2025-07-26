# bigdata-uber-dataset-analysis
assignment of uber fares  

## Uber Fares Dataset Analysis – INSY 8413

**Course:** Introduction to Big Data Analytics  
**Instructor:** Maniraguha Eric  
**Assignment Date:** July 23, 2025  
**Name:** Humure Enock  
**ID:** 27394  
**Group:** A

---

## 📑 Table of Contents

1. [Project Structure](#-project-structure)  
2. [Introduction](#-introduction)  
3. [Methodology](#-methodology)  
4. [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)  
5. [Feature Engineering](#-feature-engineering)  
6. [Dashboard Development & Analysis](#-data-analysis--dashboard-development)  
7. [Key Insights](#-key-insights)  
8. [Main Findings](#-summary-of-main-findings)    
9. [Dashboard Overview](#-power-bi-dashboard-overview)  
10. [Appreciation](#-appreciation)

---

## 📁 Project Structure

This project is organized as follows:

**Important Files**:
- [Power BI Dashboard](./uber-analysis-bigdata/Humure Enock (27394).pbix)
- [Python Notebook](./uber-analysis-bigdata/uber-dataset.ipynb)
- 📂 [Cleaned Dataset](./uber-analysis-bigdata/Data/uber_enhanced.csv)

---

## 📌 Introduction

This project explores ride behavior, pricing trends, and location-based insights using Uber Fares data.  
The analysis combines **Python for data wrangling and exploration** with **Power BI for visual storytelling**.

**our Main goals:**
- Identify peak times, fare behavior, and high-demand zones  
- Visualize patterns using interactive dashboards  
- Offer actionable recommendations using data insights

---

## 🧪 Methodology

To ensure high-quality analysis, the following approach was used:

- **Data Source**: [Kaggle Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)  
- **Cleaning & Transformation**: Handled using Python in [`uber-dataset.ipynb`](./uber-analysis-bigdata/uber-dataset.ipynb)  
- **Analysis Tool**: Power BI for dynamic visual dashboards and python, visual studio

🔧 **Steps followed**:
- Removed missing values & duplicates  
- Filtered outliers using the IQR method  
- Parsed timestamps into useful columns (hour, day, month, etc.)  
- Exported clean datasets for Power BI

**Data Cleaning Output:**  
![importing values](./uber-analysis-bigdata/screenshots/importing the libraries.png) 
![Cleaned Output](./uber-analysis-bigdata/screenshots/output of cleaning data.png)  
![handleling data](./uber-analysis-bigdata/screenshots/extract data from eda.png)
![datacleaning](./uber-analysis-bigdata/screenshots/2.dataCleaning.png)

---

## 📊 Exploratory Data Analysis (EDA)

Performed in Python using `pandas`, `matplotlib`, and `seaborn`.

- Distribution of fare amounts  
- Passenger count trends  
- Daily/weekly ride frequencies  
- Correlation between fare and trip distance  
- Mapping of pickup locations

📸 **EDA Snapshots:**  
![EDA output](./uber-analysis-bigdata/screenshots/eda output.png)  
![Histogram](./uber-analysis-bigdata/screenshots/eda data for histogram and---.png)  
![eda visualize data](./uber-analysis-bigdata/screenshots/eda for preparing visualize data.png)  
![Heatmap](./uber-analysis-bigdata/screenshots/eda heatmap.png)  
![combination of eda graph](./uber-analysis-bigdata/screenshots/combination of eda.png)

---

## 🛠️ Feature Engineering

To support advanced analysis, new features were derived:

- `hour`, `day`, `month` from `pickup_datetime`  
- `weekday` (e.g., Monday, Friday)  
- `season` (Spring, Summer, etc.)  
- `time_of_day` (Morning, Evening, Night)
    📁cleaned data:[`cleaned data`](./uber-analysis-bigdata/Data/uber_cleaned.csv)
    📁uberdata:[`uber data](./uber-analysis-bigdata/Data/uber.csv)
    📂 Final dataset: [`uber_enhanced.csv`](./uber-analysis-bigdata/Data/uber_enhanced.csv)


---

## 📈 Data Analysis & Dashboard Development

Using Power BI, an interactive dashboard was built with:

- Fare distribution charts (histogram, boxplot)  
- Time trends: hourly, daily, monthly rides  
- Geographical heatmaps (pickup areas)  
- Interactive filters: time ranges, fare bins, etc.

📸 **Dashboard Previews:**  
![Fare Graphs](./uber-analysis-bigdata/screenshots/power Bi fare graphs.png)  
![Trip Insight](./uber-analysis-bigdata/screenshots/power BI uber trip insight.png)  
![Season Insights](./uber-analysis-bigdata/screenshots/power Bi Season insights.png)  
![uber valiable](./uber-analysis-bigdata/screenshots/power Bi weathere valiable.png)  
![power bi combination photo](./uber-analysis-bigdata/screenshots/power Bi combination.png)

---

## 🔍 Key Insights

- Most fares range between **$5–$15**  
- **Fridays (6–7 PM)** see the highest ride volumes  
- Business areas and airports yield **higher fares**  
- **Spring** has the highest ride counts; **Fall** the highest average fare  
- Fare increases consistently with **trip distance**

---

## 🧾 Summary of Main Findings

- **Fare pricing** is closely linked to trip distance and time of day  
- **Peak ride times** match commuting hours and weekends  
- **Geographic hotspots** highlight opportunities for driver allocation  
- **Seasonal fluctuations** affect ride demand and pricing behavior

---

## 📊 Power BI Dashboard Overview

The dashboard was designed to help users interactively explore the Uber dataset.

**Includes:**
- Fare Distribution: Histogram, Boxplot  
- Time Trends: Hourly, Daily, Monthly  
- Pickup Location Heatmaps  
- Filters by Time of Day, Fare Range, Day of Week  

📄 [Download Dashboard](./uber-analysis-bigdata/Humure Enock (27394).pbix)
[link of power bi on the drive](./https://drive.google.com/file/d/1UR0Ox1NvyKYodCBCCaMvzl95ze7KqkYK/view?usp=drive_link)

📸 Additional Visuals:  
![ EDA](./uber-analysis-bigdata/screenshots/combination of eda.png)  
![power BI](./uber-analysis-bigdata/screenshots/power Bi combination.png)

---

## 🙏 Appreciation

> _"A great teacher doesn’t just deliver answers — they inspire the pursuit of knowledge."_

I wish to express my deep appreciation to my lecturer **Maniraguha Eric**,  
who has been more than an instructor in this course.

Thank you, sir, for guiding us not only through tools and techniques, making us work hard for our own  
but also through the mindset of a data analyst — to question, explore, and communicate clearly.

"*great mentors help us tell it right.”*
