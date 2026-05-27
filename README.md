# YouTube Video Performance Analytics Dashboard

## Project Overview

This project presents a comprehensive exploratory and trend analysis of YouTube video performance data using Python, SQL, and Power BI. The objective of the analysis is to uncover patterns in audience engagement, content growth, publishing behavior, and category-level performance across different countries and channels.

The project combines data cleaning, statistical analysis, trend analysis, and interactive dashboarding to generate actionable insights from large-scale YouTube performance data.

---

# Objectives

The analysis was designed to answer the following business and analytical questions:

* Which video categories generate the highest overall views?
* Which content categories demonstrate the strongest long-term growth?
* How do category growth trends fluctuate over time?
* Which countries exhibit the highest audience engagement quality?
* Do higher view counts translate into stronger engagement?
* Which publishing days produce the best video performance?
* Which categories consistently underperform in views and growth?
* How concentrated are total platform views among top-performing channels?

---

# Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
* **SQL**

  * Aggregations
  * CTEs
  * Window Functions
  * Ranking Functions
* **Power BI**

  * KPI Cards
  * Trend Analysis
  * Interactive Visualizations
  * Dashboard Design
* **GitHub**

  * Version Control
  * Project Documentation

---

# Dataset Features

The dataset contains video-level performance metrics, including:

* Video ID
* Channel Name
* Video Category
* Country
* Publish Date
* Views
* Engagement Score
* Video Duration
* Publishing Day
* Views
* Likes
* Dislikes

---

# Data Cleaning & Preparation

The following preprocessing steps were performed:

* Removal of duplicate records
* Handling of missing values
* Conversion of publish dates into yearly trends
* Feature engineering for:

  * Year
  * Engagement metrics
  * Growth rates
  * Publishing-day analysis
* Aggregation of category and country-level metrics

---

# Key Analytical Techniques

## 1. Year-over-Year Growth Trend Analysis

Time-series analysis was conducted to evaluate how video categories evolved across multiple years using YoY growth calculations.


## 2. Long-Term Category Growth Analysis

Long-term category performance was measured by comparing the earliest and latest yearly view totals.

## 3. Correlation Analysis

Scatter plot analysis and correlation techniques were used to evaluate the relationship between:

* Total Views
* Engagement Scores

This helped determine whether audience visibility consistently translates into audience interaction.

---

## 4. Geographic Engagement Analysis

Countries were evaluated using:

* Total Views
* Average Engagement Score
* Engagement Efficiency

This enabled normalized performance comparisons across geographic markets.

---

# Dashboard Features

## KPI Cards

* Total Platform Views
* Highest Engagement Market
* Fastest Growing Content Category
* Average Engagement Score

## Visualizations

* YoY Growth Trend Analysis of Top Categories
* Annual Platform View Volume
* Category Growth Momentum Over Time
* Geographic Share of Total Views
* Viewership vs Engagement Relationship
* Underperforming Categories by Views & Growth
* Publishing Day Performance Analysis

---

# Key Insights

* Certain video categories demonstrated strong long-term growth despite yearly volatility.
* High view counts do not always correspond to high audience engagement.
* Some countries exhibited stronger engagement efficiency despite lower overall view volumes.
* A small number of channels contributed disproportionately to total platform views.
* Publishing timing showed measurable influence on video performance.

---

# Project Structure

├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
├── visuals/
├── README.md

---

# Future Improvements

Potential future enhancements include:

* Predictive modeling for engagement forecasting
* Sentiment analysis on video metadata
* Viewer retention analysis
* Real-time dashboard integration
* Advanced clustering and segmentation techniques

---

# Author

Malcolm
Data Analytics Project Portfolio
