# 📊 Automatidata Project (Check "Module Project" Folder)

## Dataset  
The dataset is provided by the **New York City Taxi & Limousine Commission (TLC)**. It contains millions of taxi and rideshare trips, including variables such as trip distance, fare amount, payment type, passenger count, pickup/drop-off times, and location details.  

---

## Overview  
Automatidata, a data consulting company, was contracted by the NYC TLC to analyze their taxi trip data. The aim was to use data analysis and machine learning to understand fare dynamics and customer behavior, and to build a model that can predict fares before the ride begins.  

---

## Problem Statement  
Taxi fares in New York vary significantly based on trip distance, time of day, and payment type. The NYC TLC wanted to know:  
- How do customer payment methods (cash vs credit) affect fare amounts?  
- Can we develop a predictive model to estimate taxi fares in advance to help both drivers and passengers?  

---

## Objective  
- Conduct **Exploratory Data Analysis (EDA)** to identify trends and patterns in fares and payment methods.  
- Test statistical hypotheses to determine if there is a significant difference in fares between payment types.  
- Build and evaluate a **regression model** to predict fare amounts using distance, time, and other features.  

---

## Methods  
- **Data Preprocessing**: Cleaned and handled missing values, removed outliers, and engineered features such as trip distance bins and time categories.  
- **Exploratory Data Analysis (EDA)**: Used Python libraries (`pandas`, `matplotlib`, `seaborn`) to visualize fare distributions, trip distances, and payment types.  
- **Hypothesis Testing**: Conducted statistical tests (t-tests) to evaluate fare differences between cash and credit payments.  
- **Model Development**: Built a **multiple linear regression model** to predict fares based on distance, time of day, passenger count, and payment method.  
- **Model Evaluation**: Assessed model accuracy using R² score and RMSE to validate predictive performance.
- **Tableau Dashboards**: Designed **interactive dashboards** to present key KPIs (average fares, distance vs fare trends, payment breakdowns) in an intuitive way.  


---

## Results  
- Cash vs credit transactions showed a **statistically significant difference** in average fare amounts.  
- The regression model explained a substantial portion of fare variability (**R² ≈ 0.85**).  
- **Trip distance** and **time of day** were the strongest predictors of fare amount.  
- The model enables the TLC to predict fares **before the ride begins**, improving transparency for both drivers and passengers.  

---

## Goals Achieved  
✅ Provided actionable insights to the NYC TLC about taxi operations and payment preferences.  
✅ Identified key variables influencing fare amounts.  
✅ Developed and validated a predictive model to estimate fares in advance.  
✅ Presented results in a **clear executive summaries** for decision-makers.  
