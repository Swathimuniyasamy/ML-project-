The project uses the Telco Customer Churn dataset from IBM, and applies a binary classification model using Logistic Regression.
🎯 Objective
    To build a machine learning model that can:
       Accurately classify customers into "Churned" or "Stayed". Help businesses take preventive action to retain at-risk customers
📂 Dataset
    Source: IBM Telco Customer Churn Dataset
    Columns: 21 Features including:
    Customer tenure
    Monthly charges
    Total charges
    Internet service type
    Contract type
    Payment method, and more.
    Target column: Churn (Yes / No)
⚙️ Machine Learning Model
    Model Used: Logistic Regression (Linear Classification)
    Classification Type: Binary Classification
Libraries:
    pandas
    scikit-learn
    matplotlib / seaborn (optional for visuals)
✅ Steps Performed
    Loaded and cleaned the dataset (removed missing/invalid values)
    Encoded categorical features using One-Hot Encoding
    Split data into training and testing sets
    Trained a Logistic Regression model
    Evaluated accuracy and classification report
    Predicted churn for a new customer sample
📊 Results
   Model Accuracy: ~78.5%

Precision (Churned): ~0.618

Recall (Churned): ~0.503

F1 Score: ~0.555
