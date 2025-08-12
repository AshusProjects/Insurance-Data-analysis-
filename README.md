# 🏥 Insurance Data Analysis

## 📌 Project Overview
This project analyzes health insurance data from Kaggle, which contains the following attributes:
- **Age** — Age of the individual
- **Sex** — Gender (male/female)
- **BMI** — Body Mass Index
- **Children** — Number of children/dependents
- **Smoker** — Whether the individual smokes or not
- **Region** — Residential region in the US
- **Charges** — Medical insurance charges billed by the insurance company

The goal is to:
1. Explore the data with **univariate and bivariate analysis**.
2. Visualize trends and patterns using Python libraries.
3. Derive **insights** to understand the factors affecting medical charges.

---

## 📂 Dataset
Source: [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)  
Rows: 1338 | Columns: 7

---

## 📊 Key Steps in Analysis

### 1. **Data Exploration**
- Checked dataset shape, data types, missing values, and duplicates.
- Reviewed statistical summary (`.describe()`).

### 2. **Univariate Analysis**
- **Numerical Variables**: Histograms, KDE plots, and boxplots for Age, BMI, and Charges.
- **Categorical Variables**: Count plots for Sex, Smoker, Region, and Children.

### 3. **Bivariate Analysis**
- Scatter plots & regression plots to see relationships (e.g., Age vs. Charges).
- Boxplots to compare charges across smoker/non-smoker categories.
- Correlation heatmap to detect strong numeric relationships.

### 4. **Insights from Analysis**
- **Smokers** have significantly higher charges compared to non-smokers.
- **BMI** above 30 (obese range) tends to correlate with higher charges.
- **Age** has a positive correlation with medical charges.
- **Region** does not have a strong effect on charges.
- Having more **children** does not necessarily increase charges drastically.

---

## 📈 Visualizations
The project uses **Matplotlib** and **Seaborn** for plotting:
- Histograms & KDE plots for distributions
- Boxplots for categorical-numerical relationships
- Heatmap for correlation
- Scatter plots for trend analysis

---

## 🛠️ Tech Stack
- **Python** (Pandas, Numpy, Matplotlib, Seaborn)
- **Jupyter Notebook**

---

## ▶️ How to Run
1. Clone this repository:
```bash
git clone https://github.com/AshusProjects/log.git
