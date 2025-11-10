# Email Spam Detection using NLP and TF-IDF

This project predicts whether an email is **Spam** or **Not Spam** using **Natural Language Processing (NLP)** and **Machine Learning**.

I built it to understand how text data can be cleaned, processed, and used to train models that make real-world predictions — in this case, detecting unwanted spam messages automatically.

---

## Goal
To build a model that can read email text and accurately classify it as spam or not spam.

---

## How It Works

1. **Data Cleaning**
   - Lowercased all text  
   - Removed URLs, numbers, and special characters  
   - Removed stopwords and applied lemmatization  

2. **Feature Extraction**
   - Used **TF-IDF Vectorizer** to convert text into numerical features  

3. **Model Training**
   - Used **Multinomial Naive Bayes**, which works well for text data  

4. **Evaluation**
   - Accuracy: **97.45%**
   - The model performs well on unseen data and handles most tricky spam emails correctly

---

## Example Predictions
| Email Text | Prediction |
|-------------|-------------|
| “Congratulations! You’ve won a free laptop — click to claim now.” | Spam 🚨 |
| “Hey Rahul, please check the project report attached.” | Not Spam ✅ |

---

## Tech Stack
- Python  
- Pandas, NumPy  
- NLTK  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## Dataset
The dataset used in this project was provided as part of an online course on Machine Learning and Natural Language Processing.

It contains email messages labeled as **spam (1)** or **not spam (0)**.  
The data was used for learning purposes to understand text preprocessing, feature extraction, and model building.

*(Note: Since this dataset was part of a course, I’m not redistributing it here. But any similar “spam vs ham” dataset — such as the one on Kaggle — can be used to reproduce the same results.)*


---

## Future Improvements
- Try Logistic Regression or SVM for comparison  
- Use Word2Vec or BERT for deeper text understanding  
- Build a small web app using Flask or Streamlit  

---

## Author
**Rahul Kumar**  
Machine Learning Enthusiast | Data Science Learner  

If you like this project, feel free to ⭐ the repository!
