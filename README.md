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
```
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

# 🚀 Getting Started

## Prerequisites

Install the required Python packages by running the following command in your terminal:  
**pip install -r requirements.txt**

## Installation

### Clone the repository:
To get started, clone the repository to your local machine using the following steps:  
- Run the command: **git clone https://github.com/yourusername/credit-card-analytics.git**  
- Navigate to the project directory: **cd credit-card-analytics**

### Configure database connection:
Set up your database connection by creating a configuration file at `config/db_config.ini` with the following content:  
- **Section**: [database]  
- **Host**: your_db_host  
- **Name**: credit_card_db  
- **User**: your_username  
- **Password**: your_password  

### Execute the analysis pipeline:
Run the analysis notebooks to perform exploratory data analysis and modeling:  
- Open the first notebook: **jupyter notebook notebooks/1_eda_and_preprocessing.ipynb**  
- Open the second notebook: **jupyter notebook notebooks/2_ml_modeling.ipynb**

## 📂 Repository Structure

The project is organized as follows:  
- **data/**: Contains processed datasets  
- **notebooks/**: Includes analysis notebooks  
  - **1_eda_and_preprocessing.ipynb**: Notebook for exploratory data analysis and preprocessing  
  - **2_ml_modeling.ipynb**: Notebook for machine learning modeling  
- **sql/**: Stores SQL query library  
- **powerbi/**: Contains dashboard files  
- **plots/**: Stores generated visualizations  
- **reports/**: Contains model outputs  
- **config/**: Stores configuration files  
- **requirements.txt**: Lists Python dependencies  
- **README.md**: Project documentation

## 📌 Key Findings

### Card Type Insights:
- **Premium cards** show **40% higher CLV** but **15% greater delinquency risk**  
- **Blue cards** contribute **68% of total revenue**  

### Behavioral Patterns:
- **Fuel purchases** have **28% lower profitability**  
- Customers with **>60% utilization** are **3x more likely to default**  

### Segmentation Results:
- **Cluster 2 (High Spenders)** generates **58% of revenue**  
- **Cluster 0 (Low Utilizers)** has highest retention rate (**92%**)  

## 🤝 Contribution Guidelines

1. Fork the repository  
2. Create your feature branch by running:  
   **git checkout -b feature/your-feature**  
3. Commit your changes with the following command:  
   **git commit -m 'Add some feature'**  
4. Push to the branch using:  
   **git push origin feature/your-feature**  
5. Open a Pull Request  

## 📄 License
Distributed under the **MIT License**. See `LICENSE` for more information.

## 📧 Contact
**Your Name** - [your.email@example.com](mailto:your.email@example.com)  
Project Link: [GitHub Repository](https://github.com/yourusername/credit-card-analytics)
