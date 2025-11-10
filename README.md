# 📧 Email Spam Detection using NLP & TF-IDF

Hey there! 
This project is all about detecting **spam emails** using the power of **Natural Language Processing (NLP)** and **Machine Learning**.  
It analyzes email text, cleans it up, and predicts whether it's **Spam 🚨** or **Ham ✅ (Not Spam)** — with over **97% accuracy!**

## 🎯 Goal

Build a machine learning model that can **automatically classify emails** based on their content,  
helping users filter out unwanted spam messages efficiently.

## ⚙️ How It Works  

1. **Text Cleaning & Preprocessing**  
   - Lowercasing, removing URLs, numbers & special characters  
   - Tokenizing words, removing stopwords  
   - Lemmatizing words to their root forms  

2.  **Feature Extraction with TF-IDF**  
   - Converts email text into numerical vectors  
   - Gives more importance to meaningful words like *“win”, “claim”, “offer”*  

3.  **Model Training using Multinomial Naive Bayes**  
   - Simple, fast, and perfect for text-based data  

4.  **Evaluation & Visualization**  
   - Achieved **97.45% accuracy**  
   - Visualized results using a Confusion Matrix heatmap  


## 📈 Model Performance

| Metric | Score |
|:-------|:------:|
| Accuracy | **97.45%** |
| Precision (Spam) | 0.99 |
| Recall (Spam) | 0.91 |
| F1-Score | 0.95 |

The model correctly classifies most emails — even tricky ones that look legit but are spam!

##  How to Run This Project

You can easily try it yourself in 3 simple steps   

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/Email_Spam_Detection.git
