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
- [Power BI Dashboard](./Humure Enock (27394).pbix)
- Data/uber.csv
- [Python ](./uber-dataset.ipynb)

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
- **Cleaning & Transformation**: Handled using Python in [`uber-dataset.ipynb`](./uber-dataset.ipynb)  
- **Analysis Tool**: Power BI for dynamic visual dashboards and python, visual studio

🔧 **Steps followed**:
- Removed missing values & duplicates  
- Filtered outliers using the IQR method  
- Parsed timestamps into useful columns (hour, day, month, etc.)  
- Exported clean datasets for Power BI

**Data Cleaning Output:**  
importing values:<img width="1275" height="724" alt="import libralies" src="https://github.com/user-attachments/assets/597c0875-61f8-49ea-83bf-730e2ca4b770" />


Cleaned Output: <img width="1330" height="672" alt="cleaned data" src="https://github.com/user-attachments/assets/8244a67b-00b2-424c-8769-a9d60dd9510f" />

handleling data: <img width="1279" height="676" alt="handlelilng data" src="https://github.com/user-attachments/assets/753c6305-da1b-4fc9-96ba-8b87bbbd1ec9" />

datacleaning:<img width="2583" height="1285" alt="combination of import libralies" src="https://github.com/user-attachments/assets/83a3a138-827d-445d-b3fb-88413d80431c" />


---

## 📊 Exploratory Data Analysis (EDA)

Performed in Python using `pandas`, `matplotlib`, and `seaborn`.

- Distribution of fare amounts  
- Passenger count trends  
- Daily/weekly ride frequencies  
- Correlation between fare and trip distance  
- Mapping of pickup locations

📸 **EDA Snapshots:**  
EDA output:<img width="1262" height="574" alt="eda out put" src="https://github.com/user-attachments/assets/759549de-7a42-48e0-a9f5-3a9295b67759" />
<img width="1198" height="672" alt="eda" src="https://github.com/user-attachments/assets/23fd5f98-b8ed-4a1c-a528-95d97282c347" />


Histogram: <img width="1213" height="623" alt="fare amount graph eda" src="https://github.com/user-attachments/assets/651af486-20ec-4abd-af6b-8c19905010cb" />

eda visualize data:  <img width="1282" height="706" alt="eda graph of correration" src="https://github.com/user-attachments/assets/354aa984-56f9-44ae-84c6-f54204748dbd" />

<img width="1273" height="735" alt="correration" src="https://github.com/user-attachments/assets/7c686abf-a5d2-4acc-b9dd-a93171cc7502" />

Heatmap:<img width="1288" height="715" alt="fare vs distance eda" src="https://github.com/user-attachments/assets/e987e935-3cbb-4013-a833-152fa738bd98" />
<img width="1275" height="700" alt="fare amount day vs hours graph eda" src="https://github.com/user-attachments/assets/874cd43d-883e-44f8-8231-80ebe770a79a" />


combination of eda graph: <img width="3971" height="1619" alt="eda combination" src="https://github.com/user-attachments/assets/a2494e84-d3c0-4d82-9d88-f8f88b48fb92" />


---

## 🛠️ Feature Engineering

To support advanced analysis, new features were derived:

- `hour`, `day`, `month` from `pickup_datetime`  
- `weekday` (e.g., Monday, Friday)  
- `season` (Spring, Summer, etc.)  
- `time_of_day` (Morning, Evening, Night)
    📁cleaned data:[`cleaned data`](./Data/uber_cleaned.csv)
    📁uberdata:[`uber data](./Data/uber_cleaned.csv)
    📂 Final dataset: [`uber_enhanced.csv`](./Data/uber_enhanced.csv)


---

## 📈 Data Analysis & Dashboard Development

Using Power BI, an interactive dashboard was built with:

- Fare distribution charts (histogram, boxplot)  
- Time trends: hourly, daily, monthly rides  
- Geographical heatmaps (pickup areas)  
- Interactive filters: time ranges, fare bins, etc.

📸 **Dashboard Previews:**  
Fare Graphs:<img width="1320" height="729" alt="power BI fare amount" src="https://github.com/user-attachments/assets/3f0e7b1f-65ac-449b-ae75-21cb11cca223" />

Trip Insight: <img width="1235" height="736" alt="power bi uber trip insights " src="https://github.com/user-attachments/assets/a1de9c76-9466-4fdd-82ef-dc46e55dc454" />

Season Insights : <img width="918" height="762" alt="season insight" src="https://github.com/user-attachments/assets/18c6879d-ab26-4d23-932f-d32c564c9838" />

uber valiable:  <img width="1274" height="737" alt="power bi weather valiables" src="https://github.com/user-attachments/assets/e9515ee9-ed8a-4659-ba02-cb45d8686a5b" />

power bi combination photo: <img width="3804" height="1617" alt="power BI combination" src="https://github.com/user-attachments/assets/a27f96f1-d66b-4f33-b437-e86158a42abd" />


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
[link of power bi on the drive](./https://drive.google.com/file/d/1UR0Ox1NvyKYodCBCCaMvzl95ze7KqkYK/view?usp=sharing)
link of my work folder: https://drive.google.com/drive/folders/150Gl6mQrmDSo75AqDsjvzIREg2vSYp8U

📸 Additional Visuals:  
![ EDA](./<img width="3971" height="1619" alt="eda combination" src="https://github.com/user-attachments/assets/a105b87f-0965-4663-9f4b-9132baa906b3" />
)  
![power BI](./<img width="3804" height="1617" alt="power BI combination" src="https://github.com/user-attachments/assets/c4693569-30d2-40fa-afd3-0b847bcdb1ea" />
)

---

## 🙏 Appreciation

> _"A great teacher doesn’t just deliver answers — they inspire the pursuit of knowledge."_

I wish to express my deep appreciation to my lecturer **Maniraguha Eric**,  
who has been more than an instructor in this course.

Thank you, sir, for guiding us not only through tools and techniques, making us work hard for our own  
but also through the mindset of a data analyst — to question, explore, and communicate clearly.

"*great mentors help us tell it right.”*
