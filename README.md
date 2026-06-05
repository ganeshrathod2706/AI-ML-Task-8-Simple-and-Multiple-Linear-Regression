# Task 8 - Simple & Multiple Linear Regression

## Objective

To understand and implement Simple Linear Regression and Multiple Linear Regression using the Advertising Dataset and evaluate model performance using MSE and R² Score.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook / VS Code

---

## Dataset Used

Advertising Dataset

Features:
- TV
- Radio
- Newspaper

Target:
- Sales

---

## Tasks Performed

### 1. Data Loading
- Loaded the Advertising dataset using Pandas.

### 2. Data Understanding
- Checked dataset structure using:
  - head()
  - info()
  - describe()

### 3. Missing Value Analysis
- Verified that no missing values were present.

### 4. Correlation Analysis
- Generated Heatmap to identify relationships between features and target.

### 5. Simple Linear Regression
- Used TV as the independent feature.
- Predicted Sales.

### 6. Multiple Linear Regression
- Used TV, Radio, and Newspaper features.
- Predicted Sales.

### 7. Train-Test Split
- Applied 80:20 train-test split.

### 8. Model Evaluation
- Mean Squared Error (MSE)
- R² Score

### 9. Coefficient Analysis
- Analyzed feature importance using regression coefficients.

---

## Results

### Multiple Linear Regression

MSE: 3.174

R² Score: 0.899

### Feature Importance

TV = 0.0447

Radio = 0.1892

Newspaper = 0.0028

Radio advertising had the highest impact on Sales.

---

## Conclusion

The Multiple Linear Regression model achieved an R² Score of approximately 0.90, indicating excellent predictive performance. Among all advertising channels, Radio had the strongest influence on Sales while Newspaper had minimal impact.

---

## Learning Outcome

- Simple Linear Regression
- Multiple Linear Regression
- Train-Test Split
- Model Prediction
- MSE Evaluation
- R² Evaluation
- Regression Coefficients Interpretation