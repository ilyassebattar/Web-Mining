# 🛒 E-commerce Opinion Analysis — Web Mining & NLP

## 📌 Project Overview

This project presents a complete Web Mining and Natural Language Processing (NLP) pipeline for large-scale sentiment analysis of Amazon customer reviews.

The objective is to automatically extract customer opinions, identify key discussion topics, and provide explainable sentiment predictions through an interactive dashboard.

---

## 🎯 Objectives

- Collect and process large-scale customer reviews
- Perform sentiment classification using Deep Learning
- Discover hidden semantic topics in customer feedback
- Explain model predictions using Explainable AI techniques
- Visualize insights through an interactive dashboard

---

## 📊 Dataset

- Source: Amazon Customer Reviews
- Volume: **60,000 reviews**
- Language: English
- Data Type: Textual customer feedback

---

## 🛠 Technologies Used

| Category | Tools |
|-----------|--------|
| Programming | Python |
| NLP | DistilBERT |
| Topic Modeling | BERTopic |
| Explainable AI | SHAP |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Web Application | Streamlit |

---

## 🚀 Methodology

### 1. Data Collection & Preprocessing
- Cleaning and normalization of review texts
- Removal of noise and irrelevant content
- Preparation of training and testing datasets

### 2. Sentiment Analysis
- Fine-tuning of DistilBERT for sentiment classification
- Prediction of positive and negative customer opinions

**Model Performance**

| Metric | Score |
|----------|---------|
| F1-Score | **0.927** |

---

### 3. Topic Extraction
Using BERTopic to automatically identify major discussion themes within customer reviews.

Examples of extracted topics:
- Product Quality
- Delivery Experience
- Customer Service
- Pricing
- Product Features

---

### 4. Statistical Validation
- Chi-Square (χ²) statistical tests
- Validation of relationships between topics and sentiment classes

---

### 5. Explainable AI
Integration of SHAP for model interpretability:

- Feature importance visualization
- Local prediction explanations
- Improved model transparency

---

### 6. Interactive Dashboard
Development of a Streamlit application allowing users to:

- Explore customer sentiments
- Visualize extracted topics
- Analyze model explanations
- Interact with review statistics

---

## 📈 Results

- Analysis of **60,000 Amazon reviews**
- DistilBERT Fine-Tuning
- F1-Score: **0.927**
- Automated topic discovery using BERTopic
- Explainable predictions using SHAP
- Interactive Streamlit dashboard

---

## 📂 Repository Structure

```
Web-Mining/
│
├── Projet_Web.ipynb
├── README.md
├── data/
├── models/
├── outputs/
└── dashboard/
```

---

## 👨‍💻 Author

**Ilyasse Battar**

4th Year Engineering Student  
Data Science & Artificial Intelligence  
EMSI – Morocco

LinkedIn: www.linkedin.com/in/ilyasse-battar

---

## ⭐ Project Highlights

✅ Web Mining Pipeline  
✅ Natural Language Processing (NLP)  
✅ DistilBERT Fine-Tuning  
✅ BERTopic Topic Modeling  
✅ SHAP Explainability  
✅ Streamlit Dashboard
