# Spotify-Data-Analysis


# 🎧 Spotify Listening Analytics Dashboard (Power BI)

## 📌 Project Overview

Spotify Listening Analytics is an interactive Power BI dashboard designed to analyze personal Spotify listening behavior across albums, artists, tracks, time, and platforms.

The dashboard transforms raw Spotify streaming history into **actionable insights** using advanced **DAX measures, KPI logic, and time-based analysis**, enabling users to understand *how, when, and what* they listen to.

This project demonstrates business-grade analytics design, strong DAX proficiency, and data storytelling aligned with real-world BI use cases.


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


### 🔹 Weekday vs Weekend Insights

Donut charts compare listening patterns:

* Albums played (Weekday vs Weekend)
* Artists played (Weekday vs Weekend)
* Tracks played (Weekday vs Weekend)

### 🔹 Top Content Analysis

* **Top 5 Albums** by total plays
* **Top 5 Artists** by total plays
* **Top 5 Tracks** by total plays

<img src="sportifypix1.png" width = "900">


### 🔹 Listening Time Heatmap

A heatmap showing listening hours vs days of the week, highlighting:

* Peak listening hours
* Low-activity periods
* Daily listening patterns

This visualization combines time intelligence and conditional formatting for intuitive insights.


### 🔹 Listening Behavior Scatter Analysis

Scatter plot analyzing:

* **Average listening time (minutes)** vs **track frequency**
* Interactive thresholds for identifying outliers
* Separation of high-engagement vs casual listening behavior

<img src="Sportifypix2.png" width = "900">

## 🧠 DAX & Analytics Techniques Used

* Time intelligence (`DATEADD`, Year comparisons)
* Context control (`ALLSELECTED`, slicer-aware measures)
* YoY growth calculations
* KPI text measures with conditional logic
* Defensive handling of BLANK values
* Ranking and Top-N analysis
* Conditional formatting for insight emphasis

## ⚠️ Disclaimer

This project is for **educational and portfolio purposes only** and is **not affiliated with or endorsed by Spotify**.
