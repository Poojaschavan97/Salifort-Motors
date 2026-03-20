Salifort Motors — Employee Attrition Analysis & Prediction
Python • Pandas • Scikit-learn • Matplotlib • Seaborn
An end-to-end HR analytics project — identifying the key drivers of employee attrition and building a predictive model to help HR teams make data-driven retention decisions.

The Problem
High employee attrition costs organisations significantly in hiring, onboarding, and lost productivity. Salifort Motors needed to understand why employees were leaving and who was most at risk — before they resigned.

Results
MetricRandom ForestLogistic RegressionAccuracy~0.98BaselineF1-Score~0.95—Dataset size15,000+ HR records—Class imbalance handledYes — class_weightYes
Top attrition drivers identified:

Workload imbalance was the strongest predictor of employee churn
Low job satisfaction combined with no promotion in 3+ years nearly doubled attrition risk
Salary band was a significant retention factor, particularly at mid-tenure (3–5 years)


Project Workflow
Raw HR Data → Cleaning & Deduplication → EDA → Feature Engineering → Modelling → Business Recommendations
Data Preprocessing

Removed duplicates and handled missing values across 15,000+ records
Encoded categorical variables, scaled numerical features
Addressed class imbalance using Scikit-learn class_weight

Exploratory Data Analysis

Identified workload and satisfaction as primary attrition drivers
Visualised relationships between tenure, salary, promotion history, and turnover
Statistical interpretation of feature distributions and correlations

Feature Engineering

Created meaningful derived features from existing HR attributes
Reduced multicollinearity before model training
Selected predictors based on feature importance scores

Machine Learning

Built and compared Logistic Regression and Random Forest classifiers
Evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrix
Random Forest selected as final model based on F1-score performance


Key Business Recommendations

Flag employees with high workload + low satisfaction scores for proactive manager check-ins
Implement a structured promotion review cycle for employees past the 3-year mark
Reassess salary bands at the mid-tenure stage — this is the highest-risk attrition window
Build an internal early-warning dashboard tracking these 3 signals monthly


Tech Stack
LayerToolsData processingPython, Pandas, NumPyVisualisationMatplotlib, SeabornML modelsScikit-learn (Random Forest, Logistic Regression)EnvironmentJupyter Notebook


About
Built by Pooja Chavan — Data Analyst | M.Sc. Mathematics (CGPA 9.75)
