# House-Loan-Data-Analysis
This project analyzes housing loan data to understand loan default patterns and build machine learning models to predict whether a customer is likely to default on a loan. The project includes data analysis, class imbalance handling, machine learning, and deep learning models.

📌 Project Overview

Financial institutions need to identify risky borrowers before approving loans. In this project, we analyze loan data and build predictive models that help determine the probability of a borrower defaulting on a loan.

During the analysis, it was observed that only about 8% of borrowers default, which creates a class imbalance problem. To address this, resampling techniques were applied before training models.

📊 Dataset Analysis

The dataset contains borrower information and a TARGET column where:

0 → Non-defaulter

1 → Defaulter

Key observations:

Default rate ≈ 8.07%

Data is highly imbalanced

Requires techniques such as Random Under Sampling

⚙️ Technologies Used

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning models

Imbalanced-learn – Handling imbalanced datasets

TensorFlow / Keras – Deep learning model

🔍 Project Workflow
1️⃣ Data Loading

Load loan dataset using Pandas

Inspect dataset structure

2️⃣ Data Cleaning

Check missing values

Understand target distribution

3️⃣ Class Imbalance Handling

Applied RandomUnderSampler

Balanced the dataset for better model training

4️⃣ Data Visualization

Target distribution plots

Comparison of imbalanced vs balanced dataset

5️⃣ Machine Learning Model

A Logistic Regression model was trained to predict loan defaults.

Evaluation metrics used:

Recall

Classification Report

ROC-AUC Score

6️⃣ Feature Scaling

Applied StandardScaler to normalize input features.

7️⃣ Deep Learning Model

A Neural Network model was implemented using TensorFlow/Keras with:

Dense layers

Dropout for regularization

Binary Crossentropy loss

Adam optimizer

📈 Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

ROC-AUC Score

These metrics help understand how well the model identifies potential loan defaulters.

🚀 Results

Identified strong class imbalance in the dataset

Applied resampling techniques to improve model learning

Implemented Logistic Regression and Deep Learning models

Evaluated model performance using multiple metrics

📁 Project Structure
House-Loan-Default-Prediction
│
├── House_Loan_Data_Analysis.ipynb
├── dataset
├── README.md
🎯 Learning Outcomes

Through this project, I learned:

Handling imbalanced datasets

Applying resampling techniques

Building machine learning models

Implementing deep learning models

Evaluating models using ROC-AUC and classification metrics.
