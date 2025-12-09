# Predicting Listing Accuracy & Fair Market Value (FMV) in Used Cars

This repository contains a machine learning project developed by **Aheli Das, Ejiroghene Akpokiro, Linghui Feng, Sushmita Behera, and Vruti Jayesh Tailor** as part of an MBAI Business Analytics final project.

The goal of this project is to:
1. Predict the **Fair Market Value (FMV)** of used cars  
2. Assess **listing accuracy** through a trust-score model  
3. Forecast **future price trends** in the U.S. used-car market  

We worked with a large-scale automotive dataset and built models for regression, classification, and forecasting, supported by extensive feature engineering and exploratory analysis.

##  Dataset Access
Due to file size limitations, the dataset is not included in this repository.  
You can download the full dataset here:
https://www.kaggle.com/datasets/tsaustin/us-used-car-sales-data

---

##  Project Overview

The dataset originally contained over 6.5 million used-car listings from dealership websites across the United States.  
After filtering and cleaning (2013–2022 models only), we worked with **5.6 million rows** and engineered additional variables such as:

- `vehicle_age`  
- `miles_per_year`  
- `segment` categories  
- `log_price` transformations  
- Outlier flags for price & mileage  

Models built include:
- **Linear Regression Models (2 versions)** for price prediction  
- **Logistic Regression Model** for listing trustworthiness  
- **Holt’s Linear Trend Forecasting** for predicting median car prices  

---

##  Files Included

- **notebooks/UsedcarPrediction_Final.ipynb**  
  Full workflow: data cleaning, feature engineering, EDA, regression models, trust-score model, and forecasting.

- **reports/BA Final Project Report.pdf**  
  Full finalized report with figures, model outputs, correlation heatmaps, trust-score visualizations, and forecasting charts.

- **data/us-dealers-used.csv**  
  Raw dataset used for analysis (U.S. portion only).  
  Contains listings from 2013–2022 with vehicle, pricing, mileage, and location details.

---

##  Tools Used

- **Python** → Pandas, NumPy, Scikit-learn, StatsModels  
- **Visualization** → Matplotlib, Seaborn  
- **Modeling** → Linear Regression, Logistic Regression, Holt’s Trend  
- **Environment** → Jupyter Notebook  

---

##  Key Steps Performed

- Loaded & cleaned raw used-car listing data  
- Removed missing values and unnecessary fields  
- Created engineered features to improve model performance  
- Performed EDA (boxplots, heatmaps, mileage trends, price trends)  
- Built and compared multiple regression models for price prediction  
- Built a trust-score classifier using logistic regression  
- Forecasted future median prices using time-series modeling  

---

##  Contributors

- **Aheli Das**  
- **Ejiroghene Akpokiro**  
- **Linghui Feng**  
- **Sushmita Behera**  
- **Vruti Jayesh Tailor**

---

##  How to Use This Repository

1. Clone or download the repository  
2. Open the Jupyter Notebook in `/notebooks`  
3. Ensure the dataset is located in `/data`  
4. Run the notebook steps in order:  
   - Data cleaning  
   - EDA  
   - Feature engineering 
   - Regression & trust models  
   - Forecasting  

---

##  License

This project is intended for **academic and educational use only**.


