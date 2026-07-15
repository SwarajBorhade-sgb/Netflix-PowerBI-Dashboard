# 🎬 Netflix Content Analytics Dashboard | Power BI

An interactive Power BI dashboard analyzing Netflix's content library using **Power Query**, **DAX**, and **data visualization** to uncover business insights and content trends.

---

## 📌 Project Overview

This project analyzes Netflix's content library, providing insights into movies, TV shows, genres, ratings, countries, and release trends through an interactive Power BI dashboard.

### Key Objectives
- Analyze Netflix's content distribution
- Compare Movies vs TV Shows
- Identify top content-producing countries
- Explore genre and rating trends
- Visualize yearly content growth
- Build an interactive dashboard for business insights

---

## 📊 Dashboard Preview

> **Add your dashboard screenshot here**

![Dashboard Preview](<img width="981" height="557" alt="Netflix png" src="https://github.com/user-attachments/assets/3da6cd9e-e16e-4222-81e8-ab74a67606bd" />
)

---

## 📈 Key Performance Indicators (KPIs)

- 🎬 Total Titles
- 🎥 Total Movies
- 📺 Total TV Shows
- 🌍 Total Countries
- 🎭 Total Genres
- ⭐ Average Runtime
- 📅 Content Added by Year

---

## 📊 Dashboard Features

- Executive Summary
- Movies vs TV Shows Analysis
- Country-wise Content Distribution
- Genre Analysis
- Content Rating Analysis
- Yearly Release Trends
- Interactive Filters & Slicers

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling

---

## 📂 Repository Structure

```
Netflix-PowerBI-Dashboard
│
├── Dashboard Images
│   └── Dashboard.png
│
├── Dataset
│   └── Netflix Dataset.xlsx
│
├── Netflix Dashboard.pbix
│
└── README.md
```

---

## 📊 Sample DAX Measures

```DAX
Total Titles = COUNTROWS(Netflix)

Movies =
CALCULATE(
    COUNTROWS(Netflix),
    Netflix[type] = "Movie"
)

TV Shows =
CALCULATE(
    COUNTROWS(Netflix),
    Netflix[type] = "TV Show"
)
```

---

## 💡 Business Insights

- Movies make up the majority of Netflix's content library.
- The United States has the highest number of titles.
- Most content has been added after 2015.
- Drama and International Movies are among the most popular genres.
- TV-MA is the most common content rating.

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- Power BI
- DAX
- Power Query
- Dashboard Design
- Business Intelligence
- KPI Development
- Data Visualization

---

## 📷 Dashboard

Replace the placeholder image with your own dashboard screenshot.

---



---

## ⭐ If you found this project helpful, consider giving it a Star!
