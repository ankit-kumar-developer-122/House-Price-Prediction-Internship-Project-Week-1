# 🏠 House Price Prediction

## 📌 Project Overview

This project was completed as part of the **Week 1 Internship Assignment**. The goal was to build a machine learning model capable of predicting house prices based on various property features and identify the factors that have the greatest influence on housing prices.

The project covers the complete machine learning workflow, including data exploration, preprocessing, visualization, model training, evaluation, and business insights.

---

## 🎯 Problem Statement

Real estate buyers and sellers often rely on guesswork or outdated comparisons to estimate a property's value. This project aims to provide a data-driven solution by developing a regression model that predicts house prices using property characteristics such as area, number of bathrooms, air conditioning, stories, and other housing features.

---

## 📊 Dataset

**Housing Prices Dataset**

🔗 https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

The dataset contains various house attributes along with their corresponding prices, making it suitable for regression analysis and predictive modeling.

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📋 Project Workflow

### 1. Data Loading & Exploration
- Loaded the dataset using Pandas
- Explored rows, columns, and data types
- Identified target and feature variables
- Checked for missing values

### 2. Data Cleaning
- Removed duplicate records
- Handled missing values
- Converted categorical features into numerical values
- Prepared data for model training

### 3. Model Building
- Split data into training and testing sets (80:20)
- Trained a Linear Regression model
- Trained a Random Forest Regressor
- Compared model performance

### 4. Data Visualization
Created the following visualizations:
- House Price Distribution Histogram
- Correlation Heatmap
- Actual vs Predicted Price Scatter Plot

### 5. Insights & Summary
- Identified important price-driving features
- Evaluated model performance
- Generated business recommendations

---

## 📈 Model Performance

| Model | Performance |
|---------|------------|
| Linear Regression | Best Performing |
| Random Forest Regressor | Slightly Lower Accuracy |

### Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

**Best R² Score:** ~65%

---

## 🔍 Key Insights

- House area had the strongest impact on price.
- Number of bathrooms was another major pricing factor.
- Air conditioning and number of stories significantly increased property value.
- Linear Regression outperformed Random Forest despite being a simpler model.
- Luxury houses were sometimes undervalued by the prediction model.

---

## 💡 Business Recommendation

Real estate companies should focus on properties with larger areas, more bathrooms, and air conditioning, as these features contribute most significantly to higher property values. The prediction model can support pricing decisions but should be used cautiously for luxury properties.

---

## 📂 Project Structure

```text
HousePricePrediction/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
├── charts/
│   ├── house_price_distribution.png
│   ├── correlation_heatmap.png
│   └── actual_vs_predicted.png
│
└── README.md
```

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/HousePricePrediction.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run the Notebook

Open:

```text
analysis.ipynb
```

and execute all cells.

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Machine Learning Regression Models
- Model Evaluation Techniques
- Feature Importance Analysis
- Real-world Data Science Workflow

---

## 👨‍💻 Author

**Ankit Kumar**

B.Tech (Information Technology)
College : Rungta College of Engineering and Technology, Bhilai, Chhattisgarh

Internship Project – Week 1
