🛡️ Phishing Detection using Machine Learning

This project implements several machine learning models to classify websites as phishing or legitimate based on extracted features from a dataset.

 Dataset

- The dataset file must be named `dataset.csv`.
- It should contain a target column named `Result` or `label`.

 How to Run

1. Clone the repository:

   bash
   git clone https://github.com/yourusername/phishing-detector.git
   cd phishing-detector
(Optional) Create a virtual environment:

bash

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies
pip install -r requirements.txt
Run the main script:


python phishing_detection.py
📦 Requirements
Include the following in requirements.txt:


pandas
numpy
scikit-learn
xgboost
lightgbm
catboost

Models Used
Decision Tree

Random Forest

AdaBoost

Gradient Boosting (XGBoost, CatBoost, LightGBM, Histogram-Based)

Logistic Regression

KNN

MLP (Neural Network)

SVM (Linear, Poly, RBF, Sigmoid)
