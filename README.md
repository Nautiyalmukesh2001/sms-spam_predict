![Header](https://raw.githubusercontent.com/mukesh-ai/readme-assets/main/spam-sms-header.png)

# 📱 Spam SMS Detection using Machine Learning

A machine learning project to classify SMS messages as either **"ham"** (not spam) or **"spam"**, leveraging NLP techniques and classification algorithms.

---

## 🚀 Project Overview

This project follows a complete ML workflow for text classification:

1. **Data Loading & Cleaning**  
   - Load the SMS dataset  
   - Remove duplicates and irrelevant columns  
   - Handle missing values

2. **Exploratory Data Analysis (EDA)**  
   - Analyze message distribution (ham vs spam)  
   - Visualize message length, word count, sentence count  
   - Generate word clouds for ham and spam texts

3. **Data Preprocessing**  
   - Lowercasing, tokenization  
   - Remove stopwords, punctuation, and special characters  
   - Apply stemming using NLTK

4. **Model Building**  
   - Convert text to features using **CountVectorizer** and **TfidfVectorizer**  
   - Train models including **Logistic Regression**, **Naive Bayes**, **XGBoost**, and others

5. **Model Evaluation & Selection**  
   - Evaluate models using **accuracy**, **precision**, and **confusion matrix**  
   - Select and save the best-performing model

---

## 📂 Dataset

The dataset used is **`spam.csv`** taken from Kaggle, consisting of SMS messages labeled as:

- `ham` – legitimate messages  
- `spam` – unsolicited messages

---

## 🧰 Dependencies

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud xgboost

---

## ▶️ How to Run

1. Clone this repository or download the project files.  
2. Ensure `spam.csv` is in the same directory as the notebook.  
3. Open the Jupyter Notebook or run it in Google Colab.  
4. Execute the notebook cells sequentially.

---

## 🧱 Code Structure

The notebook is organized into the following sections:

- **Data Loading and Cleaning**  
- **Exploratory Data Analysis (EDA)**  
- **Text Preprocessing**  
- **Model Building**  
- **Model Evaluation**  
- **Model Saving**

---

## ✅ Results

- Multiple classification models were compared.  
- The best model was selected based on accuracy and precision.  
- The **Naive Bayes** model demonstrates strong performance in identifying spam messages.

---


## 🚀 Conclusion

This project demonstrates the practical application of machine learning techniques in Natural Language Processing (NLP) to detect spam messages. It showcases the end-to-end workflow from data cleaning to model deployment readiness, with room for future enhancement.

Feel free to explore the code, try different models, or build on this project for deployment!



