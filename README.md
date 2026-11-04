# 📊 Customer Churn Analysis: Driving Retention Strategy

## 🎯 Project Overview
Customer acquisition is roughly five times more expensive than customer retention. This project analyzes a dataset of 500 customers to identify the primary drivers of customer churn and segment the user base by risk. The goal is to provide data-driven, actionable recommendations to the customer success and marketing teams to reduce attrition and improve lifetime value.

## 🛠️ Setup Instructions
To reproduce this analysis locally, follow these steps:
1. Clone this repository: `git clone https://github.com/satadru105/capstone_business_analysis.git`
2. Navigate to the project folder: `cd capstone_business_analysis`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the Jupyter Notebooks in the `notebooks/` directory sequentially (1 -> 2 -> 3).

## 📁 Code Structure
```text
capstone_business_analysis/
│
├── data/
│   ├── raw_data.csv           # Original 500-row dataset
│   └── cleaned_data.csv       # Processed data with engineered features
│
├── notebooks/
│   ├── 1_data_cleaning.ipynb  # Data formatting and feature engineering (Tenure Groups)
│   ├── 2_eda.ipynb            # Exploratory Data Analysis and visual storyboarding
│   └── 3_analysis.ipynb       # Statistical testing (Chi-Sq, T-Test) & Random Forest
│
├── reports/
│   ├── executive_summary.pdf  # 1-page business summary
│   └── technical_report.pdf   # Detailed technical documentation
│
├── presentations/
│   └── business_presentation.pptx # 10-15 slide presentation deck
│
├── README.md                  # Comprehensive project documentation
└── requirements.txt           # Python package dependencies