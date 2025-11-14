# FoodTrends-Customer-Satisfaction-Analytics-Dashboard

# 🍽️ AI-Powered Insights on Food Quality, Delivery Performance & User Satisfaction
### A Power BI + Python Data Analytics Project

---

## 📘 Overview

**FoodTrends** is a data analytics project built to analyze customer satisfaction, food quality, delivery efficiency, and service experience using **Power BI** and **Python**.  
The dashboard transforms raw survey data into meaningful business insights through **DAX calculations, KPIs, interactive charts, and AI-driven analytics**.

This project was developed as part of an **Infosys Data Analytics Internship**, showcasing end-to-end BI development — from data cleaning to dashboard storytelling.

---

## 🎯 Project Objectives

- Analyze factors influencing customer satisfaction  
- Measure food quality, freshness, quantity, and politeness  
- Understand delivery performance and its impact on ratings  
- Build interactive dashboards to support data-driven decisions  
- Convert categorical survey responses (Agree, Neutral, Disagree) into numerical scores for KPI calculation  

---

## 📂 Dataset Description

The dataset contains customer feedback on:

- Food Quality Score  
- Freshness Score  
- Quantity Score  
- Delivery Time Score  
- Politeness Score  
- Satisfaction Index  
- Age, Gender, Location, Meal Type, Platform  
- Delivery Efficiency (Early, On-Time, Late)
---

## 🧮 Key KPI Calculations (DAX)

All textual feedback like *Agree / Neutral / Disagree* was converted into numerical values and averaged.

```DAX
Avg_Satisfaction = AVERAGE(Data[Satisfaction Index])

Avg_Freshness = AVERAGE(Data[Food Freshness Score])

Avg_DeliveryEfficiency = AVERAGE(Data[Less Delivery time Score])


## 📌 Dashboard Pages

### 📄 Page 1 – Overview & Key Metrics
- Avg. Satisfaction Index  
- Delivery Efficiency Gauge  
- Food Quality Score  
- Customer Profile Snapshot  
- Platform-wise Ratings  

---

### 📄 Page 2 – Delivery Performance
- Delivery Time Distribution  
- Early vs On-Time vs Late Deliveries  
- Delivery Impact on Satisfaction  
- Delivery Zone Map  

---

### 📄 Page 3 – Customer Demographics
- Age Group Satisfaction  
- Gender-wise Ratings  
- Location Heatmap  
- Meal Type Preferences  

---

### 📄 Page 4 – Food Quality Analytics
- Freshness vs Satisfaction  
- Quantity vs Satisfaction  
- Taste vs Quality Matrix  
- Politeness Impact  

---

### 📄 Page 5 – Quality & Satisfaction Metrics  
**Visuals Included:**
- KPI Cards  
- Avg Satisfaction  
- Avg Freshness  
- Avg Delivery Efficiency  
- Highly Satisfied Users  
- Food Quality Gauge  
- Satisfaction by Age Group (Bar Chart)  
- Politeness vs Delivery Time (Line Chart)  
- Freshness vs Satisfaction (Scatter Plot)  
- Quantity vs Satisfaction (Combined Chart)  
- Attribute-wise Performance Table  

---

## 📊 Visualizations Used
- KPI Cards  
- Gauges  
- Bar & Column Charts  
- Line Charts  
- Scatter Plots  
- Pie/Donut Charts  
- Heatmaps  
- Tables with Data Bars  
- Geographical Maps  
- Slicers & Filters  

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard development & DAX modeling |
| **Python (Pandas, NumPy)** | Data cleaning & preprocessing |
| **Excel** | Data preparation |
| **DAX** | KPI creation & measure calculations |
| **Power Query** | Data transformation |

---

## 🚀 Project Workflow

### 1. Data Cleaning (Python + Power Query)
- Removing duplicates  
- Handling missing values  
- Converting categorical survey responses into numeric values  

### 2. Data Modeling (Power BI)
- Creating relationships  
- Developing DAX measures  

### 3. Dashboard Development
- Designing visuals  
- Creating KPIs & gauges  
- Formatting & report storytelling  

### 4. Insight Extraction
- Identifying satisfaction drivers  
- Analyzing delivery performance  
- Understanding customer behavior  

---

## 💡 Key Insights Generated
- Faster deliveries strongly increase politeness perception and satisfaction  
- Freshness and quantity of food are major drivers of happiness  
- Younger customers report slightly higher satisfaction  
- Around **46%** of customers are highly satisfied — indicating strong overall service performance  
- Outer regions show lower satisfaction — identifying improvement areas  

