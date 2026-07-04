# 📈 Sales Forecasting using Machine Learning

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-f7931e?logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

This project is an end-to-end **Sales Forecasting System** built using Machine Learning. The objective is to analyze historical sales data, identify business trends, and predict future sales to help businesses make informed decisions regarding inventory planning, staffing, and demand forecasting.

This project was developed as **Task 1** for the **Future Interns Machine Learning Internship**.

---

## 🎯 Problem Statement

Businesses rely on sales forecasting to make strategic decisions. This project uses historical sales data to build a machine learning model capable of predicting future sales based on business and time-related features.

---

## 🚀 Features

- ✅ Data Cleaning
- ✅ Exploratory Data Analysis (EDA)
- ✅ Feature Engineering
- ✅ Machine Learning Model Training
- ✅ Sales Prediction
- ✅ Future Sales Forecasting
- ✅ Business Insights
- ✅ Professional Visualizations

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab
- Git & GitHub

---

## 📂 Project Structure

```text
FUTURE_ML_01
│
├── data/
│   └── Sample - Superstore.csv
│
├── notebooks/
│   └── Sales_Forecasting.ipynb
│
├── models/
│   └── sales_forecasting_model.pkl
│
├── outputs/
│   ├── graphs/
│   └── predictions/
│
├── images/
│   ├── eda/
│   └── forecast/
│
├── reports/
│   └── Project_Report.pdf
│
├── src/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Dataset

**Dataset:** Sample Superstore Dataset

The dataset contains historical sales information including:

- Order Date
- Ship Mode
- Segment
- Country
- City
- State
- Region
- Category
- Sub-Category
- Quantity
- Discount
- Profit
- Sales

---

## 🔄 Machine Learning Workflow

```text
Historical Sales Data
          │
          ▼
Data Cleaning
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Train-Test Split
          │
          ▼
Model Training
          │
          ▼
Model Evaluation
          │
          ▼
Future Sales Prediction
          │
          ▼
Business Insights
```

---

## 🤖 Machine Learning Model

The following model was used:

- **Random Forest Regressor**

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

- Sales Distribution
- Profit Distribution
- Category-wise Sales
- Region-wise Sales
- Monthly Sales Trend
- Yearly Sales Trend
- Top Customers
- Top Products
- Correlation Heatmap
- Sales vs Profit

---

## 📷 Sample Visualizations

> Add your screenshots inside the `images/` folder and update the paths below.

### Sales Distribution

![Sales Distribution](images/eda/sales_distribution.png)

---

### Correlation Heatmap

![Correlation Heatmap](images/eda/heatmap.png)

---

### Future Sales Forecast

![Forecast](images/forecast/forecast.png)

---

## 💡 Business Insights

Some key observations from the analysis include:

- Technology category generated the highest sales.
- Sales showed seasonal variation across months.
- Regional sales performance varied significantly.
- Discounts influenced profitability.
- Historical trends can help businesses forecast future demand.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YushBytes/FUTURE_ML_01.git
```

Go inside the project folder:

```bash
cd FUTURE_ML_01
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the notebook:

```text
notebooks/Sales_Forecasting.ipynb
```

Run all cells sequentially.

---

## 📁 Output Files

The project generates:

- Trained Machine Learning Model (`.pkl`)
- Forecast CSV
- Feature Engineered Dataset
- Business Graphs
- Future Sales Predictions

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Visualization
- Feature Engineering
- Machine Learning
- Regression Modeling
- Model Evaluation
- Business Analytics
- GitHub Project Organization

---

## 🔮 Future Improvements

- Streamlit Web Application
- Hyperparameter Tuning
- Time Series Forecasting Models
- XGBoost & LightGBM Comparison
- Interactive Dashboard
- Automated Report Generation

---

## 👨‍💻 Author

**Ayush Rahul Bidwai**

🎓 B.Tech Computer Science Engineering  
🏫 SRM Institute of Science and Technology

---

## ⭐ Acknowledgements

- Future Interns Machine Learning Internship
- Scikit-learn Documentation
- Pandas Documentation
- Matplotlib Documentation

---

## 📜 License

This project is created for educational and internship purposes.