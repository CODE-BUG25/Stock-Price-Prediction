#  Netflix Stock Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-green)

---

##  Project Overview

This project predicts **Netflix (NFLX) stock closing prices** using **Machine Learning**. Historical stock market data is analyzed, visualized, and used to train a **Linear Regression** model that predicts the stock's closing price.

The project demonstrates the complete Machine Learning workflow:

- Data Collection
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Model Training
- Model Evaluation
- Prediction & Visualization

---

##  Project Structure

```
Netflix-Stock-Predictor/
│
├── Netflix Stock Predictor.ipynb
├── NFLX.csv
├── README.md
├── requirements.txt
└── images/
    ├── closing_price_trend.png
    ├── correlation_heatmap.png
    ├── stock_price_prediction.png
    ├── regression_line.png
    └── volume_traded_over_time.png
```

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Exploratory Data Analysis

###  Closing Price Trend

Shows how Netflix's closing stock price changes over time.

![Closing Price Trend](images/closing_price_trend.png)

---

###  Correlation Heatmap

Displays the correlation between stock features.

![Correlation Heatmap](images/correlation_heatmap.png)

---

###  Trading Volume

Shows the daily trading volume.

![Trading Volume](images/volume_traded_over_time.png)

---

## Machine Learning Model

**Model Used**

- Linear Regression

### Features Used

- Open Price
- High Price
- Low Price
- Volume
- Date (converted to ordinal values)

### Target Variable

- Closing Price

---

##  Prediction Result

Comparison of Actual vs Predicted Closing Prices.

![Prediction](images/stock_price_prediction.png)

---

##  Regression Line

Regression line showing the relationship between actual and predicted values.

![Regression Line](images/regression_line.png)

---

##  Evaluation Metrics

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

##  How to Run

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Netflix-Stock-Predictor.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Netflix Stock Predictor.ipynb
```

---

##  Future Improvements

- Random Forest Regressor
- XGBoost Regressor
- LSTM Neural Networks
- Real-time Stock Price Prediction
- Hyperparameter Tuning
- Interactive Dashboard using Streamlit

---

##  Learning Outcomes

Through this project, I learned:

- Data preprocessing using Pandas
- Data visualization using Matplotlib & Seaborn
- Feature engineering
- Linear Regression
- Model evaluation
- GitHub project management

---

##  Contributing

Contributions and suggestions are welcome!

Feel free to fork this repository and submit a pull request.

---

##  License

This project is licensed under the MIT License.

---

##  Author

**Sourabh Verma**

If you found this project helpful, consider giving it a ⭐ on GitHub!
