# 📱 SMS Spam Classifier

A machine learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using NLP techniques and Scikit-learn models.

---

## 🔍 Problem Statement

With the rise of unsolicited messages, SMS spam detection has become essential. The goal of this project is to build a binary classifier that can automatically label a text message as **spam** or **not spam** based on its content.

---

## 🧠 Approach

1. **Text Preprocessing**  
   - Lowercasing  
   - Tokenization  
   - Removing special characters  
   - Removing stop words  
   - Stemming

2. **Feature Extraction**  
   - CountVectorizer  
   - TF-IDF Vectorizer (used for final model)
  
3. **Exploratory Data Analysis**

- WordClouds and Bar Charts for most frequent spam and ham words
- Message length distribution
- Correlation heatmap of engineered features

---

4. **Model Training**  
 Implemented a variety of classification models using **Scikit-learn** and **XGBoost**:

- `LogisticRegression`
- `SVC` (Support Vector Classifier)
- `MultinomialNB` (Naive Bayes)
- `DecisionTreeClassifier`
- `KNeighborsClassifier`
- `RandomForestClassifier`
- `AdaBoostClassifier`
- `BaggingClassifier`
- `ExtraTreesClassifier`
- `GradientBoostingClassifier`
- `XGBClassifier` (from `xgboost`)

Also tried basic techniques to improve model performance such as:
- Feature scaling
- Parameter tuning
- Different vectorizers
- Model ensemble comparisons



5. **Evaluation Metrics**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1 Score  
   - Confusion Matrix

---










