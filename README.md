# 🏠 House Price Prediction using Linear Regression

## Overview

This project implements a **Simple Linear Regression** model to predict median house prices using the **California Housing Dataset** from Scikit-learn.
The goal is to understand the relationship between the average number of rooms in a house and its median value.

The project demonstrates the complete Machine Learning workflow including data preprocessing, model training, prediction, evaluation, and visualization.

---

## Dataset

* Source: Scikit-learn (fetch_california_housing)
* Target Variable: `MEDV` (Median House Value)
* Feature Used: `AveRooms` (Average number of rooms per household)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## Machine Learning Steps

1. Load the California housing dataset
2. Convert dataset into a Pandas DataFrame
3. Check for missing values
4. Select feature (`AveRooms`) and target (`MEDV`)
5. Split data into training and testing sets (80:20)
6. Train the Linear Regression model
7. Predict house prices on test data
8. Evaluate model performance using:

   * Mean Squared Error (MSE)
   * R² Score
9. Visualize regression line and actual data points

---

## Model Evaluation

The model performance is measured using:

* **Mean Squared Error (MSE)** – measures prediction error
* **R² Score** – indicates how well the model explains variance in house prices

---

## Output

The program:

* Displays model coefficients and intercept
* Shows predicted vs actual house prices
* Plots regression line with actual data points

---

## How to Run the Project

1. Install required libraries:

```
pip install pandas numpy scikit-learn matplotlib
```

2. Run the Python file:

```
python house_price_prediction.py
```

---

## Project Structure

```
House-Price-Prediction/
│── house_price_prediction.py
│── README.md
```

---

## Learning Outcomes

* Understanding of Linear Regression
* Data preprocessing techniques
* Model training and testing
* Evaluation metrics (MSE and R²)
* Data visualization in Machine Learning

---

## Future Improvements

* Use multiple features instead of one
* Apply Polynomial Regression
* Perform feature scaling
* Compare with other regression algorithms (Random Forest, SVR)
