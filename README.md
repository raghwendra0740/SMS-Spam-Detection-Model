# SMS-Spam-Detection-Model
Developed text analyzer using Multinomial Naive Bayes algorithm and Count Vectorizer, achieving high accuracy on large-scale datasets.
<br>
This is my BTech undergrad Major Project

## 📌 Introduction:-

This project uses Natural Language Processing (NLP) and Machine Learning techniques to classify SMS messages as **Spam** or **Ham (Not Spam)**.

The model is built using **Multinomial Naive Bayes**, which is highly effective for text classification tasks. The project also includes data visualization techniques to better understand the dataset.

---

## ✔️ Accuracy

- **Training Accuracy:** 99.41%  
- **Testing Accuracy:** 98.56%  

---

## 🔍 Workflow

1. **Data Collection**
   - SMS Spam dataset from UCI Machine Learning Repository / Kaggle  

2. **Data Preprocessing**
   - Convert text to lowercase  
   - Remove punctuation  
   - Remove stopwords  
   - Apply stemming using Porter Stemmer  

3. **Data Visualization**
   - Visualization using Matplotlib  
   - WordCloud generation to analyze frequent words in spam and ham messages  

4. **Feature Extraction**
   - CountVectorizer / TF-IDF Vectorizer  

5. **Model Building**
   - Multinomial Naive Bayes algorithm  

6. **Evaluation**
   - Accuracy score  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib  
- WordCloud  

---

## 🧠 Key Insights

- Data visualization helps in understanding word frequency patterns  
- WordCloud highlights commonly used words in spam messages  
- Text preprocessing significantly improves model performance  
- Multinomial Naive Bayes performs efficiently for text classification  

---

## 🏁 Dataset Used

- SMS Spam Collection Dataset (UCI Machine Learning Repository)  
- Also available on Kaggle  

---

## 🚀 How to Run

1. Clone the repository  
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn nltk matplotlib wordcloud
