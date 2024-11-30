# Steel Industry Energy Consumption Classification

## Overview

This project focuses on analyzing the Steel Industry Energy Consumption dataset to predict the load type using machine learning classification models. It involves exploratory data analysis, data preprocessing, model training, and evaluation.

## Dataset

The dataset used in this project is the "Steel Industry Energy Consumption" dataset, sourced from Kaggle. 

**Dataset Columns:**

- **date:** Date in format dd/mm/yyyy
- **Usage_kWh:** Total energy consumption in kWh
- **Lagging_Reactive_Power_kVarh:** Lagging reactive power in kVarh
- **Leading_Reactive_Power_kVarh:** Leading reactive power in kVarh
- **CO2(tCO2):** CO2 emissions in tonnes
- **Lagging_Power_Factor:** Lagging power factor
- **Leading_Power_Factor:** Leading power factor
- **NSM:** Number of seconds from midnight
- **WeekStatus:** Weekend or weekday
- **Day_of_week:** Day of the week
- **Load_Type:** Type of load (Light, Medium, Maximum)


## Project Workflow

1. **Data Import**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing**
4. **Feature Engineering**
5. **Model Selection**
6. **Hyperparameter Tuning**
7. **Model Evaluation**

## Results

The Random Forest classifier achieved the highest accuracy in predicting the load type of the Steel Industry Energy Consumption dataset.

Correlation Heatmap  
![Correlation Heatmap](/pic1.png)  

Confusion Matrix  
![Confusion Matrix](/pic2.png)  
