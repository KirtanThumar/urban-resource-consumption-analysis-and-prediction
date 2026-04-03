# Urban Resource Consumption Analysis and Prediction

## Overview

This project focuses on analyzing how urban resources like energy, water, and waste are consumed over time, using Mumbai as a case study.

The idea behind this project was simple — cities are growing fast, and resource usage is increasing, but this data is rarely used properly for prediction. So I tried to analyze past data and see if we can predict future demand using basic machine learning models.

---

## What this project does

* Cleans and combines multiple real-world datasets
* Analyzes trends in energy, water, and waste consumption
* Studies how population growth affects resource usage
* Builds machine learning models to predict future demand

---

## Dataset

The project uses publicly available datasets related to Mumbai, including:

* Energy consumption
* Population growth
* Water consumption
* Solid waste generation

Most of the data comes from government sources like data.gov.in, CPCB, CWC, and related reports.

---

## Approach

### 1. Data Preparation

All datasets were cleaned and merged based on year. Some columns required formatting and handling missing values.

### 2. Exploratory Data Analysis

I used graphs and plots to understand how each resource changes over time and how they relate to population.

### 3. Machine Learning

Initially, I used only "year" as input, but later improved the model by adding "population" as another feature.

Steps followed:

* First predict future population using regression
* Then use year + predicted population to forecast resource consumption

Models used:

* Linear Regression
* Polynomial Regression

---

## Key Observations

* Resource consumption is steadily increasing
* Population has a strong impact on all resources
* Polynomial regression gave better results than linear regression
* Multi-feature input (year + population) improved predictions

---

## How to run

1. Download or clone the repository
2. Make sure all CSV files are in the same folder
3. Open the notebook in Jupyter or Google Colab
4. Run all cells

---

## Limitations

* Dataset is small and mostly linear
* External factors like climate, policy, etc. are not included
* Predictions are based on historical trends

---

## Future Improvements

* Use larger and more detailed datasets
* Try advanced models like Random Forest
* Build a dashboard for visualization
* Extend the project to multiple cities

---

## About

This project was developed as part of my internship work. The goal was to apply data analysis and machine learning to a real-world problem and understand how data can support better planning.
