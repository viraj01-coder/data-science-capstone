# data-science-capstone
# Winning Space Race with Data Science 🚀

## Project Overview

This project is part of the **IBM Data Science Professional Certificate** on Coursera.

The objective of this project is to analyze SpaceX launch data and build machine learning models to predict whether the **Falcon 9 first stage will land successfully**.

Successful rocket landing and reuse significantly reduces the cost of space missions.

---

## Business Problem

SpaceX launches cost millions of dollars.
Landing and reusing the Falcon 9 first stage is critical to reducing launch costs.

This project aims to:

* Predict whether a Falcon 9 rocket will land successfully
* Identify the key factors affecting landing success
* Analyze historical launch data

---

## Data Sources

The dataset was collected from:

1. **SpaceX REST API**
2. **Wikipedia Web Scraping**

The data includes information such as:

* Launch Site
* Payload Mass
* Orbit Type
* Booster Version
* Landing Outcome

---

## Project Methodology

The project followed these steps:

1. Data Collection
2. Data Wrangling
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Interactive Visual Analytics
6. Machine Learning Model Building
7. Model Evaluation

---

## Tools and Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SQL
* Folium
* Plotly Dash

---

## Exploratory Data Analysis

Several visualizations were created to understand the data:

* Scatter plots for payload vs success
* Bar charts for orbit success rate
* Line charts for yearly landing success trends

Key findings:

* Launch success increased significantly after **2015**
* **Orbit type and launch site** strongly influence landing success
* Payload mass also affects landing outcomes

---

## Interactive Visualizations

### Folium Map

An interactive map was created to visualize launch sites and landing success.

Features:

* Launch site markers
* Success / Failure color coding
* Distance analysis to nearby infrastructure

### Plotly Dash Dashboard

An interactive dashboard was built with:

* Launch site dropdown filter
* Payload mass range slider
* Pie charts for success ratio
* Scatter plots for payload vs landing success

---

## Machine Learning Models

Four classification models were trained and evaluated:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed using **GridSearchCV**.

---

## Model Results

All models achieved the same test accuracy:

**Accuracy: 83.33%**

This shows strong predictive performance for landing outcomes.

---

## Key Findings

* SpaceX landing success improved significantly over time
* Orbit type is a strong predictor of landing success
* Launch site also influences success probability
* Machine learning models can effectively predict landing outcomes

---

## Author

Virajbhai Vinubhai Mavani

IBM Data Science Professional Certificate
Coursera
