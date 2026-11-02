# Car Price Prediction

## Project Overview
This project predicts car prices using Machine Learning techniques. It analyzes different car features and estimates their selling prices.

## Dataset
- Dataset: Car Price Prediction
- Total Records: 205
- Total Columns: 26
- Target Variable: `price`

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Workflow
1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Linear Regression Model
8. Random Forest Model
9. Model Evaluation and Comparison
10. Saving the Trained Model

## Machine Learning Models
- Linear Regression
- Random Forest Regressor

## Model Evaluation
The models were evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

**Best Model:** Random Forest Regressor

**R² Score:** 0.9566 (95.66%)

## Project Files
- `Car_Price_Prediction.ipynb` – Complete Jupyter Notebook
- `CarPrice_Assignment.csv` – Dataset
- `Data Dictionary - carprices.xlsx` – Dataset description
- `car_price_model.pkl` – Saved trained model
- `requirements.txt` – Required Python libraries
- `.gitignore` – Files excluded from Git

## Conclusion
The project demonstrates how machine learning can predict car prices using different vehicle features. The Random Forest model achieved an R² score of 95.66% on the test dataset.