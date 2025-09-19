# CHURN_DATA_ANALYSIS
📊 Churn Analysis
📌 Project Overview

This project explores customer churn patterns using telecom dataset features such as phone service, internet service, online security, backup, device protection, streaming services, and tech support. The goal is to identify the key factors influencing customer churn and provide actionable insights for reducing churn.

📂 Dataset

The dataset contains customer-level information such as:

Demographics: SeniorCitizen, tenure, etc.

Services: PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies

Target Variable: Churn (Yes/No)

🔎 Methodology

Data Cleaning & Preprocessing

Handled missing values and categorical features.

Exploratory Data Analysis (EDA)

Count plots and stacked bar charts to compare churn vs. non-churn groups.

Subplots created for multiple service-related features.

Percentage Analysis

Group-wise churn percentage calculated for better interpretation.

📊 Visualizations

Countplots by Service Features: Show distribution of churn within each service category.

Stacked Percentage Bars: Highlight percentage of churners vs. non-churners for each group.

Example visualization:

Churn by Internet Service → Fiber optic customers show much higher churn compared to DSL.

Churn by Online Security/Backup/Tech Support → Lack of these services correlates strongly with higher churn.

🔑 Key Insights

Customers with fiber optic internet churn more than DSL customers.

Customers without online security, backup, or tech support have the highest churn.

Customers with value-added services show improved retention.

🚀 Conclusion

Churn is significantly influenced by internet type and availability of support/security services. Companies can reduce churn by:

Offering bundled packages with online security, backup, and tech support.

Improving satisfaction for fiber optic users through better service quality or pricing strategies.

⚙️ Tech Stack

Python: pandas, numpy, seaborn, matplotlib

Jupyter Notebook for analysis and visualization

📌 Future Work

Apply machine learning models (Logistic Regression, Random Forest, XGBoost) for churn prediction.

Build a dashboard for interactive churn analysis (using Plotly/Dash/Streamlit).
