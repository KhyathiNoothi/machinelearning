# Student Performance Prediction using Random Forest

## Overview

This project uses a Random Forest Regression model to predict student academic performance based on various factors such as study habits, attendance, parental involvement, and other educational attributes.

The model is trained using a student performance dataset and saved as a serialized `.pkl` file for future predictions.

---

## Project Structure

```text
Student-Performance-Prediction/
│
├── RandomForest.ipynb          # Model training and evaluation notebook
├── student_rf_model.pkl        # Trained Random Forest model
├── README.md                   # Project documentation
└── Dataset files               # Student performance dataset
```

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection
- Random Forest model training
- Model evaluation using performance metrics
- Model serialization using Pickle
- Future prediction support

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Pickle
- Jupyter Notebook

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Train-Test Split
6. Random Forest Model Training
7. Model Evaluation
8. Model Saving using Pickle

---

## Model Used

### Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Advantages:
- Handles non-linear relationships
- Robust against overfitting
- Works well on tabular datasets
- Provides feature importance

---

## Evaluation Metrics

The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## How to Run

### Clone the Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Run the Notebook

Open:

```text
RandomForest.ipynb
```

using Jupyter Notebook or VS Code and execute the cells.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Feature importance visualization
- Deployment using Flask
- Interactive web interface
- Comparison with XGBoost and other ensemble models

---

