# 📊 ESG Scores Under Scrutiny

**A Data Science Investigation into the Relationship Between ESG Scores and Stock Performance**

## 🔍 Overview

This project investigates the extent to which Environmental, Social, and Governance (ESG) scores are informative indicators of financial performance, using a dataset of S&P 500 companies. The research challenges the conventional wisdom of ESG-driven investment strategies and considers whether a shift to more robust reporting frameworks, such as the Corporate Sustainability Reporting Directive (CSRD), is warranted.

## 📁 Project Structure
```
esg_analysis/
├── data/             # Raw and processed datasets
├── notebooks/        # rmd and html file with analysis
├── visualizations/   # Generated plots 
└── README.md
```

## 🎯 Research Questions

- Do ESG scores correlate with total stock returns?
- Are ESG scores still reliable performance indicators?
- How does the static nature of ESG scores affect their predictive power?

## 🧪 Methodology

This project follows a six-step Data Science workflow:

1. **Problem Understanding**: Framing ESG metrics as potential predictors of financial returns.
2. **Data Preprocessing**: Cleaning and standardizing ESG and financial data.
3. **Exploratory Data Analysis**: Statistical summaries and correlation analysis.
4. **Data Preparation**: Feature engineering and filtering.
5. **Modeling**: Linear and polynomial regression models with sector-based interactions. Decesion tree and ramdom forest models also included. 
6. **Evaluation & Deployment**: Model assessment via cross-validation and interpretability.

## 📈 Key Features

- Multiple regression models (linear, polynomial, and interaction models)
- Cross-validation for robust performance evaluation
- ESG scores as both individual and composite indicators
- Sector-based analysis to explore heterogeneous effects

## 📌 Notable Findings

- ESG scores alone may not be strong predictors of stock performance.
- Polynomial terms and sector-specific effects reveal nuanced patterns.
- ESG investing might benefit from alignment with more dynamic and transparent frameworks like CSRD.

## 🛠️ Tools and Technologies

- **R** (tidyverse, caret, ggplot2)
- **RMarkdown** for reproducible analysis
- **ESG and financial data** sourced from S&P 500 datasets (Kaggle)

## 📬 Contact

For questions or collaboration ideas, feel free to reach out via [LinkedIn](https://www.linkedin.com/todomonkos) or open an issue on this repository.

---
