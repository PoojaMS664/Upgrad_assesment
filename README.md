# Linear Regression from Scratch – Housing Prices

This project implements **Linear Regression from scratch** using Python and NumPy, without relying on machine learning libraries such as Scikit-learn or Statsmodels. The objective is to understand how linear regression works internally, including data preprocessing, model training using gradient descent, and performance evaluation.

## Project Structure

* **Part 1 – Data Preprocessing**

  * Data loading from CSV
  * Handling missing values
  * Encoding categorical variables
  * Train-test split (no information leakage)
  * Feature scaling and bias addition

* **Part 2 – Linear Model**

  * Custom prediction function using matrix multiplication

* **Part 3 – Training**

  * Mean Squared Error (MSE) loss
  * Gradient Descent implementation
  * Loss tracking and visualization

* **Part 4 – Evaluation**

  * Model testing on unseen data
  * MSE and RMSE calculation
  * Actual vs Predicted analysis

## Learning Objective

To understand the internal working of linear regression, including:

* How model coefficients affect predictions
* How gradient descent optimizes weights
* How preprocessing impacts model performance

## Requirements

* Python 3.x
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

## Usage

1. Clone the repository
2. Place the housing dataset (`housing.csv`) in the project folder
3. Open the Jupyter Notebook and run all cells

## Output

* Trained linear regression model
* Loss curve visualization
* Test performance metrics (MSE/RMSE)

---

This project is intended for educational purposes to demonstrate the fundamentals of machine learning without using high-level ML libraries.