# twitter-sentiment-analysis-using-machine-learning
Twitter Sentiment Analysis using Machine Learning 
# Twitter Sentiment Analysis

## 📌 Project Overview
This project performs **sentiment analysis on Twitter data** to classify tweets as
**positive or negative** using machine learning techniques.

The model is trained and evaluated using the **Sentiment140 dataset**, which contains
1.6 million labeled tweets collected via the Twitter API.

---

## 📊 Dataset Description
**Dataset Name:** Sentiment140  
**Source:** Kaggle  

🔗 Dataset Link:  
https://www.kaggle.com/datasets/kazanova/sentiment140

### Dataset Details:
- Total tweets: 1,600,000
- Labels:
  - `0` → Negative sentiment
  - `4` → Positive sentiment
- Tweet fields include:
  - Polarity
  - Tweet text
  - User information (ignored in this project)

⚠️ The dataset file is **not uploaded** to this repository due to size limitations.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## ⚙️ Project Workflow
1. Dataset loading and inspection  
2. Text preprocessing:
   - Lowercasing
   - Removing URLs, mentions, special characters
   - Stopword removal
   - Stemming  
3. Feature extraction using **TF-IDF Vectorization**  
4. Model training using machine learning algorithms  
5. Model evaluation using accuracy and performance metrics  

---

## 🤖 Machine Learning Models
- Logistic Regression  
- Naive Bayes  

---

## 📈 Results
The trained model achieves good accuracy in classifying tweet sentiments
into positive and negative categories.

---


git clone https://github.com/your-username/twitter-sentiment-analysis.git

