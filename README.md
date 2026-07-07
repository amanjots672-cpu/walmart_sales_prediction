# walmart_sales_prediction
# 🛒 Walmart Sales Prediction

A Machine Learning project that predicts Walmart weekly sales using historical store data and various economic and environmental factors. This project covers the complete data analysis and model-building workflow, from data preprocessing and exploratory data analysis (EDA) to training and evaluating a Linear Regression model.

---

## 📌 Project Overview

The goal of this project is to predict **Weekly Sales** for Walmart stores based on features such as:

- Holiday status
- Temperature
- Fuel Price
- CPI (Consumer Price Index)
- Unemployment Rate

The notebook demonstrates a complete machine learning pipeline using Python and Scikit-learn.

---

## 📂 Dataset

The project uses the **Walmart Sales Dataset** containing historical sales records and related economic indicators.

### Features

| Feature | Description |
|---------|-------------|
| Store | Store ID |
| Date | Date of sales |
| Holiday_Flag | Indicates whether the week is a holiday |
| Temperature | Average temperature |
| Fuel_Price | Fuel price in the region |
| CPI | Consumer Price Index |
| Unemployment | Unemployment rate |
| Weekly_Sales | Target variable |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

1. Import libraries
2. Load dataset
3. Data inspection
4. Handle duplicate and missing values
5. Exploratory Data Analysis (EDA)
6. Univariate Analysis
7. Feature preprocessing
8. Train-Test Split
9. Feature Scaling
10. Train Linear Regression model
11. Model Evaluation

---

## 📈 Exploratory Data Analysis

The notebook includes:

- Dataset overview
- Data types and statistics
- Missing value analysis
- Duplicate checking
- Boxplots for numerical features
- Outlier detection

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Linear Regression

The model is trained using Scikit-learn and evaluated using the training and testing scores.

---

## 📁 Repository Structure

```
Walmart-Sales-Prediction/
│
├── Walmart_Sales_Prediction.ipynb
├── Walmart.csv
├── README.md
└── requirements.txt (optional)
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Walmart-Sales-Prediction.git
```

Move into the project folder:

```bash
cd Walmart-Sales-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Future Improvements

- Feature Engineering
- Hyperparameter tuning
- Compare multiple regression models
- Random Forest Regressor
- XGBoost Regressor
- Model deployment using Flask or Streamlit

---

## 📚 Libraries Used

```python
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

## 👤 Author

**Gurkirat Bains**

- Aspiring Data Analyst & Machine Learning Enthusiast
- Passionate about Data Analytics, Power BI, Excel, SQL, and Python

---

## ⭐ If you found this project helpful, please consider giving it a star!
