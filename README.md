# 🎬 Netflix Content Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

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

```
(Add dashboard screenshot here)
```

![Dashboard](Images/Dashboard.png)

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

---

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

(Add Screenshot)

---

### Rating Analysis

(Add Screenshot)

---

### Country Analysis

(Add Screenshot)

---

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

## 👩‍💻 Author

Janice Cyril Vaz

Power BI | SQL | Python | Data Analytics

GitHub

LinkedIn

---

## ⭐ If you found this project useful

Please consider giving this repository a ⭐# Netflix-PowerBI-Analytics-Dashboard
Interactive Netflix Content Analytics Dashboard built using Power BI, Power Query, and DAX.
