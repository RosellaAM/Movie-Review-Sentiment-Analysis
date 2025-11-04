# Film Review Sentiment Analysis - Negative Review Detection System

[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0%2B-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![NLP](https://img.shields.io/badge/Natural--Language-Processing-blueviolet)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Film Review Sentiment Analysis** is a natural language processing solution for Film Junky Union that automatically detects negative movie reviews from IMDB data. The project addresses the community's need to filter and categorize film reviews through binary sentiment classification models achieving an F1 score exceeding 0.85.

## 📊 Project Overview
Film Junky Union, a cutting-edge community for classic film enthusiasts, requires an automated system to filter negative reviews. This project implements multiple machine learning models to classify IMDB movie reviews as positive or negative, with rigorous evaluation and comparison of different approaches.

## 🚀 Results (FILL THESE ARE EXAMPLES)
The final **Logistic Regression with TF-IDF** model demonstrated:
- **F1 Score: 0.87** (exceeding the target of 0.85)
- **Accuracy: 86%** on test data
- **Precision: 0.85** for negative review detection
- **Recall: 0.89** for capturing true negative reviews
- Robust performance across different review styles and lengths

## 💼 Business Impact (FILL THESE ARE EXAMPLES)
- **Content Filtering**: Automatic categorization of negative reviews for community moderation
- **User Experience**: Enhanced community engagement through better content organization
- **Scalable Moderation**: Reduced manual effort in review management
- **Data-Driven Insights**: Understanding sentiment patterns in film criticism

## 🎯 Core Skills
* **Text Preprocessing**: Tokenization, lowercasing, stopword removal, and text normalization
* **Exploratory Data Analysis**: Class distribution analysis, text length examination, and linguistic pattern identification
* **Feature Engineering**: TF-IDF vectorization, n-gram analysis, and text representation strategies
* **Model Comparison**: Evaluation of Logistic Regression, Gradient Boosting, and alternative classifiers
* **Hyperparameter Tuning**: Grid search optimization for maximum F1 performance
* **NLP Techniques**: Text vectorization, sentiment analysis, and feature importance interpretation
* **Model Evaluation**: Comprehensive analysis using F1-score, precision, recall, and confusion matrices
* **Statistical Validation**: Cross-validation and hypothesis testing for model reliability

## 🛠️ Tech Stack
* **Machine Learning** → Scikit-learn, XGBoost
* **NLP Processing** → NLTK, SpaCy (optional)
* **Text Vectorization** → TF-IDF, CountVectorizer
* **Backend** → Python 3.8+, Pandas, NumPy
* **Visualization** → Matplotlib, Seaborn, WordCloud
* **Development** → Jupyter Notebooks

## Local Execution
1. Clone the repository:

git clone https://github.com/RosellaAM/Movie-Review-Sentinent-Analysis.git

2. Install dependencies:

pip install -r requirements.txt

3. Run analysis:

  jupyter notebook notebooks/sentiment_analysis_reviews.ipynb
