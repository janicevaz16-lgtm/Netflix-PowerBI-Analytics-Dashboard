# 🎬 Netflix Content Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![Status](https://img.shields.io/badge/Project-Completed-success)
![Netflix Dashboard](images/dashboard.png)

---

## 📌 Project Overview

This project presents an interactive Netflix Content Analytics Dashboard developed using Microsoft Power BI.

The dashboard provides business insights into Netflix's content library by analyzing:

- Movies vs TV Shows
- Rating Distribution
- Content Release Trends
- Country-wise Content Distribution
- Interactive Filtering
- KPI Summary

The objective is to demonstrate professional Business Intelligence, Data Cleaning, Data Modeling, and Dashboard Development skills.

---

## 📊 Dashboard Preview
<img width="1432" height="802" alt="image" src="https://github.com/user-attachments/assets/510e4c6e-ea54-4859-87e0-5e6fc7b15cdf" />

```
![Netflix Dashboard](images/dashboard.png)
```



---

## 🚀 Business Questions Answered

✔ How many Movies and TV Shows are available?

✔ Which countries produce the highest amount of Netflix content?

✔ Which ratings dominate Netflix?

✔ How has Netflix content grown over the years?

✔ What percentage of content consists of Movies vs TV Shows?

---

## 📂 Dataset

Dataset Source

Netflix Titles Dataset

Source:

Kaggle

---

## 🛠 Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- CSV Dataset

---

## ⚙ Data Cleaning

The following transformations were performed using Power Query:

- Removed duplicate records
- Removed null values
- Corrected data types
- Standardized column names
- Cleaned country values
- Created calculated measures

---

## 📈 Dashboard Features

### KPI Cards

- Total Titles
- Movies
- TV Shows
- Countries

---

### Interactive Visualizations

- Donut Chart
- Bar Chart
- Line Chart
- Rating Distribution
- Country Distribution

---

### Slicers

- Country
- Rating
- Type

---

## 📊 DAX Measures

Movie Count

```DAX
Movie Count =
CALCULATE(
COUNT(Netflix[show_id]),
Netflix[type]="Movie"
)
```


- Total Titles
- Total Movies
- Total TV Shows
- Movie Percentage
- TV Show Percentage
- Total Countries
- Total Titles = COUNTROWS('Netflix')
---
Data Model 

## 🗂 Data Model

This dashboard uses a cleaned Netflix dataset imported into Power BI.

Relationships were established where necessary, and calculations were created using DAX measures.

TV Show Count

```DAX
TV Show Count =
CALCULATE(
COUNT(Netflix[show_id]),
Netflix[type]="TV Show"
)
```

---

Average Rating

```DAX
Average Rating =
AVERAGE(Netflix[vote_average])
```

---

## 📌 Key Insights

• Movies represent the majority of Netflix content.

• TV-MA is the most common rating.

• United States contributes the highest number of titles.

• Netflix content increased rapidly after 2015.

---

## 📷 Dashboard Screenshots

### Home Dashboard



---

### Rating Analysis



---

### Country Analysis



---
## 🚀 Future Improvements

- Add Genre Analysis
- Add Director Analysis
- Add Actor Analysis
- Publish Dashboard to Power BI Service
- Add Drill-through Pages
  
## 🧠 Skills Demonstrated

✔ ETL

✔ Power Query

✔ Data Cleaning

✔ DAX

✔ KPI Design

✔ Data Modeling

✔ Business Intelligence

✔ Dashboard Design

✔ Git & GitHub
## 📁 Repository Structure

```
Netflix-PowerBI-Analytics-Dashboard
│
├── Dashboard
├── Dataset
├── Documentation
├── Images
└── README.md
```

---
Dataset Statistics

Total Records : 8,807

Columns : 12

Countries : 120+

Movies : 6,131

TV Shows : 2,676

Workflow Diagram

CSV Dataset
      ↓
Power Query
      ↓
Data Cleaning
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Visualizations
      ↓
Interactive Dashboard

## 📄 License

MIT License

## 👩‍💻 Author

Janice Cyril Vaz

Power BI | SQL | Python | Data Analytics

GitHub: https://github.com/janicevaz16-lgtm/Netflix-PowerBI-Analytics-Dashboard/edit/main/README.md

LinkedIn: https://www.linkedin.com/in/janice-vaz-b07884272/

---

## 🎯 Conclusion

This project demonstrates end-to-end Business Intelligence development using Microsoft Power BI.

The dashboard transforms raw Netflix data into actionable insights through data cleaning, modeling, DAX calculations, and interactive visualizations.

It showcases practical skills required for Data Analyst and Business Intelligence roles.

Please consider giving this repository a ⭐# Netflix-PowerBI-Analytics-Dashboard
Interactive Netflix Content Analytics Dashboard built using Power BI, Power Query, and DAX.
