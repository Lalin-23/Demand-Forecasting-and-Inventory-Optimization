# Demand Forecasting and Inventory Optimization

A data-driven project focused on **forecasting product demand** and **optimizing inventory levels** to minimize costs while ensuring high service levels. This project demonstrates how predictive analytics and operations research techniques can be combined for smarter supply chain decisions.

---

## 📌 Problem Statement

Businesses often face challenges such as:

* Overstocking → high holding costs
* Understocking → stockouts and lost sales
* Poor demand visibility

This project aims to **accurately forecast demand** and **optimize inventory policies** (reorder points, safety stock, order quantity) to balance cost and service level.

---

## 🎯 Objectives

* Forecast future demand using historical sales data
* Evaluate multiple time-series and ML models
* Optimize inventory using forecast outputs
* Reduce holding, ordering, and stockout costs
* Provide actionable insights for decision-making

---

## ✨ Key Features

* 📈 Time-series demand forecasting
* 🤖 Machine learning–based prediction models
* 📦 Inventory optimization (EOQ, safety stock, reorder point)
* 📊 Performance evaluation using standard metrics
* 🔁 Scenario analysis for demand uncertainty

---

## 🏗️ Project Structure

```
Demand-Forecasting-Inventory-Optimization/
├── data/
│   ├── raw_sales_data.csv        # Historical demand data
│   ├── processed_data.csv        # Cleaned & transformed data
├── notebooks/
│   ├── EDA.ipynb                 # Exploratory Data Analysis
│   ├── Forecasting.ipynb         # Demand forecasting models
│   ├── Inventory_Optimization.ipynb # Optimization logic
├── src/
│   ├── preprocess.py             # Data cleaning & feature engineering
│   ├── forecasting_models.py     # ARIMA / SARIMA / ML models
│   ├── inventory.py              # EOQ, safety stock, ROP calculations
│   ├── evaluate.py               # Model evaluation
├── outputs/
│   ├── forecasts.csv             # Forecast results
│   ├── inventory_plan.csv        # Optimized inventory decisions
│   ├── plots/                    # Forecast & inventory plots
├── README.md
├── requirements.txt
└── app.py                        # (Optional) Dashboard / API
```

---

## ⚙️ Technologies Used

* **Python 3.x**
* **NumPy, Pandas** – data processing
* **Matplotlib, Seaborn** – visualization
* **Statsmodels** – ARIMA / SARIMA
* **Scikit-learn** – ML models & metrics
* **SciPy / PuLP** – optimization
* **Streamlit / Flask** (optional) – deployment

---

## 🧠 Modeling Approaches

### 🔹 Demand Forecasting

* Moving Average & Exponential Smoothing
* ARIMA / SARIMA
* Machine Learning (Linear Regression, Random Forest, XGBoost)

### 🔹 Inventory Optimization

* Economic Order Quantity (EOQ)
* Safety Stock Calculation
* Reorder Point (ROP)
* Service Level–based optimization

---

## 🚀 Workflow

1. Data collection and cleaning
2. Exploratory data analysis (trend, seasonality)
3. Train and validate forecasting models
4. Select best-performing model
5. Compute optimal inventory policies
6. Evaluate cost and service-level impact

---

## ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/demand-forecasting-inventory-optimization.git
cd demand-forecasting-inventory-optimization
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Notebooks

Open and execute notebooks in the `notebooks/` folder using Jupyter or Google Colab.

---

## 📈 Evaluation Metrics

### Forecasting Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)

### Inventory Metrics

* Service Level
* Total Inventory Cost
* Stockout Frequency

---

## 🧪 Sample Insight

```
Product A:
Forecasted Monthly Demand: 1,200 units
Optimal Order Quantity (EOQ): 350 units
Reorder Point: 180 units
Expected Service Level: 95%
```

---

## 🔮 Future Enhancements

* Deep learning models (LSTM, Transformer)
* Multi-product & multi-warehouse optimization
* Real-time demand forecasting
* Integration with ERP systems
* Interactive dashboard

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Lalin
Data Science / Operations Analytics Enthusiast

---

⭐ If you find this project useful, please give it a star!
