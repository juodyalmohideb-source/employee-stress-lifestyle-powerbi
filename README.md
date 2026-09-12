# Analyzing Employee Stress Levels and Lifestyle Factors Using Power BI

## Overview

This project presents an interactive Business Intelligence solution developed using Power BI to analyze employee stress levels and explore their relationship with workplace conditions, mental health, sleep, physical activity, and other lifestyle factors.

The project integrates two datasets to provide a broader view of employee well-being. Interactive dashboards, KPIs, filters, and data visualizations are used to explore patterns and identify factors associated with different stress levels.

## Objectives

- Analyze employee stress and burnout levels.
- Explore the relationship between workplace factors and stress.
- Examine sleep duration and sleep quality across different occupations and stress levels.
- Analyze the relationship between physical activity, sleep, and stress.
- Provide interactive dashboards that support data exploration and clear presentation of insights.

## Datasets

The project uses two datasets:

### Tech Mental Health and Burnout

This dataset contains workplace and mental health information, including work mode, work hours, overtime, job satisfaction, manager support, work-life balance, sleep hours, physical activity, stress, anxiety, depression, and burnout indicators.

### Sleep Health and Lifestyle

This dataset contains sleep, lifestyle, and health-related information, including occupation, sleep duration, quality of sleep, physical activity, stress level, BMI category, heart rate, blood pressure, and daily steps.

The datasets were prepared and transformed using Power Query before being used in the Power BI data model.

## Data Preparation

The data preparation process included:

- Removing duplicate records.
- Filtering selected categorical values.
- Changing data types.
- Renaming selected columns.
- Rounding selected numerical values.
- Creating stress categories: Low, Moderate, and High.
- Creating sleep categories: Good Sleep, Moderate Sleep, and Poor Sleep.

A `Stress_Dim` dimension table was also created in Power BI to support the organization and analysis of stress categories.

## Dashboard

### Dashboard 1 – Workplace & Mental Health

The first dashboard focuses on workplace and mental health factors.

It includes KPIs and visualizations for:

- Average Stress Level
- Average Burnout Score
- Average Anxiety Score
- Stress distribution
- Stress levels by gender
- Overtime hours across stress levels
- Burnout levels across work modes
- Burnout and sleep duration by stress level

Interactive slicers are provided for **Stress Category** and **Work Mode**.

### Dashboard 2 – Lifestyle & Health

The second dashboard focuses on lifestyle and health-related factors.

It includes:

- Average Sleep Duration
- Average Stress Level
- Average Heart Rate
- Average Sleep Duration by Occupation
- Physical Activity, Sleep, and Stress Relationship
- Stress Level vs Sleep Quality
- Sleep Duration across BMI Categories
- BMI Category Distribution

Interactive slicers are provided for **Stress Category**, **BMI Category**, and **Occupation**.

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Interactive Data Visualization

## Key Insights

The analysis highlights patterns between employee stress and factors such as overtime, work mode, burnout, sleep duration, sleep quality, physical activity, occupation, and BMI category.

The dashboards indicate that lower physical activity and poorer sleep tend to be associated with higher stress levels within the analyzed data.

These results describe patterns and associations in the data and should not be interpreted as causal relationships.

## Project Files

- `Project_BI_Dashboard_Final.pbix` – Power BI dashboard.
- `data/` – Contains the datasets used in the project.
- `images/` – Contains dashboard preview images.

## Conclusion

This project demonstrates how Power BI can be used to integrate and analyze employee workplace, mental health, sleep, and lifestyle data.

The interactive dashboards provide a clear way to explore employee stress and well-being patterns using data-driven visualizations and Business Intelligence techniques.
