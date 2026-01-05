# Sportify-Data-Analysis


# 🎧 Spotify Listening Analytics Dashboard (Power BI)

## 📌 Project Overview

Spotify Listening Analytics is an interactive Power BI dashboard designed to analyze personal Spotify listening behavior across albums, artists, tracks, time, and platforms.

The dashboard transforms raw Spotify streaming history into **actionable insights** using advanced **DAX measures, KPI logic, and time-based analysis**, enabling users to understand *how, when, and what* they listen to.

This project demonstrates business-grade analytics design, strong DAX proficiency, and data storytelling aligned with real-world BI use cases.

---

## 🎯 Key Objectives

* Analyze listening trends across albums, artists, and tracks
* Track year-over-year (YoY) performance
* Understand listening behavior by time of day and day of week
* Compare usage across platforms and playback behaviors
* Build slicer-driven, insight-focused KPIs


## 📊 Dashboard Pages & Features

### 🔹 Overview KPIs

Top-level metrics summarizing listening activity:

* Total Albums Played
* Total Artists Played
* Total Tracks Played
* Dynamic Latest Year vs Previous Year (YoY) KPIs with percentage change


### 🔹 Trend Analysis (Over Time)

* Line charts showing
* Visual identification of growth, peaks, and declines
* Time-intelligent calculations using DAX

### 🔹 Year-over-Year (YoY) Performance

* Comparison of Latest Year (LY) vs Previous Year (PY)
* Percentage change calculations
* Defensive DAX logic to handle missing or incomplete periods
* Clean KPI text formatting for executive-style reporting


### 🔹 Platform & Playback Analysis

Interactive slicers allow filtering by:

* Platform (Android, iOS, Mac, Web Player, Windows, Cast to Device)
* **Shuffle status**
* **Skip behavior**


---

### 🔹 Weekday vs Weekend Insights

Donut charts compare listening patterns:

* Albums played (Weekday vs Weekend)
* Artists played (Weekday vs Weekend)
* Tracks played (Weekday vs Weekend)

Helps identify **habitual vs leisure listening behavior**.

---

### 🔹 Top Content Analysis

* **Top 5 Albums** by total plays
* **Top 5 Artists** by total plays
* **Top 5 Tracks** by total plays

Optimized for ranking clarity and fast comparison.

img sportifypix1.png

### 🔹 Listening Time Heatmap

A heatmap showing **listening hours vs days of the week**, highlighting:

* Peak listening hours
* Low-activity periods
* Daily listening patterns

This visualization combines **time intelligence and conditional formatting** for intuitive insights.

---

### 🔹 Listening Behavior Scatter Analysis

Scatter plot analyzing:

* **Average listening time (minutes)** vs **track frequency**
* Interactive thresholds for identifying outliers
* Separation of high-engagement vs casual listening behavior

Used to explore correlations between listening duration and frequency.

---

## 🧠 DAX & Analytics Techniques Used

* Time intelligence (`DATEADD`, Year comparisons)
* Context control (`ALLSELECTED`, slicer-aware measures)
* YoY growth calculations
* KPI text measures with conditional logic
* Defensive handling of BLANK values
* Ranking and Top-N analysis
* Conditional formatting for insight emphasis

---

## 🛠️ Tech Stack

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* Spotify streaming history dataset
* Custom Date table
* Interactive slicers and drill-through design

---

## 📂 Repository Contents

```
Sportify.pbix        # Power BI dashboard file
/Images              # Dashboard screenshots
README.md            # Project documentation
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. Use slicers to explore platforms, years, and behaviors
4. Review KPIs, trends, and insights dynamically

---

## 📈 Business Value Demonstrated

* Behavioral analytics and trend detection
* KPI-driven storytelling
* Time-based performance comparison
* Dashboard design aligned with executive and analyst use cases

---

## ⚠️ Disclaimer

This project is for **educational and portfolio purposes only** and is **not affiliated with or endorsed by Spotify**.

---

## 👤 Author

**Kayode Gabriel Olusanya**
Business Intelligence & Data Analyst
📍 Canada
🔗 GitHub: [https://github.com/yourusername](https://github.com/yourusername)

---

### 🔥 Optional Enhancements (Highly Recommended)

If you want, I can:

* Rewrite this for **ATS-optimized portfolio wording**
* Add a **“DAX Highlights” section with code snippets**
* Help you choose the **best screenshots for GitHub**
* Align it directly with **Canadian BI / Data Analyst job descriptions**

Just tell me 👍
