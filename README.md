# 🐶 Pet Insurance Claims Risk Analytics

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-orange?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)

</p>

---

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Quick Start](#quick-start)
- [Analysis Workflow](#analysis-workflow)
- [Model Performance](#model-performance)
- [Key Findings](#key-findings)
- [Example Visualisations](#example-visualisations)
- [Skills Demonstrated](#skills-demonstrated)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Project Overview

This project demonstrates an end-to-end insurance analytics workflow using a large synthetic pet insurance claims dataset designed for pricing and predictive modelling.

The project combines:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Risk Segmentation
- Predictive Machine Learning
- Business Insights & Strategic Recommendations

The objective is to identify the key drivers of claim severity and support pricing, underwriting and portfolio management decisions for pet insurance providers.

---

## Project Highlights

- Analysed over **188,000** insurance claims.
- Engineered insurance-specific pricing variables.
- Built and compared **four** regression models.
- Produced business recommendations for pricing and underwriting.
- Published the complete project on GitHub.

---

## Technologies

| Category | Tools |
|----------|------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Data Visualisation | Matplotlib |
| Development | Jupyter Notebook |
| Version Control | GitHub |

## Project Structure

```text
pet-insurance-claims-risk-analytics/

├── images/                  
├── notebooks/              
│   ├── 01_dataset_exploration.ipynb
│   ├── 02_pet_insurance_mapping.ipynb
│   ├── 03_risk_segmentation_analysis.ipynb
│   ├── 04_model_building.ipynb
│   └── 05_business_insights.ipynb
│
├── reports/
│   └── 05_business_insights.html
│
├── README.md
└── LICENSE
```

---

## Quick Start

Clone the repository

```bash
git clone https://github.com/ryleeli/pet-insurance-claims-risk-analytics.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Analysis Workflow

### 01 Dataset Exploration

- Data quality assessment
- Missing value inspection
- Claim severity distribution
- Exploratory analysis

---

### 02 Feature Engineering

Creation of insurance pricing variables:

- Age Risk Factor
- Breed Risk Factor
- Coverage Risk Factor
- Excess Risk Factor

---

### 03 Risk Segmentation

Business analysis including:

- Coverage level comparison
- Breed risk analysis
- Risk heatmap

---

### 04 Predictive Modelling

Four regression models were evaluated:

- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting

Evaluation metrics:

- MAE
- RMSE
- R²

Gradient Boosting achieved the strongest overall performance.

---

### 05 Business Insights

Final recommendations covering:

- Pricing strategy
- Underwriting optimisation
- Risk segmentation
- Portfolio management

---

## Key Findings

- Older pets generate significantly higher expected claim amounts.
- Comprehensive policies consistently produce the highest claim severity.
- Breed-specific risk remains an important pricing factor.
- Gradient Boosting delivered the best predictive performance.

---

## Model Performance

Four regression models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE) and R².

| Model | MAE ↓ | RMSE ↓ | R² ↑ |
|------|------:|------:|------:|
| Linear Regression | 2757.52 | 4371.87 | 0.1309 |
| Decision Tree | 2776.95 | 4403.48 | 0.1183 |
| Random Forest | 2773.20 | 4396.58 | 0.1211 |
| **Gradient Boosting** | **2747.88** | **4358.19** | **0.1364** |

Gradient Boosting achieved the best predictive performance across all evaluation metrics.

These results demonstrate that ensemble learning methods provide modest improvements over traditional regression techniques for predicting insurance claim severity.


## Example Visualisations

### Claim Severity Distribution

The claim severity distribution is highly right-skewed, indicating that a small proportion of claims account for very high losses.

![](images/claim_severity_distribution.png)

---

### Coverage Level Comparison

Average claim severity increases consistently from Basic to Comprehensive policies.

![](images/coverage_analysis.png)

---

### Breed × Coverage Risk Matrix

High-risk breeds combined with Comprehensive coverage exhibit the greatest expected claim severity.

![](images/risk_heatmap.png)

---

### Model Performance Comparison

Gradient Boosting achieved the lowest prediction error and the highest explanatory power.

![](images/model_comparison.png)

---

### Top Feature Importance

Engineered pricing variables dominate model predictions, with age-related features contributing the most.

![](images/gradient_boosting_feature_importance.png)

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Modelling
- Machine Learning
- Model Evaluation
- Data Visualisation
- Insurance Pricing Analytics
- Risk Segmentation
- Business Insights

---

# Future Improvements

Potential extensions include:

- Hyperparameter tuning
- Cross-validation
- XGBoost / LightGBM models
- SHAP explainability
- Interactive Power BI dashboard
- Streamlit deployment
- SQL data warehouse integration

---

## Author

**Yanjie (Rylee) Li**

Master of Actuarial Studies  
Australian National University

Interested in:

- Data Analytics
- Machine Learning
- Insurance Pricing
- Risk Analytics

GitHub:
https://github.com/ryleeli

---

## Acknowledgements

This project was completed as part of my personal data analytics portfolio to demonstrate practical applications of machine learning and business analytics in insurance.
