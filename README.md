# 📈 Statistical Analysis of S&P 500 Companies Using Financial Metrics

This project performs a detailed statistical analysis of publicly available financial data for S&P 500 companies. The analysis uses foundational statistical methods to uncover trends, sector-based differences, and predictive patterns in company valuation metrics such as Market Capitalization, Price-to-Earnings (P/E), and Earnings per Share (EPS).

The project was conducted as part of the graduate-level course **MA-541: Statistical Methods** at Stevens Institute of Technology.

---

## 🎯 Objectives

- Explore and visualize key financial indicators such as Price, Market Cap, P/E Ratio, and Dividend Yield.
- Detect skewness, outliers, and distribution characteristics using box plots and histograms.
- Identify whether certain financial metrics vary significantly across sectors.
- Build a predictive model to estimate a company’s Market Cap based on its financial ratios.
- Uncover hidden financial groupings among companies using unsupervised learning techniques like clustering.

---

## 🔍 Methodology

- **Exploratory Data Analysis (EDA)**:
  - Histograms and boxplots for understanding distributions.
  - Sector-wise visualizations to compare financial ratios.
  - Correlation matrix to assess linear relationships.

- **Hypothesis Testing**:
  - *Mann-Whitney U-Test*: Used to assess P/E ratio differences between Tech and Non-Tech sectors.
  - *Kruskal-Wallis Test*: Analyzed Market Cap and P/E variation across sectors.
  - *Chi-Square Test*: Evaluated the association between sector type and dividend distribution.
  - *Pearson Correlation*: Assessed strength of linear relationships, e.g., between EBITDA and Market Cap.

- **Model Building**:
  - Applied multiple linear regression using log-transformed Market Cap as the response variable.
  - Included features like P/E, Earnings per Share, and Dividend Yield.
  - Evaluated model accuracy using R² and residual analysis.

- **Clustering**:
  - Applied K-Means algorithm on scaled numeric data.
  - PCA used to visualize clusters and interpret cluster characteristics.

---

## ✅ Key Results

- **Distribution Analysis**: Most financial metrics were right-skewed, indicating the presence of high-value outliers.
- **Outlier Detection**: Sectors like Technology and Healthcare showed significant valuation dispersion.
- **Hypothesis Testing**:
  - P/E ratio and Market Cap varied significantly across sectors.
  - No significant correlation was found between sector type and dividend payment.
- **Regression Model**:
  - Achieved an R² score of ~0.47.
  - Log transformation of Market Cap improved model interpretability.
- **K-Means Clustering**:
  - Optimal number of clusters determined via elbow method.
  - Identified 4 clusters with distinct financial profiles.

---

## 🧰 Tools & Libraries Used

- **Languages**: Python (Jupyter/Colab)
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Statistical Analysis: `scipy`, `statsmodels`
  - Machine Learning: `scikit-learn`
- **Documentation & Report**: LaTeX (Overleaf)

---

> *This repository was created for academic purposes as part of the MA-541 Statistical Methods course at Stevens Institute of Technology.*
