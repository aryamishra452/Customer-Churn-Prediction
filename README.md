# Customer-Churn-Prediction

This project focuses on building a machine learning model to predict customer churn for a telecommunications company, enabling proactive customer retention strategies.

#🎯Goal
To develop a highly accurate classification model that identifies customers at high risk of churning based on their account and service data.

#✨ Key Findings (from EDA)
-Contract Type: Customers on Month-to-month contracts are the most likely to churn.
-Internet Service: High correlation between Fiber optic service and churn.
-Support: Lack of services like Online Security or Tech Support increases churn risk.
-Tenure: Newer customers with low tenure are at higher risk.

#🛠️ Methodology and Models
-Data Preprocessing: Handled missing values, cleaned features, and applied Label Encoding to convert categorical data into numerical format.
-Modeling: Trained and compared various models (Logistic Regression, Random Forest, KNN, SVC, etc.).
-Final Model: An Ensemble Voting Classifier was selected for its balanced and robust predictive performance.

#📈 Results
Final Accuracy Score~81.6%
Churn (Yes) F1-Score~62%

#🚀 Future Scope
Streamlit Web AppThe next phase of this project is to deploy the trained model into an interactive web application using Streamlit. This application will allow business stakeholders to:
-Input new customer features.
-Receive real-time churn predictions.
-Visualize model performance and feature importance.
-Guide retention teams with actionable insights and intervention strategies.

#⚙️ Technologies Used
-Python 3.x
-Pandas & NumPyScikit-learn (Machine Learning)
-Seaborn & Plotly (Visualization)
-Streamlit (Planned Deployment)
