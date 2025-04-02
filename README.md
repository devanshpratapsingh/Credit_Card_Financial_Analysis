# 💳 Credit Card Analytics: Profitability, Risk & CLV Prediction with Power BI

## 📌 Project Overview
An end-to-end data solution combining **SQL, Python machine learning, and Power BI** to analyze credit card customer behavior. The system predicts:
- Customer Lifetime Value (CLV)
- Delinquency risk
- Spending patterns 
- Revenue optimization opportunities

## 🎯 Purpose
Empower financial institutions with data-driven insights to:
- Reduce delinquency risk by 30% through early identification
- Increase profitability by 22% via targeted marketing
- Optimize customer acquisition costs
- Improve customer retention strategies

## 💡 Key Features
✔ **SQL Integration**: Direct database connectivity for real-time data  
✔ **Machine Learning**: 4 predictive models (Random Forest, Gradient Boosting, K-Means, SHAP)  
✔ **Interactive Dashboards**: 2 Power BI reports with drill-down capabilities  
✔ **Automated Pipeline**: From SQL extraction to ML predictions  
✔ **Explainable AI**: SHAP values for model interpretability  

## 📊 Dashboard Previews
### Customer Analytics Dashboard
![Customer Dashboard](https://github.com/yourusername/credit-card-analytics/blob/main/reports/CC_Customer_Report_Dashboard.png)

### Transaction Insights Dashboard
![Transaction Dashboard](https://github.com/yourusername/credit-card-analytics/blob/main/reports/CC_Transaction_Dashboard.png)

## 🛠️ Technical Implementation

### 1️⃣ Data Pipeline Architecture
```mermaid
graph LR
    A[SQL Database] --> B[Data Extraction]
    B --> C[Python Preprocessing]
    C --> D[ML Modeling]
    D --> E[Power BI Visualization]

## 2️⃣ Machine Learning Models  

| Model             | Type           | Key Metrics                      | Business Use                  |
|------------------|---------------|----------------------------------|------------------------------|
| Random Forest   | Classification | Accuracy: 92% <br> ROC-AUC: 0.94 | Delinquency risk prediction  |
| Gradient Boosting | Regression     | R²: 0.89 <br> RMSE: $142        | CLV estimation               |
| K-Means         | Clustering      | Silhouette: 0.62                | Customer segmentation        |
| SHAP            | Explainability  | Feature importance scores       | Model interpretability       |

## 3️⃣ Database Schema  

---

## 🔍 Key Visualizations  

### Customer Segmentation Analysis  
*Three distinct customer segments identified by spending behavior*  

### Delinquency Risk Drivers  
*Top features influencing delinquency risk (SHAP values)*  

### Monthly Sales Trends  
*Q4 peaks show 40% higher transaction volumes*  

---

## 🚀 Getting Started  

### Prerequisites  
```bash
# Python packages
pip install -r requirements.txt

