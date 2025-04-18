📡 Customer Churn Prediction for DTH Services
🧠 Overview
This project aims to predict customer churn for a Direct-To-Home (DTH) service provider. Given the intense market competition and high customer retention costs, we use machine learning to identify customers likely to churn and design targeted offers to retain them effectively.

📁 Project Resources
This repository includes key materials that provide a comprehensive view of the project's scope and results:

📊 Raw Datasets – Used for analysis and model training

📓 Python Notebook – Contains scripts for data cleaning, EDA, and model building

📈 Business Presentation Report – Summarizes findings, business understanding, and strategic recommendations

📘 Detailed Project Report – Covers methodology, code, and in-depth insights

🗂 Table of Contents
Project Background

Objectives

Data Overview

Exploratory Data Analysis (EDA)

Model Building

Model Performance

Business Insights and Recommendations

Contributors

License

📌 Project Background
The DTH industry experiences a churn rate between 14% and 16%, with this particular provider at 16.84%. The project was initiated to reduce churn through predictive analytics and targeted retention strategies.

🎯 Objectives
Build a predictive model to identify potential churners

Recommend data-driven, actionable strategies to reduce churn

Enhance customer retention and company revenue

🧾 Data Overview
The dataset consists of 11,260 customer accounts and 19 features, including:

Account tenure

Service scores

Payment methods

Customer feedback and demographics

Preprocessing steps included:

Handling missing values

Removing duplicates

Feature engineering

📊 Exploratory Data Analysis (EDA)
Key findings from EDA:

Higher churn rates among newer customers

Poor customer service strongly correlates with churn

Differences in churn patterns across payment methods and demographic groups

🧪 Model Building
We implemented and compared multiple machine learning models:


Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	85%	80%	78%	79%
Random Forest	88%	83%	85%	84%
XGBoost	92%	90%	91%	90.5%
XGBoost was fine-tuned for maximum precision and recall and emerged as the most effective model.

📈 Model Performance
Recall: 91%

Enables accurate identification of churn-prone customers

Supports targeted interventions and personalized retention offers

💡 Business Insights and Recommendations
Improve Onboarding: Reduce early-stage churn by enhancing first experiences

Boost Customer Service: Personalize support based on service scores and interactions

Tailored Offers: Use model outputs to provide strategic, personalized retention deals
