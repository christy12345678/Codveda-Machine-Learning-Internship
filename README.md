# Codveda Machine Learning Internship - Level 1 Tasks

This repository contains my completed and optimized projects for Level 1 of my Machine Learning Internship at Codveda Technologies. 

## 📋 Task Overview
* **Task 1: Data Preprocessing** – Cleaned, structured, and normalized an unformatted housing prediction dataset using `pandas` and `scikit-learn`.
* **Task 2: Linear Regression Model** – Built, evaluated, and optimized a predictive regression pipeline to forecast market values.

## 🛠️ Technical Execution & Optimization
1. **Data Formatting:** Handled a raw dataset delivered without header rows. Applied explicit 14-attribute mapping to parse space-separated data into distinct numerical columns.
2. **Data Split & Scaling:** Implemented an 80/20 train-test split using `train_test_split` (random_state=42) and normalized numerical features using `StandardScaler`.
3. **Outlier Filtering:** Identified artificial target price constraints capped at $50,000. Removing these noise points significantly reduced overall model error.
4. **Feature Engineering:** Applied logarithmic transformations (`np.log1p`) to highly skewed indicators (like `LSTAT`) to capture non-linear, curved data trends.

## 📊 Performance Results
* **Baseline Linear Model:** R-squared (R²) = **0.67** | Mean Squared Error (MSE) = **24.29**
* **Optimized Upgraded Model:** R-squared (R²) = **0.80** | Mean Squared Error (MSE) = **10.26**

*The optimized preprocessing workflow cut prediction error more than in half and pushed model accuracy to a robust 80%!*
