# Regression Models — Linear & Logistic Regression

Implementation of Linear Regression and Logistic Regression using an external dataset (CSV), with MSE and R-Squared Score evaluation.

---

## Overview

| Model | Task | Target |
|---|---|---|
| Linear Regression | Predict House Price | Continuous (Price) |
| Logistic Regression | Classify High / Low Price | Binary (1 = High, 0 = Low) |

---

## Dataset

- **Source:** External CSV file (house_price.csv)
- **Rows:** 200
- **Columns:** Area_sqft, Bedrooms, House_Age, Distance_to_City_km, Has_Garage, Price

---

## Evaluation Metrics

### Linear Regression
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-Squared Score (R2)

### Logistic Regression
- Mean Squared Error (MSE)
- R-Squared Score (R2)
- Accuracy Score
- Classification Report (Precision, Recall, F1-Score)

---

## Project Structure

```
regression-models-ml/
├── regression_analysis.ipynb   # Main notebook
├── house_price.csv             # External dataset
└── README.md                   # Project documentation
```

---

## How to Run

1. Open `regression_analysis.ipynb` in Google Colab
2. Run all cells
3. When prompted in Step 2, upload `house_price.csv` from your device
4. All outputs, plots and metrics will be generated automatically

---

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Author

HEMANTHSELVA A K — Data Science Intern, Sourcesys Technologies
