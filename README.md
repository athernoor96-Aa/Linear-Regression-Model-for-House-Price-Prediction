# Linear-Regression-Model-for-House-Price-Prediction

This project implements a complete machine learning pipeline using **Linear Regression** to predict house prices based on various features such as area, number of bedrooms, bathrooms, parking availability, and other property attributes.


## Project Overview

The objective of this project is to build an interpretable regression model that predicts house prices using structured housing data. The project follows standard machine learning practices including data exploration, preprocessing, model training, evaluation, and interpretation.


## Dataset

- The dataset contains both **numerical** and **categorical** features.
- Target variable: **price**
- Source: Public housing dataset used for academic purposes.

## Exploratory Data Analysis (EDA)

The following EDA techniques were applied:
- Dataset inspection (shape, data types, missing values)
- Pair plots to analyze relationships and outliers
- Correlation heatmap to identify important features and multicollinearity

## Machine Learning Pipeline

The project follows these steps:

1. Data Loading and Inspection  
2. Exploratory Data Analysis (EDA)  
3. Feature Selection and Target Definition  
4. Train–Test Split  
5. Data Preprocessing  
   - Scaling numerical features using `StandardScaler`
   - Encoding categorical features using `OneHotEncoder`
6. Model Training using `LinearRegression`
7. Model Evaluation using:
   - Mean Squared Error (MSE)
   - R² Score
8. Model Interpretation using regression coefficients

## Model Evaluation Metrics

- **Mean Squared Error (MSE)**: Measures average squared prediction error  
- **R² Score**: Measures the proportion of variance explained by the model

## Model Interpretation

Linear regression coefficients were analyzed to understand how each feature impacts house prices. This improves transparency and helps identify key price-driving factors.

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter / Google Colab  

## How to Run the Project

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Run all cells sequentially
3. Review model outputs and visualizations

## Output

- Trained Linear Regression model
- Evaluation metrics
- Visualizations
- Interpretable coefficients
- HTML export of the notebook (for submission)

## Conclusion

This project demonstrates a complete and interpretable linear regression workflow for house price prediction. Proper data preprocessing, feature selection, and evaluation ensure reliable and meaningful predictions.
