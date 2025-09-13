# SCT Internship Task 1

**Intern:** Mayank Chaudhary  
**Intern ID:** SCT/AUG25/5568  
**Email:** chaudharymayank8928@gmail.com  
**LinkedIn:** [www.linkedin.com/in/-mayank-chaudhary](https://www.linkedin.com/in/-mayank-chaudhary)  
**Company:** SkillCraft Technology

---

## Project Overview

This repository contains the solution for SCT Internship Task 1, which involves predicting house prices using linear regression. The workflow includes:

- Loading and exploring the dataset (`train.csv`, `test.csv`)
- Data cleaning and feature engineering (e.g., handling missing values, creating total bathroom feature)
- Model training and evaluation using scikit-learn's LinearRegression
- Visualizing model performance
- Generating predictions for the test set
- Creating a submission file (`submission.csv`)

## File Structure

- `linear_reg_House_price.ipynb`: Jupyter notebook with all code, analysis, and results.
- `train.csv`: Training dataset containing house features and sale prices.
- `test.csv`: Test dataset for prediction.
- `submission.csv`: Output file with predicted house prices for the test set.

## How to Run

1. Open `linear_reg_House_price.ipynb` in Jupyter Notebook or VS Code.
2. Run all cells sequentially to reproduce the results and generate predictions.
3. The final predictions will be saved in `submission.csv`.

## Key Steps in the Notebook

- **Data Loading:** Reads the training and test datasets using pandas.
- **Preprocessing:** Handles missing values and creates new features (e.g., total bathrooms).
- **Feature Selection:** Uses `GrLivArea`, `BedroomAbvGr`, and `Totalbath` as input features.
- **Model Training:** Splits the data, trains a linear regression model, and evaluates performance using R² and RMSE.
- **Visualization:** Plots actual vs predicted prices for both training and testing sets.
- **Prediction:** Applies the trained model to the test set and saves results for submission.
- **Example Predictions:** Demonstrates predictions for sample house configurations.

## Contact

For any queries, reach out via email or LinkedIn above.

---
