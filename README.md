Here’s a formatted version of the README file that includes headers, lists, and code blocks:

---

# **Assessing the Impact of Social Determinants on Obesity Rates Across U.S. Counties**

This repository contains code and analysis for the project **"Assessing the Impact of Social Determinants on Obesity Rates Across U.S. Counties: A Machine Learning Analysis and Policy Recommendations"**.

## **Project Overview**
This project leverages machine learning to predict county-level obesity rates using social determinants such as:
- Economic factors
- Healthcare access
- Food environment
- Neighborhood characteristics

The goal is to offer insights for policymakers on the impact of these determinants and recommend data-driven public health strategies.

## **Repository Structure**
- **`code/`**: Contains Python scripts for:
  - Data preprocessing
  - Exploratory Data Analysis (EDA)
  - Model training and evaluation
- **`Ma_Report.pdf`**: The detailed project report explaining:
  - Methodology
  - Results
  - Policy recommendations

## **Data**
- **Source**: The U.S. CDC's Diabetes Surveillance System ([link](https://gis.cdc.gov/grasp/diabetes/DiabetesAtlas.html))
- **Target Variable**: Obesity rate (%) for U.S. counties in 2021
- **Predictors**: Economic stability, food environment, access to healthcare, physical environment, social indices

## **Modeling Approach**
Several machine learning models were applied to predict obesity rates:
- **Linear Regression**
- **Ridge and Lasso Regression**
- **Random Forest**
- **Support Vector Regression (SVR)**
- **XGBoost**

## **Key Findings**
The **Support Vector Regression (SVR)** model outperformed others, achieving the best predictive performance with an R-squared value above 0.5 across both training and test datasets.

## **Usage Instructions**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Yuhan-Ma/Obesity-ML-Analysis.git
   ```
2. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the analysis**:
   ```bash
   python analysis.py
   ```

## **Dependencies**
- Python 3.x
- pandas
- scikit-learn
- xgboost
- matplotlib
- seaborn

## **Results & Policy Recommendations**
The analysis revealed that access to healthcare, socioeconomic factors, and neighborhood environments are critical determinants of obesity. Based on these findings, several policy recommendations were made, such as:
- Promoting health education programs targeting high-risk communities
- Improving urban planning for walkable neighborhoods
- Increasing access to affordable, healthy food options

For more detailed results and suggestions, please refer to the full report: **[Ma_Report.pdf](./Ma_Report.pdf)**.

## **Contact**
For questions or collaboration, please contact Yuhan Ma at **ym581@georgetown.edu**.

---

This structured README file will give a clear overview of your project for anyone visiting your GitHub page. Let me know if you'd like to tweak any sections further!
