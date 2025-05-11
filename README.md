🧠 Predicting Customer Churn Using Machine Learning to Uncover Hidden Patterns
📌 Problem Statement
Customer churn is a major concern for businesses, especially those with subscription-based models. This project uses machine learning to predict customer churn by analyzing historical customer data to uncover hidden behavioral patterns. The goal is to enable proactive retention strategies and improve customer lifetime value.

🎯 Objectives
Predict customer churn using machine learning

Analyze historical data to identify risk indicators and patterns

Enable organizations to take timely retention actions

🛠️ Project Workflow
Data Collection – Gather customer data: demographics, transactions, support logs

Preprocessing – Clean data, handle missing values, encode variables, scale features

EDA – Visualize patterns and correlations

Feature Selection – Identify relevant predictors

Modeling – Train multiple models (Logistic Regression, Random Forest, XGBoost)

Evaluation – Use metrics like Accuracy, F1 Score, ROC AUC

Interpretation – Apply SHAP to explain predictions

Deployment (Optional) – API or dashboard integration

Monitoring – Track performance and retrain with new data

🧾 Dataset Features
Feature Name	Description
CustomerID	Unique customer identifier
Gender	Customer’s gender
Age	Age of the customer
Tenure	Months with the company
SubscriptionType	Subscription plan type
MonthlyCharges	Monthly billing amount
TotalCharges	Total amount charged
PaymentMethod	Payment mode used
ContractType	Length of the contract
InternetService	Type of internet service
OnlineSecurity	Online security add-on status
TechSupport	Tech support add-on status
StreamingServices	Use of streaming services
CustomerSupportCalls	Support contact count
LastInteractionDate	Date of last customer activity
Churn	Target variable (1 = Yes, 0 = No)

⚙️ Technologies Used
Languages/Libraries: Python, Pandas, Scikit-learn, XGBoost, SHAP, Seaborn, Matplotlib

Modeling: Logistic Regression, Random Forest, XGBoost

Visualization: SHAP, confusion matrix, ROC curve

Deployment (Optional): Flask, Streamlit, Docker

Version Control: Git, GitHub

📊 EDA Highlights
Distribution plots, bar charts, and box plots

Correlation heatmaps

Churn analysis by contract type, support calls, etc.

SHAP plots to interpret feature influence

📈 Model Performance
Models were evaluated using the following metrics:

Accuracy

Precision

Recall

F1 Score

ROC AUC

Best model: Random Forest (tuned using GridSearchCV)

📤 Deployment (Optional)
REST API using Flask or FastAPI

Interactive dashboards using Streamlit

Cloud deployment via AWS / Azure / GCP

👥 Team Members
Name	Role	Contribution
Priyadharshini R	Lead	Coordination, documentation, data engineering
Nandhitha M	Data Engineer	Data collection, cleaning, preprocessing
Varshini S, Vaishnavi A	NLP Specialist / Data	Feature engineering, model evaluation
Sonika R	Data Analyst / Visualization	EDA, visualizations, insight generation

🔗 GitHub Repository
Project Repository (Insert your actual repo link here)
