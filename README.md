Smart Lender - Loan Approval Prediction System
📌 Project Overview

Smart Lender is a Machine Learning-based web application that predicts whether a loan application is likely to be approved based on applicant details. The project uses data preprocessing, exploratory data analysis, feature engineering, SMOTE for class balancing, and classification algorithms to provide accurate loan approval predictions.

🚀 Features
Loan approval prediction using Machine Learning
Data preprocessing and missing value handling
Categorical feature encoding
Exploratory Data Analysis (EDA)
Univariate, Bivariate, and Multivariate Analysis
SMOTE for balancing the dataset
Feature scaling using StandardScaler
Model training and evaluation
Flask web application for prediction
User-friendly interface
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-learn (SMOTE)
Flask
HTML
CSS
Bootstrap
Pickle
📂 Project Structure
Smart-Lender/
│
├── dataset/
│   └── loan_prediction.csv
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
├── training/
│   └── loan_prediction.ipynb
│
├── app.py
├── rdf.pkl
├── scale.pkl
├── requirements.txt
├── README.md
└── .gitignore
📊 Dataset

The dataset contains applicant information including:

Gender
Married
Dependents
Education
Self Employed
Applicant Income
Coapplicant Income
Loan Amount
Loan Amount Term
Credit History
Property Area
Loan Status
🔍 Data Preprocessing
Handling missing values
Encoding categorical variables
Feature transformation
Data type conversion
Feature scaling
Dataset balancing using SMOTE
📈 Exploratory Data Analysis

The project performs:

Univariate Analysis
Bivariate Analysis
Multivariate Analysis

Visualizations include:

Distribution Plot
Count Plot
Swarm Plot
Heatmap
Correlation Matrix
🤖 Machine Learning Models

The following algorithms were evaluated:

Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Classifier
K-Nearest Neighbors (KNN)

The best-performing model is saved using Pickle and used for predictions.

🌐 Web Application

The Flask application allows users to enter loan details through a web interface and predicts whether the loan will be approved.

⚙️ Installation

Clone the repository

git clone https://github.com/yourusername/Smart-Lender.git

Move into the project folder

cd Smart-Lender

Install required packages

pip install -r requirements.txt

Run the Flask application

python app.py

Open your browser

http://127.0.0.1:5000/
📊 Model Workflow
Import Libraries
Load Dataset
Data Cleaning
Exploratory Data Analysis
Handle Missing Values
Encode Categorical Variables
Apply SMOTE
Feature Scaling
Train-Test Split
Model Training
Model Evaluation
Save Model
Deploy using Flask
📸 Screenshots
Home Page
Loan Prediction Form
Prediction Result
Data Analysis Graphs



🎯 Future Enhancements
Improve prediction accuracy using XGBoost
Deploy on Render or Railway
Add user authentication
Store prediction history
Create dashboard with analytics
