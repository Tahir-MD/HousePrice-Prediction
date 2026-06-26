# House Price Prediction - Machine Learning Project

A complete machine learning solution for predicting house prices using Linear Regression. This project implements a full data science pipeline from data loading and preprocessing to model training, evaluation, and deployment.

# 🏠 Project Overview

This project predicts house prices based on various features such as location, number of rooms, population density, and median income. It demonstrates end-to-end machine learning workflow including data exploration, feature engineering, model training, and evaluation.

# 📊 Dataset

The project uses the California Housing Dataset which contains:

· 20,640 samples of housing districts
· 8 numerical features + 1 categorical feature
· Target variable: median_house_value

# Features:

· longitude, latitude: Geographic coordinates
· housing_median_age: Median age of houses
· total_rooms: Total number of rooms
· total_bedrooms: Total number of bedrooms
· population: Total population in block
· households: Total number of households
· median_income: Median income of households
· ocean_proximity: Proximity to ocean (categorical)

# 🚀 Features

· Complete Data Pipeline: Loading, cleaning, and preprocessing
· Exploratory Data Analysis: Visualizations and statistical analysis
· Feature Engineering: Handling categorical variables, correlation analysis
· Model Training: Linear Regression implementation
· Model Evaluation: RMSE and R² score calculation
· Results Visualization: Actual vs Predicted plots, residual analysis
· Model Persistence: Save trained model using pickle

# 📈 Results

The trained Linear Regression model achieves:

· RMSE (Root Mean Square Error): ~$68,000
· R² Score: ~0.65
· Interpretable coefficients showing feature importance

# 🛠️ Installation & Requirements

Prerequisites

· Python 3.8+
· pip package manager

Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
# SynTecxHub_ML_Intership_Week_02

# Spam Detection - Machine Learning Project

A complete machine learning solution for detecting spam messages using Natural Language Processing (NLP) techniques. This project implements an end-to-end pipeline from text preprocessing to model deployment with an interactive CLI interface.

# 📧 Project Overview

This project classifies SMS messages as either "Spam" (unwanted/unsolicited messages) or "Ham" (legitimate messages). It demonstrates comprehensive NLP workflow including text preprocessing, feature extraction, model comparison, evaluation, and deployment.

# 📊 Dataset

The project uses the SMS Spam Collection Dataset which contains:

· 5,572 SMS messages
· 2 classes: Ham (legitimate) and Spam
· Class distribution:

· Ham messages: 4,827 (87%)
· Spam messages: 747 (13%)

# Features:

· Message: Raw text content of SMS
· Label: 'ham' or 'spam' (target variable)
· Clean_Message: Preprocessed text after cleaning and stemming

# 🚀 Features

· Complete Text Pipeline: Cleaning, stemming, stopword removal
· Exploratory Data Analysis: Class distribution visualization
· Feature Engineering: TF-IDF Vectorization for text to numerical conversion
· Model Comparison: Naive Bayes vs Logistic Regression
· Model Evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
· Results Visualization: Side-by-side confusion matrix comparison
· Model Persistence: Save best pipeline using joblib
· Interactive CLI: Real-time spam detection interface

# 📈 Results

The trained models achieve:

· Naive Bayes Accuracy: 96.5%
· Logistic Regression Accuracy: 97.8%
· Precision (Spam): 0.99
· Recall (Spam): 0.92
· F1-Score: 0.95

# 🛠️ Installation & Requirements

Prerequisites

· Python 3.8+
· pip package manager

# Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk joblib
```

Download NLTK Data

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

# Interactive CLI Mode

```bash
==================================================
SPAM DETECTOR CLI
==================================================
Type 'quit' to exit

Enter your message: Congratulations! You've won a lottery!
==================================================
MESSAGE: Congratulations! You've won a lottery!
PREDICTION: Spam
==================================================
```

# 📊 Model Comparison

Model Accuracy Precision (Spam) Recall (Spam) F1-Score
Naive Bayes 96.5% 1.00 0.89 0.94
Logistic Regression 97.8% 0.99 0.92 0.95

# 🔮 Future Improvements

· Add deep learning models (LSTM, BERT)
· Create web application using Flask/Streamlit
· Deploy as REST API using FastAPI
· Add more datasets for better generalization
· Implement real-time email filtering

# 📝 requirements.txt

```
pandas
numpy
matplotlib
seaborn
scikit-learn
nltk
joblib
jupyter
```

# 📌 Acknowledgments

· Syntexhub for the internship opportunity
· UCI Machine Learning Repository for the dataset
· NLTK and Scikit-learn communities for amazing tools

# 📞 Contact & Links

· GitHub Repository: https://github.com/Tahir-MD/SynTecxHub_ML_Intership_Week_02
· LinkedIn: https://www.linkedin.com/in/tahir-mahmood-781b93329?utm_source=share_via&utm_content=profile&utm_medium=member_android
· Email: tahirdool67@gmail.com

---

⭐ If you found this project helpful, please give it a star!

© 2024 Tahir-MD | SynTecxHub Machine Learning Internship - Week 2 Task
