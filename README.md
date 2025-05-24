
# COSC3126 – Data Mining Assignment 3

## 📘 Project Title: Bayesian and Ensemble Approaches for Obesity Prediction and Sentiment Analysis

This repository contains the full code, datasets, evaluation results, and visualizations for **Assignment 3** of the COSC3126 Data Mining course at RMIT University. The project explores **Naïve Bayes and advanced data mining techniques** to solve two key problems:
1. **Multi-class classification of obesity levels** using physiological and lifestyle data.
2. **Sentiment classification of short text reviews** using bag-of-words and probabilistic classifiers.

---


## 🎯 Objectives

- Evaluate **Naïve Bayes** vs advanced classifiers on **obesity classification** and **sentiment tasks**.
- Apply **ensemble methods** (Random Forest, MLP, AdaBoost) for improved accuracy.
- Conduct **clustering**, **association rule mining**, and **feature selection**.
- Design a **hybrid ensemble model** combining Random Forest, Logistic Regression, and MLP with soft voting.

---

## 🧪 Techniques Used

### Task 1: Obesity Level Classification
- Dataset: *Obesity.csv* (2,111 records, 7 obesity classes)
- Models: OneR, J48, Naïve Bayes, Logistic Regression, MLP, KNN, AdaBoost
- Metrics: Accuracy, F1-score, Confusion Matrix
- Key Finding: Random Forest achieved the highest accuracy (95.3%) with selected features.

### Task 1.2: Sentiment Classification
- Dataset: Amazon, IMDB, Yelp (3,000 labeled sentences)
- Models: Naïve Bayes, BayesNet
- Techniques: Bag-of-Words, TF-IDF, N-Grams
- Result: Naïve Bayes had superior ROC performance; BayesNet slightly better in cross-validation accuracy.

### Task 2: Advanced Data Mining
- Dataset: *Online Shoppers Purchasing Intention Dataset*
- Techniques: KMeans Clustering (K=3), Apriori Association Rules, Random Forest feature selection
- Hybrid Ensemble: Random Forest + Logistic Regression + MLP with soft voting
- Result: Achieved 96.1% accuracy with 30% faster training and improved interpretability

---

## 📈 Key Results

| Task                     | Best Model        | Accuracy | Key Insight |
|--------------------------|-------------------|----------|-------------|
| Obesity Classification   | Random Forest     | 95.3%    | Synthetic oversampling boosts class balance |
| Sentiment Analysis       | Naïve Bayes (ROC) | 76.2%    | Simpler models work with TF-IDF |
| Shopper Prediction       | Hybrid Ensemble   | 96.1%    | Feature selection + voting improves efficiency |

---

## 🔧 Dependencies

- Python 3.8+
- pandas, numpy, scikit-learn
- seaborn, matplotlib
- nltk (for sentiment preprocessing)
- mlxtend (for association rules)

---

## 👨‍🏫 Course Information

- Course: **COSC3126 – Data Mining**
- Institution: **RMIT University**
- Semester: **2025 Semester 1**
- Group: **Group 2**

---

## 📚 References

Includes:
- Zhou (2012) – Ensemble Methods
- Heckerman (1996) – Bayesian Networks
- Komarek (2004) – Logistic Regression for Data Mining  

---

## 📌 License

This project is for academic use only. © 2025 Group 2 – COSC3126 RMIT.
