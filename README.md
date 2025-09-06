# **📊 Patient Readmission Prediction Using Machine Learning**
# **📌 Project Overview**

This project focuses on predicting hospital patient readmission rates using Machine Learning. By analyzing patient demographics, medical history, and hospital records, the system identifies high-risk patients who are more likely to be readmitted. The model leverages data preprocessing, feature engineering, visualization, and classification algorithms to deliver accurate and actionable insights for healthcare providers.

# **⚙️ Features**

Data Preprocessing: Handling missing values, label encoding categorical data, and removing outliers.

Visualization: Count plots, histograms, and heatmaps to uncover hidden patterns and correlations.

Feature Engineering: Improved dataset quality through encoding, IQR-based outlier removal, and correlation analysis.

Model Building: Implemented Decision Tree Classifier, chosen for its interpretability and ability to handle mixed data types.

Hyperparameter Tuning: Optimized model performance with GridSearchCV.

Model Evaluation: Assessed using Accuracy, Precision, Recall, Jaccard Score, and Log Loss.

Improved Accuracy: Achieved a 6.7% increase in accuracy after optimization.

Prediction on New Data: Model predicts whether a patient will be readmitted (1: Yes, 0: No).

# **🛠️ Tech Stack**

Python

NumPy – Numerical computations

Pandas – Data manipulation and analysis

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning model and evaluation

# **📂 Workflow**

Import Libraries – Load Python packages for data processing and ML.

Load Dataset – Patient records with demographics and medical history.

Data Preprocessing – Handle missing data, encode categorical variables, and remove outliers.

Visualization – Explore patterns in features and relationships with readmission.

Feature Engineering – Refine dataset for better model input.

Model Building – Train Decision Tree Classifier.

Hyperparameter Tuning – Optimize with GridSearchCV.

Model Training & Evaluation – Train the model and evaluate using multiple metrics.

Prediction – Classify new patient data as Readmitted (1) or Not Readmitted (0).

# **📊 Results**
<img width="837" height="391" alt="image" src="https://github.com/user-attachments/assets/2a0f9af0-1f93-4542-a021-210ffe211fe1" />

Model Accuracy Improved by 6.7% after hyperparameter tuning.

Provided better insights into key factors driving patient readmissions.

Enabled hospitals to proactively identify and manage high-risk patients.

# **🚀 Future Enhancements**

Integration with real-time hospital databases and wearable health devices.

Deployment as a Web or Mobile App for hospital use.

Advanced models like Random Forest, XGBoost, and Deep Learning for higher accuracy.

Incorporation of NLP for analyzing doctors’ notes and patient feedback.

📌 Conclusion

This system demonstrates the power of machine learning in healthcare analytics, offering a scalable and interpretable solution for predicting patient readmissions. By improving prediction accuracy, it helps optimize hospital resources, reduce costs, and enhance patient care.
