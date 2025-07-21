Metro Train APU Fault Detection Using Machine Learning
This project uses machine learning techniques to detect potential faults or abnormal behaviors in Metro Train Auxiliary Power Units (APUs). By analyzing operational data and applying predictive algorithms, this solution aims to support condition-based maintenance and improve railway safety and efficiency.

🔍 Features
Data Loading and Cleaning from CSV-based operational logs

Exploratory Data Analysis (EDA) using:

Bar plots

Violin plots

Histograms

Scatter plots

Correlation heatmaps

Label Encoding to convert categorical data into numeric format

SMOTE for balancing imbalanced fault vs. non-fault classes

Train-Test Split for model training and evaluation

Implemented Classifiers:

Naive Bayes

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Decision Tree

Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

Confusion matrix with heatmaps

Visualization of model performance

Fault Type Classification Output

🧠 ML Workflow Overview
Data upload and cleaning

EDA to understand feature relationships

Preprocessing using LabelEncoder and SMOTE

Splitting into training and testing data

Training classifiers and evaluating performance

Predicting APU fault types

🛠️ Technologies Used
Python

Jupyter Notebook

pandas, numpy, seaborn, matplotlib for data handling and visualization

scikit-learn for modeling

imblearn for SMOTE resampling

🧪 Applications
Metro train maintenance management

Early detection of APU failures

Predictive analytics in railway systems

📈 Future Enhancements
Integration with real-time metro data feeds

Deep learning approaches for time-series forecasting

Dashboard for live fault detection and alerts
