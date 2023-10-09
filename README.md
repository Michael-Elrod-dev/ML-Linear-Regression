# ML-Linear-Regression

## Introduction
This project aims to create a linear regression model to predict the winning times of the 100m race based on historical data. The project uses various polynomial degree models to find the best fit for the given data. The primary objective is to determine which model (linear, quadratic, cubic, or fourth-degree) best predicts the winning times.

## Setup & Installation

1. **Prerequisites**
   - Python (version 3.x recommended)
   - Required Libraries: `matplotlib`, `tabulate`, `numpy`

2. **Installation**
   - Clone this repository or download the source code.
   - Navigate to the project directory.
   - Install the required libraries using pip:
     ```bash
     pip install matplotlib tabulate numpy
     ```

3. **Running the Program**
   - Ensure you have the `W100MTimes.txt` data file in the project directory.
   - Run the script:
     ```bash
     python linear_regression_100m.py
     ```

## Usage

1. **K-Fold Cross Validation**
   - When you run the program, it will first perform a 5-fold cross-validation on the data to evaluate the performance of the different polynomial models. The training and testing errors for each fold and their averages will be displayed in a table format.

2. **Error Visualization**
   - The program will then display a plot showcasing the training and testing errors against the polynomial degree. This helps in visually determining which polynomial degree might be the best fit for the data.

3. **Predictions**
   - The program will compute the final weights using the entire dataset for the linear model (or whichever model is deemed best).
   - It will then predict the winning times for the years 1980, 2000, and 2024 using the chosen model.

## Conclusion
This project provides a hands-on approach to linear regression and model evaluation. It offers insights into how different polynomial degrees can affect the performance and prediction capabilities of a regression model.

## Note
This is a basic implementation, and there are various enhancements and optimizations possible, like regularization, to further improve the model's performance.
