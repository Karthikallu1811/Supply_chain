# Supply_chain

🚚 Supply Chain Analytics & Machine Learning Project


Overview:

This project focuses on analyzing and optimizing supply chain operations using data analytics and machine learning. The objective was to evaluate supplier performance, product profitability, shipping efficiency, and operational KPIs, and build a predictive model to forecast product demand.

The project was developed in Google Colab using Python, covering the complete workflow from exploratory data analysis to feature engineering and machine learning model deployment.


Technologies & Libraries Used:

1.Python
2.Pandas
3.NumPy
4.Matplotlib
5.Seaborn
6.Scikit-learn
7.XGBoost
8.Joblib
9.Google Colab


Project Workflow:

The dataset was cleaned and validated to ensure consistency across numerical and categorical variables. Missing values and inconsistencies were handled safely to maintain data integrity.

Exploratory Data Analysis was performed to evaluate product revenue distribution, supplier defect rates, manufacturing lead times, shipping performance, and correlation patterns across operational variables.

Multiple derived features were engineered, including stock turnover, margin estimates, profit margin, cost efficiency, delivery efficiency, and quality index to enhance predictive performance.

Categorical variables such as product type, supplier name, and shipping carriers were encoded using OneHotEncoder, while numerical features were standardized using StandardScaler.

A complete preprocessing pipeline was built using ColumnTransformer to ensure proper scaling and encoding. The final machine learning model was implemented using XGBoost Regressor to predict product demand.

The trained preprocessing pipeline and model were saved using Joblib for future deployment.


Key Business Insights:

Identified high-performing product categories and revenue drivers.

Analyzed supplier lead time and defect rate impact on profitability.

Evaluated shipping cost versus delivery time trade-offs.

Estimated margin performance across suppliers and product segments.

Discovered correlation patterns influencing stock turnover and sales.


Machine Learning Implementation:

Target Variable: Number of Products Sold

Feature Engineering included advanced ratio metrics and efficiency indicators.

Train-Test split applied with reproducible random state.

Preprocessing and model training were combined into a unified pipeline.

Model artifacts were saved for deployment readiness.


What This Project Demonstrates:

*End-to-end data analytics workflow

*Advanced feature engineering

*Business KPI evaluation

*Data preprocessing pipeline design

*Machine learning model development

*Production-ready model saving
