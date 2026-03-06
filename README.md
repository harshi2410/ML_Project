# ML_Project
**Lung Cancer Prediction using Machine Learning**
**Project Overview**
This project focuses on predicting the likelihood of lung cancer using multiple machine learning algorithms. The objective is to analyze health-related features such as smoking habits, anxiety, fatigue, chronic disease, and other symptoms to determine whether a patient may have lung cancer.
The dataset used for this project is sourced from Kaggle and contains several attributes related to lifestyle and medical conditions.
By applying different machine learning models, we compare their performance using evaluation metrics such as accuracy, precision, recall, and F1-score.

**Team Members**
Name	Models Implemented
Siddhesh:Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree
Harshita:Random Forest, Support Vector Machine (SVM), Neural Network (MLP)

**Dataset**
Dataset: Lung Cancer Dataset
Source: Kaggle
Features in dataset include:
Gender
Age
Smoking
Yellow Fingers
Anxiety
Peer Pressure
Chronic Disease
Fatigue
Allergy
Wheezing
Alcohol Consumption
Coughing
Shortness of Breath
Chest Pain

**Target Variable:**
LUNG_CANCER (Yes / No)

Machine Learning Models Used
Models Implemented by Siddhesh
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree Classifier

Models Implemented by Harshita
Random Forest Classifier
Support Vector Machine (SVM)
Neural Network (MLP Classifier)

**Technologies Used**
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
GitHub
Repository hosted on GitHub.

**Project Workflow**
Data Collection
Data Preprocessing
Data Visualization
Feature Encoding and Scaling
Train-Test Split
Model Training
Model Evaluation
Performance Comparison
Evaluation Metrics

The models are evaluated using the following metrics:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC Curve
Data Visualization

Various graphs are used to understand the dataset and model performance:
Correlation Heatmap
Lung Cancer Distribution Plot
Confusion Matrix
Feature Importance Graph
Model Performance Comparison Chart

**Repository Structure**
lung-cancer-ml-prediction
│
├── 01_logistic_regression.ipynb
├── 02_knn.ipynb
├── 03_decision_tree.ipynb
├── 04_random_forest.ipynb
├── 05_svm.ipynb
├── 06_neural_network.ipynb
│
├── lung_cancer.csv
└── README.md

How to Run the Project
Clone the repository
git clone https://github.com/yourusername/lung-cancer-ml-prediction.git
Open the notebooks using Google Colab or Jupyter Notebook.
Run the cells sequentially to train and evaluate the models.
Expected Outcome
The project compares multiple machine learning models and identifies which algorithm performs best for lung cancer prediction based on evaluation metrics.
Future Improvements
Hyperparameter tuning
Larger medical datasets

Deep learning models

Deployment using web applications
