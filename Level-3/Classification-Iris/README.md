# Level 3 – Predictive Modeling (Classification)

## Objective
To build and evaluate multiple classification models for predicting flower species using the Iris dataset, and to compare their performance using standard evaluation metrics.

---

## Dataset
Iris Dataset  
The dataset contains numerical features such as sepal and petal dimensions, along with a categorical target variable representing flower species.

---

## Task Performed: Classification Modeling

### Steps Involved
- Loaded and inspected the Iris dataset
- Separated features and target variable
- Split the data into training and testing sets
- Applied feature scaling for models that require normalized input
- Trained multiple classification models:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- Evaluated model performance using accuracy, precision, recall, and F1-score
- Performed hyperparameter tuning on the best-performing model using GridSearchCV

---

## Model Evaluation
Model performance was evaluated using:
- **Accuracy** to measure overall correctness
- **Precision** to measure correctness of positive predictions
- **Recall** to measure the ability to identify all relevant instances
- **F1-score** to balance precision and recall

Random Forest achieved the best overall performance among the evaluated models.

---

## Tools & Libraries
- Python
- pandas
- numpy
- scikit-learn

---

## Outcome
Multiple classification models were successfully trained and evaluated.  
The Random Forest model demonstrated superior performance, and hyperparameter tuning further improved its robustness and reliability.

