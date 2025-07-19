🛳️ Titanic Survival Prediction

This project uses the famous Titanic dataset to build a logistic regression model for predicting passenger survival. The notebook includes data preprocessing, visualization, model training, and evaluation.
📁 Project Structure

titanic-analysis/
├── titanic_notebook.ipynb       # Main Jupyter Notebook with code & outputs
├── requirements.txt             # (Optional) Python packages used
└── README.md                    # This file

📊 Dataset Overview

    Source: Kaggle Titanic: Machine Learning from Disaster

    Fields include:

        Survived (target variable)

        Pclass, Sex, Age, SibSp, Parch, Fare, etc.

🔍 Key Steps

    Data Cleaning

        Dropped irrelevant columns like Name and Ticket

        Handled missing values in Age and Embarked

    Feature Encoding

        Converted categorical features like Sex into numeric format

    Feature Scaling

        Used StandardScaler to normalize the data

    Modeling

        Applied Logistic Regression (sklearn)

        Tried different solvers and tuned iterations

    Evaluation

        Accuracy Score

        Classification Report

        Feature importance visualization using coefficient values

📈 Results

The logistic regression model achieved reasonable accuracy in predicting survival. Feature importance was visualized to understand the effect of each feature.
🚀 Getting Started

git clone https://github.com/yourusername/titanic-analysis.git
cd titanic-analysis
jupyter notebook

🛠️ Requirements (optional)

If you'd like, include a requirements.txt with packages like:

pandas
numpy
matplotlib
seaborn
scikit-learn

Install with:

pip install -r requirements.txt

📌 License

This project is for educational purposes only
