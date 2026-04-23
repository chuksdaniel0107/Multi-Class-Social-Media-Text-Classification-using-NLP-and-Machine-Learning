# Multi-Class Social Media Text Classification using NLP and Machine Learning

## 📌 Overview

This project builds an end-to-end Natural Language Processing (NLP) pipeline to classify social media posts into multiple categories using supervised machine learning models. The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation.

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* NLTK
* Scikit-learn
* WordCloud

---

## 📂 Dataset

The dataset is provided in JSON format and contains:

* Social media post text
* Category labels (multi-class)
* Timestamps

---

## ⚙️ Project Workflow

### 1. Data Loading and Preparation

* Loaded JSON dataset into a Pandas DataFrame
* Explored dataset structure and class distribution
* Filtered top categories for balanced modelling

---

### 2. Exploratory Data Analysis (EDA)

* Visualised class distribution
* Analysed tweet length and text characteristics
* Generated:

  * Word clouds per category
  * Most frequent words
  * Top bigrams
* Created correlation heatmaps and pairplots

---

### 3. Text Preprocessing (NLP)

* Removed:

  * URLs
  * special characters
  * irrelevant tokens
* Converted text to lowercase
* Removed stopwords using NLTK
* Created a clean_text feature for modelling

---

### 4. Feature Engineering

* Applied **TF-IDF vectorization**
* Included **n-grams (unigrams and bigrams)**
* Engineered additional features:

  * Text length
  * Character count
  * Average word length

---

### 5. Model Development

Built and compared multiple machine learning models:

* Logistic Regression
* Support Vector Machine (SVM)
* Naive Bayes

Implemented using **Scikit-learn pipelines** for efficient preprocessing and training.

---

### 6. Model Evaluation

* Evaluated models using:

  * Accuracy
  * Precision, Recall, F1-score
* Generated:

  * Confusion matrices
  * Classification reports
* Plotted:

  * Model performance comparison
  * ROC curves (multi-class AUC analysis)

---

## 📊 Results

* Achieved strong classification performance across multiple categories
* SVM demonstrated the best overall performance in terms of accuracy and F1-score
* Identified class imbalance effects on minority categories

---

## 🚀 How to Run the Project

1. Install dependencies:
   pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud

2. Download NLTK stopwords:
   import nltk
   nltk.download('stopwords')

3. Run the Jupyter Notebook


[Your LinkedIn]
[Your Email]
