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

1. **Data Import:** Importing the dataset using the `kagglehub` library.
2. **Exploratory Data Analysis (EDA):** Exploring the dataset using descriptive statistics, visualizations, and correlation analysis to understand the data distribution, relationships between variables, and potential outliers.
3. **Data Preprocessing:** Transforming categorical features into numerical representations using label encoding.
4. **Feature Engineering:** Creating new features or transforming existing ones to improve model performance. In this case, dropped `date` feature.
5. **Model Selection:** Training and evaluating various classification models, including Logistic Regression, KNN, SVM, Decision Tree, Naive Bayes, and Random Forest.
6. **Hyperparameter Tuning:** Using Grid Search with Cross-Validation to find the optimal hyperparameters for the selected model (Random Forest).
7. **Model Evaluation:** Evaluating the best model using metrics such as accuracy, confusion matrix, and classification report.

## Results

The Random Forest classifier achieved the highest accuracy in predicting the load type of the Steel Industry Energy Consumption dataset.

## Conclusion

This project demonstrates the application of machine learning classification models for predicting load types in the steel industry. Further improvements could be explored by incorporating additional features, experimenting with different models, or tuning hyperparameters.


## Usage

1. Install the required libraries
2. Run the Jupyter Notebook or Python script containing the project code.
3. The notebook contains detailed comments and explanations for each step of the workflow.
4. To reproduce the results, download the Steel Industry Energy Consumption dataset from Kaggle and replace the file path in the code accordingly.


## Libraries Used

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `plotly`

## Contributing

Contributions to this project are welcome. Please feel free to submit pull requests for bug fixes, enhancements, or new features.

## License

This project is licensed under the [MIT License](LICENSE).
