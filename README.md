# Machine-Learning-Spam-Mails-Detection

### Project Overview
This project focuses on developing and evaluating machine learning models to classify emails as spam or non-spam (ham). We applied traditional machine learning models and deep learning techniques to achieve high accuracy and efficiency. A key highlight of the project is the use of Particle Swarm Optimization (PSO) for feature selection, which significantly improved model performance and reduced computational overhead.

### Dataset
Source: Kaggle's Spam Mails Dataset.\
Entries: 4,601 emails.\
Features: 56 features describing email attributes such as word frequency, capital letters, and other spam-related characteristics.\
Target Variable: Binary classifier (1 = Spam, 0 = Ham).

### Machine Learning Models Used

**Traditional Models**:
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
k-Nearest Neighbors (KNN)

**Deep Learning Models**:
Recurrent Neural Networks (RNN)
Convolutional Neural Networks (CNN)

**Evaluation Metrics**
Models were assessed using multiple metrics to ensure a comprehensive evaluation:
Accuracy, Balanced Accuracy
Precision, Recall, F1-Score
ROC AUC, PR AUC
Matthews Correlation Coefficient (MCC)
Cohen Kappa Score

### Training and testing times were also compared.
Performance Before and After Feature Selection, Results are stored in two Excel sheets:\
model_evaluation_metrices_.xlsx (before feature selection).\
model_evaluation_metrices_after_feature_selection.xlsx (after feature selection).
