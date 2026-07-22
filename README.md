# 🛒 End-to-End E-commerce Analytics Project

## 📌 Project Overview

This project is a complete End-to-End E-commerce Analytics solution developed using Python, SQL, Machine Learning, and Power BI. It demonstrates the complete data analytics lifecycle—from collecting and cleaning raw e-commerce data to building predictive machine learning models and creating interactive business dashboards.

The project is based on the Olist Brazilian E-commerce Dataset and focuses on understanding customer purchasing behavior, sales performance, delivery efficiency, and predicting order values using Machine Learning.

---

# 🎯 Objectives

- Clean and preprocess real-world e-commerce datasets.
- Merge multiple relational datasets into a unified analytical dataset.
- Perform Exploratory Data Analysis (EDA).
- Build SQL queries for business insights.
- Engineer features for predictive modeling.
- Train and compare Machine Learning regression models.
- Predict customer order values.
- Create an interactive Power BI dashboard.
- Demonstrate an end-to-end Data Analytics workflow.

---

# 📂 Project Structure

```
Ecommerce_Analytics_Project/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Loading.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Data_Merging.ipynb
│   ├── 04_Exploratory_Data_Analysis.ipynb
│   ├── 05_Feature_Engineering.ipynb
│   ├── 06_SQL_Analysis.ipynb
│   ├── 07_Machine_Learning.ipynb
│   └── 08_Model_Evaluation.ipynb
│
├── models/
│   └── random_forest_model.pkl
│
├── dashboard/
│   └── Ecommerce_Dashboard.pbix
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset Information

Dataset Source:

**Olist Brazilian E-commerce Public Dataset**

The project integrates multiple datasets including:

- Customers
- Orders
- Order Items
- Payments
- Reviews
- Products
- Sellers
- Geolocation
- Product Category Translation

---

# 🛠 Technologies Used

## Programming

- Python 3.x

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite3
- Scikit-learn
- Joblib

## Database

- SQLite

## Visualization

- Power BI

## Version Control

- Git
- GitHub

---

# 📖 Project Workflow

## 1️⃣ Data Loading

- Imported multiple CSV datasets.
- Verified dataset dimensions.
- Checked data types.
- Examined missing values.

---

## 2️⃣ Data Cleaning

Performed:

- Missing value treatment
- Duplicate removal
- Data type conversion
- Null value analysis
- Data consistency checks

---

## 3️⃣ Data Merging

Merged multiple tables using common keys including:

- customer_id
- order_id
- product_id
- seller_id

Created a master dataset for analysis.

---

## 4️⃣ Exploratory Data Analysis

Performed analysis on:

- Sales Trends
- Customer Distribution
- Product Categories
- Delivery Time
- Payment Methods
- Order Status
- Customer Reviews
- Revenue Distribution

Created multiple visualizations using:

- Bar Charts
- Pie Charts
- Histograms
- Box Plots
- Heatmaps
- Correlation Matrix

---

## 5️⃣ Feature Engineering

Created useful features including:

- Delivery Time
- Shipping Delay
- Order Month
- Order Year
- Order Day
- Customer Purchase Frequency
- Total Spending
- Average Spending

Prepared dataset for Machine Learning.

---

## 6️⃣ SQL Business Analysis

Implemented SQL queries to answer business questions such as:

- Total Revenue
- Monthly Sales
- Top Selling Categories
- Best Performing Sellers
- Customer Order Frequency
- Average Delivery Time
- Payment Analysis

---

## 7️⃣ Machine Learning

### Target Variable

```
order_value
```

### Models Trained

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

# 📈 Model Evaluation

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Model Comparison

| Model | MAE | RMSE | R² Score |
|--------|------:|------:|------:|
| Random Forest | 86.53 | 222.33 | 0.7591 |
| Decision Tree | 102.92 | 310.47 | 0.5303 |
| Linear Regression | 138.44 | 365.24 | 0.3500 |

**Best Model:** Random Forest Regressor

---

# 📊 Power BI Dashboard

The dashboard provides interactive insights including:

- Sales Overview
- Revenue Trends
- Order Status
- Customer Analysis
- Payment Analysis
- Product Category Analysis
- Delivery Performance

---

# 📌 Business Insights

- Random Forest significantly outperformed Linear Regression and Decision Tree.
- Customer purchasing behavior is highly non-linear.
- Delivery performance impacts customer satisfaction.
- Product category and payment method influence order value.
- E-commerce sales show seasonal patterns.
- Feature engineering improved prediction performance.

---

# 📷 Sample Visualizations

Include screenshots such as:

- Power BI Dashboard
- Feature Importance Plot
- Actual vs Predicted Plot
- Correlation Heatmap
- Sales Analysis Charts

---

# 🚀 How to Run the Project

## Clone Repository

```bash
git clone https://github.com/yourusername/Ecommerce_Analytics_Project.git
```

## Navigate

```bash
cd Ecommerce_Analytics_Project
```

## Install Requirements

```bash
pip install -r requirements.txt
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open notebooks in sequence:

```
01 → 02 → 03 → 04 → 05 → 06 → 07 → 08
```

---

# 📁 Large Files Notice

Due to GitHub file size limitations, the following files are excluded from the repository:

- Large processed datasets
- Trained Machine Learning models
- SQLite database

These files can be regenerated by running the notebooks sequentially.

---

# 🔮 Future Improvements

- Hyperparameter Tuning
- XGBoost Regression
- LightGBM
- Streamlit Dashboard
- Model Deployment
- Cloud Deployment
- Real-time Data Pipeline

---

# 👩‍💻 Author

**Vaishnavi Gawade**

GitHub:
https://github.com/VaishnaviG18

LinkedIn:
(https://www.linkedin.com/in/vaishnavi-gawade-583958297/)

---

# ⭐ If you found this project useful, please consider giving it a star!
