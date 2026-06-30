# House Price Prediction using Linear Regression

## Overview
This project implements a **Linear Regression** model to predict house prices based on selected house features. The model is trained using the training dataset and predicts house prices for the test dataset.

## Objective
To build a machine learning model that estimates the sale price of a house using:
- Living Area (Square Footage)
- Number of Bedrooms
- Number of Bathrooms

## Dataset
The project uses the House Prices dataset consisting of:

- `train.csv` – Contains house features and the target variable (`SalePrice`).
- `test.csv` – Contains house features for which prices need to be predicted.

## Features Used
- `GrLivArea` – Above ground living area (square feet)
- `BedroomAbvGr` – Number of bedrooms
- `FullBath` – Number of full bathrooms

### Target Variable
- `SalePrice`

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn

## Steps Performed
1. Imported the required Python libraries.
2. Loaded the training and testing datasets.
3. Selected the required features and target variable.
4. Checked and handled missing values.
5. Trained a Linear Regression model using the training dataset.
6. Predicted house prices for the test dataset.
7. Generated a `submission.csv` file containing the predicted prices.

## Machine Learning Model
- Linear Regression

## Output
The model generates a file named `submission.csv` containing:

| Id | SalePrice |
|----|-----------|
| 1461 | Predicted Price |
| 1462 | Predicted Price |
| ... | ... |

## Project Structure
```
├── train.csv
├── test.csv
├── submission.csv
├── House_Price_Prediction.ipynb
└── README.md
```

## Requirements
Install the required libraries:

```bash
pip install pandas numpy scikit-learn
```

## How to Run
1. Upload `train.csv` and `test.csv` to Google Colab.
2. Run all the cells in the notebook.
3. The trained model will generate `submission.csv` with predicted house prices.

## Future Improvements
- Feature engineering
- Data preprocessing and outlier removal
- Hyperparameter tuning
- Compare Linear Regression with Decision Tree, Random Forest, XGBoost, and Gradient Boosting models
- Cross-validation for improved model performance

## Author
**Deepak Singh**

B.Tech Computer Science and Engineering  
Dr. B.R. Ambedkar National Institute of Technology (NIT) Jalandhar
