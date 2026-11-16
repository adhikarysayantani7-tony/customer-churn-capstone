# Capstone Project: Customer Churn Prediction & Retention Strategy

## Project Overview
This capstone project solves a real-world subscription customer churn problem end-to-end—covering Exploratory Data Analysis (EDA), feature engineering, model comparison, executive reporting, and a 9-slide presentation.

## Repository Structure
- `README.md`: Project overview, model performance summary, and navigation guide
- `requirements.txt`: Required Python dependencies
- `data/customer_churn_capstone.csv`: Subscription customer churn dataset
- `notebooks/capstone_analysis.ipynb`: Interactive Jupyter Notebook with EDA, feature engineering, and model training
- `reports/final_report.pdf`: Detailed project report (PDF)
- `reports/presentation_slides.pdf`: 9-slide final presentation summarizing insights and recommendations

## Model Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| Decision Tree | 82.5% | 81.0% | 77.3% | 79.1% |
| Logistic Regression | 87.5% | 88.2% | 84.3% | 86.2% |
| **Random Forest (Selected)** | **92.5%** | **93.8%** | **89.9%** | **91.8%** |

## Key Insights & Recommendations
1. **Annual Contract Incentives**: Offer 15% upgrade discounts to Month-to-month subscribers before month 6.
2. **Proactive Support Escalation**: Trigger immediate outreach when a customer logs 3+ support tickets.
3. **First-Year Onboarding**: Focus retention check-ins on customers within their first 12 months of tenure.

## How to Run
1. Clone the repository:
   `git clone https://github.com/adhikarysayantani7-tony/customer-churn-capstone.git`
2. Install dependencies:
   `pip install -r requirements.txt`
3. Open the notebook:
   `jupyter notebook notebooks/capstone_analysis.ipynb`
