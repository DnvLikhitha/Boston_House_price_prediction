# Boston House Price Prediction

This project presents a machine learning model to predict housing prices in Boston using regression techniques. It involves data preprocessing, exploratory data analysis (EDA), model training and evaluation, all documented in a Google Colab notebook.

---

## Project Structure

```
├── Boston_House_Price_Prediction.ipynb  # Main Jupyter Notebook
├── HousingData.csv                      # Dataset file
└── README.md                            # Project documentation
```

---

## Objective

To build an effective regression model that can predict the median value of owner-occupied homes in Boston suburbs based on various housing features provided in the dataset.

---

## Dataset

- Source: UCI Machine Learning Repository  
- File: `HousingData.csv`  
- Features include:
  - CRIM: Crime rate per capita
  - ZN: Proportion of residential land zoned
  - INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT
  - MEDV: Median value of owner-occupied homes (Target)

---

## Technologies Used

- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn (Linear Regression)  
- Google Colab

---

## Methodology

1. Data Cleaning: Handled missing values and outliers  
2. Exploratory Data Analysis: Visualized distributions and relationships between features  
3. Feature Engineering: Applied scaling and encoding as needed  
4. Model Training: Trained Linear Regression models  
5. Evaluation: Assessed using R² Score and Mean Squared Error  

---

## How to Run

1. Open `Boston_House_Price_Prediction.ipynb` in Google Colab  
2. Upload `HousingData.csv` when prompted  
3. Run all cells to follow the full analysis and model training process
---

## How to Run

1. Open `Boston_House_Price_Prediction.ipynb` in Google Colab  
2. Upload `HousingData.csv` when prompted  
3. Run all cells to follow the full analysis and model training process
---

## Results

- The model's performance is evaluated using metrics like Mean Squared Error (MSE) and R-squared to ensure accuracy and reliability.
---

