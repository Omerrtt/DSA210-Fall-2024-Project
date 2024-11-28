# DSA210-Fall-2024-Project

# Project Proposal: Relationship Between Sleep Duration and Step Count

## Dataset Description

This project uses health data exported from Apple Health, focusing on:
- **Sleep Data:** Daily total sleep duration (in hours), aggregated from fragmented intervals recorded by the device.
- **Step Count Data:** Daily total step count, capturing the number of steps taken throughout the day.

The datasets are preprocessed to:
- Remove outliers (e.g., extreme sleep or step values).
- Align data by date for consistent analysis.
- Ensure consistency by handling missing or invalid entries.

---

## Project Idea

The goal of this project is to explore the relationship between sleep duration and physical activity (measured by daily step count). Specifically, the project aims to answer:
- Does the amount of sleep correlate with daily physical activity levels?
- How do step counts influence sleep patterns on the following night?

By analyzing these relationships, this project seeks to provide insights into optimizing rest and activity for improved health and well-being.

---

## Project Plan

### 1. Data Preparation
- Load and clean raw data from Apple Health.
- Align sleep and step data by date.
- Handle outliers and missing values.

### 2. Exploratory Data Analysis (EDA)
- Visualize distributions of sleep duration and step counts using histograms and box plots.
- Generate time-series plots to observe trends and patterns.
- Identify anomalies or interesting data points.

### 3. Statistical Analysis
- Perform correlation analysis to measure the strength of the relationship between sleep and steps.
- Use regression modeling (e.g., linear regression) to analyze dependencies between variables.
- Explore potential lag effects (e.g., how activity influences sleep the next day).

### 4. Visualization and Reporting
- Create scatter plots, bar charts, and line graphs to communicate findings.
- Summarize results in a report highlighting key insights and recommendations.
