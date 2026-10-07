# 📊 Probability & Statistics Project
## Medical Cost Personal Insurance Analysis

### About the Project

This project analyzes the **Medical Cost Personal Insurance** dataset using probability and statistical techniques.

The project studies medical insurance charges and investigates patterns involving:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Residential region
- Medical charges

The analysis includes data cleaning, descriptive statistics, probability, distributions, the Central Limit Theorem, confidence intervals, hypothesis testing, correlation, regression, and data visualizations.

The main goal is to understand **why medical costs vary between individuals** and identify the factors most strongly associated with higher medical charges.

---

## 📁 Project Files

Make sure these files are kept in the same folder:

```text
medical_insurance_prob_stats_project(2).ipynb
insurance.csv
README.md
```

The notebook reads the dataset using:

```python
df = pd.read_csv('insurance.csv')
```

---

## ▶️ How to Run the Project

### 1. Install Python

Install **Python 3.9 or newer**.

Check your Python installation:

```bash
python --version
```

### 2. Install Required Libraries

Open Command Prompt / Terminal in the project folder and run:

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
```

### 3. Start Jupyter Notebook

Run:

```bash
jupyter notebook
```

A browser window will open.

### 4. Open the Project

Open:

```text
medical_insurance_prob_stats_project(2).ipynb
```

### 5. Run the Notebook

Run the cells from top to bottom using:

**Cell → Run All**

or press:

```text
Shift + Enter
```

Run the cells in order because later sections use data and variables created in earlier sections.

---

## 📊 Main Project Sections

1. **Data Cleaning & Variable Types**
   - Missing values
   - Duplicate records
   - Outlier detection
   - Variable classification and encoding

2. **Descriptive Statistics & Visualizations**
   - Mean
   - Median
   - Mode
   - Variance
   - Standard deviation
   - Skewness
   - Histograms
   - Boxplots
   - Scatter plots

3. **Probability Analysis**
   - Chebyshev's Inequality
   - Bayes' Theorem

4. **Distributions & Central Limit Theorem**
   - Distribution fitting
   - Sampling distributions
   - Central Limit Theorem

5. **Confidence Intervals & Hypothesis Testing**
   - Confidence intervals
   - t-tests
   - Proportion z-test
   - Null and alternative hypotheses

6. **Correlation & Regression**
   - Pearson correlation
   - Correlation heatmap
   - Simple linear regression
   - Multiple linear regression
   - R² analysis

---

## 👥 Learning Group 6

| S.No. | Name | Registration No. |
|---|---|---|
| 1 | N.G. Mokshith Sai | 252U1R8066 |
| 2 | N. Sai Manu Harsha | 252U1R8063 |
| 3 | M. Sahil | 252U1R8084 |
| 4 | S. Kiran Teja | 252U1R8083 |
| 5 | L. Sathya Narayana | 252U1R8100 |
| 6 | P. Sai Kumar Reddy | 252U1R8075 |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

---

## 📌 Dataset

**Medical Cost Personal Dataset**

The dataset contains personal and medical information such as age, sex, BMI, children, smoking status, region, and medical charges.

Dataset source:

https://www.kaggle.com/datasets/mirichoi0218/insurance

---

## 🎯 Project Objective

To use probability and statistical methods to understand the distribution of medical insurance charges, measure their variation, identify important relationships, and investigate factors associated with higher healthcare costs.

---

### Quick Start

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
jupyter notebook
```

Then open `medical_insurance_prob_stats_project(2).ipynb` and run all cells.
