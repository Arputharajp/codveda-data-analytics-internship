# Level 2 – Regression Analysis (House Prediction)

## Objective
To build and evaluate a regression model that predicts house prices based on multiple input features, using a cleaned housing dataset.

---

## Dataset
House Prediction Dataset  
The dataset contains numerical features related to housing characteristics and a target variable representing house prices (`MEDV`).

---

## Task Performed: Regression Analysis

### Steps Involved
- Loaded the cleaned dataset prepared in Level 1
- Separated independent features (X) and target variable (y)
- Split the data into training and testing sets
- Trained a Linear Regression model using scikit-learn
- Evaluated the model using performance metrics
- Interpreted model coefficients to understand feature impact

---

## Model Evaluation
The model was evaluated using:
- **R-squared (R²)** to measure explained variance
- **Mean Squared Error (MSE)** to measure prediction error
- **Root Mean Squared Error (RMSE)** for error magnitude

The regression model demonstrated reasonable predictive performance on unseen data.

---

## Model Interpretation
- Features such as the number of rooms (RM) showed a strong positive influence on house prices.
- Features like LSTAT showed a negative relationship with house prices.
- Coefficients helped identify which variables most significantly affect predictions.

---

## Tools & Libraries
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## Outcome
A regression model was successfully built and evaluated, providing insights into the factors influencing house prices and serving as a foundation for predictive modeling.

