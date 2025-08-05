# 📈 Stock Price Prediction using Machine Learning

This project was completed as part of a Machine Learning Internship. The goal is to predict stock **closing prices** using historical stock data with features like `open`, `high`, `low`, and `volume`.

---

## 🗂️ Dataset

- **Source**: Provided as `Stock Prices Data Set.csv`
- **Columns**:
  - `symbol`: Ticker symbol of the stock (e.g., AAPL, ABBV)
  - `date`: Date of record
  - `open`, `high`, `low`, `close`: Stock prices
  - `volume`: Number of shares traded

---

## 🎯 Objective

- Predict the **closing price** of a selected stock (AAPL) based on historical data using machine learning models.

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib, Seaborn (Visualization)
- Scikit-learn (ML Models)

---

## 📊 Visualizations

- Line plot of stock price over time
- Boxplot for quartile analysis
- Correlation heatmap
- Histogram of price distribution
- Scatter plot: Open vs Close

---

## 🤖 Machine Learning Models

| Model                | Description                       |
|---------------------|-----------------------------------|
| Linear Regression    | Simple baseline model             |
| Random Forest Regressor | Advanced model for better accuracy |

### ✅ Evaluation Metrics:
- **MSE (Mean Squared Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**

---
## Key Insights 
Here are the visual plots for your internship project:

1. Box Plot (Quartile Visualization):
Shows the spread, quartiles, and outliers of open, high, low, close, and volume.
Helps identify data distribution and potential anomalies.

2. Correlation Heatmap:

Displays how strongly features are related.
For example, open, high, low, and close are highly correlated, which is expected for stock prices.

---

## 🧪 Results

- **Random Forest** performed better than **Linear Regression** with higher R² and lower RMSE.
- Strong correlations observed between `open`, `high`, `low`, and `close`.
- - Linear Regression gave a basic baseline with moderate accuracy.
- Random Forest performed better with higher R² and lower RMSE.
- Stock data is affected by many external factors, so model accuracy has limitations.
- This project shows how to preprocess, train, evaluate, and visualize ML models.

---


## 📬 Contact

**Intern:** Komal

**Email:** komal93singh@gmail.com

**LinkedIn:** https://www.linkedin.com/in/komal-b61580158/

---

## 📁 Project Structure

```

📦 stock-price-prediction/
├── 📄 README.md
├── 📊 Stock Prices Data Set.csv
├── 📓 internship\_project\_notebook.ipynb
└── 📁 images/ (optional - contains saved charts)

````

---

## 📌 How to Run

1. Clone the repository or download the files.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
````

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook internship_project_notebook.ipynb
   ```

---

## 🙋‍♀️ Internship Learnings

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Model building and evaluation
* Visualization and insights
* Real-world application of ML

---


