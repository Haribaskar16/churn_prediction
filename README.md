# Churn-prediction

## Project Overview ##

This project analyzes the Telco Customer Churn dataset to identify factors that influence customer churn and propose data-driven strategies to reduce it.
Churn (when customers stop using a service) is one of the biggest challenges for subscription-based businesses. By analyzing customer behavior, tenure, monthly charges, and contracts.

- Understand why customers churn

- Build visualizations & insights

- Propose business strategies to improve retention

- Suggest advanced improvements like predictive modeling and A/B testing

### Tech Stack ###

- Python (Pandas, NumPy, Matplotlib, Seaborn)

- Jupyter / Google Colab for analysis

- GitHub for version control

- Scikit-learn, XGBoost for ML models

- Power BI for dashboards

## Dataset ##

### Source: Telco Customer Churn Dataset ###

### Columns include: ###

- customerID – Unique identifier

- tenure – Number of months the customer has stayed

- MonthlyCharges – Current monthly bill

- TotalCharges – Total amount charged

- PaymentMethod, InternetService, Churn, etc.

## Analysis & Insights ##

📊 Churn Rate Analysis:

1. By Contract Type:
   Month-to-month      : 42.7%
   One year            : 11.3%
   Two year            : 2.8%

2. By Payment Method:
   Bank transfer (automatic): 16.7%
   Credit card (automatic)  : 15.2%
   Electronic check         : 45.3%
   Mailed check             : 19.1%

3. By Internet Service:
   DSL            : 19.0%
   Fiber optic    : 41.9%
   No             : 7.4%

🚨 High-Risk Customer Segments:
   1. Month-to-month contract customers
   2. Electronic check payment customers

💡 Model Recommendations:
   • Focus retention efforts on: Month-to-month contract customers
   • Best model for deployment: Logistic Regression
   • Model accuracy: 84.5%

## Advanced Improvements ##

- Predictive Modeling (Logistic Regression, Random Forest, XGBoost)

- Feature Engineering (usage trends, payment stability, CLV)

- Clustering for Customer Segmentation

- Interactive Dashboard (Power BI)

## Charts ##

![charts](images/Screenshot%202025-08-27%20195647%20-%20Copy.png)
![charts](images/Screenshot%202025-08-27%20195712.png)
![charts](images/Screenshot%202025-08-27%20195738.png)

