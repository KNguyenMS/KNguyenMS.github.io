# Heart Disease Prediction Project
This project explores how logistic regression can be used to predict the likelihood of heart disease based on health-related risk factors.

## Objective
- Identify key risk factors and assess prediction accuracy.

## Key Findings
- The strongest predictors of heart disease were:
  - **Age**
  - **High cholesterol**
  - **High blood pressure**
  - **Smoking status**
  - **Diabetes**
- Logistic regression achieved **84% accuracy** and an **F1-score of 0.78**.

## Methods
- **Data Preprocessing:** Handling missing values, encoding categorical variables, and resampling.
- **Modeling Approach:** Logistic Regression for binary classification.
- **Feature Selection:** Identifying key predictors based on correlation analysis.
- **Performance Evaluation:** Precision, recall, F1-score, and ROC-AUC.

## How to Recreate the Analysis
Follow these steps to run the model and reproduce the results:

1. **Download the dataset:**  
   - File: [`heart_disease_health_indicators_BRFSS2015.csv`](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset)  
   - Place the CSV file in the same directory as the Jupyter Notebook.

2. **Run the Jupyter Notebook (`.ipynb` file):**  
   - Open `Project 3 Heart Disease.ipynb` in Jupyter Notebook or Google Colab.
   - Execute the code **cell by cell** to perform preprocessing, feature selection, and model training.

3. **Review the Results:**  
   - The notebook will generate summary statistics, model performance metrics, and visualizations.
   - Examine the ROC curve, confusion matrix, and feature importance plots.
  

For more details, visit the [Heart Disease Prediction Project Repository](https://github.com/KNguyenMS/KNguyenMS.github.io/tree/main/Heart-Disease-Prediction).
