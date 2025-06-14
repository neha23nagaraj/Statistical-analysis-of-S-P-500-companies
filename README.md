# Statistical Analysis of S&P 500 Companies Using Financial Metrics

This project presents a comprehensive statistical analysis of key financial metrics across companies in the S&P 500 index. The goal is to identify patterns, correlations, sector-based differences, and valuation insights using a combination of exploratory data analysis, statistical testing, regression modeling, and unsupervised learning.

## 📊 Objectives

- Understand distributions and central tendencies of financial ratios like P/E, P/S, and Market Cap.
- Detect and interpret outliers using box plots and distribution analysis.
- Assess sector-wise performance and valuation using visualizations and hypothesis testing.
- Build a multiple linear regression model to predict Market Capitalization.
- Apply K-Means clustering to group companies based on financial profiles.

## 🧪 Methodology

- **Data Preprocessing**: Handled missing values, standardized numeric features.
- **EDA**: Generated histograms, box plots, and correlation matrices to visualize financial patterns.
- **Hypothesis Testing**:
  - Mann-Whitney U-Test to compare P/E ratios across tech and non-tech sectors.
  - Kruskal-Wallis test for median differences in P/E and Market Cap across sectors.
  - Chi-square test to check association between Sector and Dividend status.
  - Pearson correlation test for Market Cap vs. P/E.
- **Regression Modeling**: Built a multiple linear regression model using selected financial indicators to predict log-transformed Market Cap.
- **Clustering**: Applied K-Means clustering on scaled financial metrics, visualized with PCA.

## 📈 Key Results

- Significant sector-wise differences were identified in valuation metrics.
- Positive correlation between Market Cap and EBITDA observed.
- Regression model explained ~47% of the variance in Market Cap (R² = 0.47).
- K-Means clustering revealed 4 distinct company profiles based on financial behavior.

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels, Scikit-learn)
- Jupyter/Google Colab (Notebook environment)
- LaTeX (for report formatting)

## 📁 Project Structure

```
├── data/                     # Cleaned financial dataset
├── code/
│   ├── eda_analysis.ipynb    # Main notebook with EDA and statistical testing
│   ├── regression_model.ipynb
│   └── clustering.ipynb
├── figures/                  # Plots and visualizations used in report
├── report/                   # Final report (PDF + LaTeX)
└── README.md
```


> *This project was completed as part of MA-541 Statistical Methods course at Stevens Institute of Technology.*
