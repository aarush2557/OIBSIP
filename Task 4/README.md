# 📧 Email Spam Detection using Machine Learning

## 📌 Project Overview

This project implements an **Email Spam Detection System** using **Natural Language Processing (NLP)** and **Machine Learning**. The model classifies messages as **Spam** or **Ham (Legitimate)** by preprocessing text, extracting features with **TF-IDF**, and training machine learning classifiers.

This project was completed as **Task 4** of the **Oasis Infobyte Internship (OIBSIP)**.

---

## 🎯 Objective

Build a binary classification model that can accurately distinguish spam emails/messages from legitimate ones using NLP techniques and machine learning algorithms.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* WordCloud

---

## 📂 Dataset

The project uses the **SMS Spam Collection Dataset**, containing labeled messages as:

* **Ham** – Legitimate messages
* **Spam** – Unwanted or promotional messages

---

## ✨ Features

* Data loading and exploration
* Class distribution analysis
* Text preprocessing

  * Lowercase conversion
  * Punctuation removal
  * Number removal
  * Stopword removal
* TF-IDF Vectorization
* Train-Test Split
* Multinomial Naive Bayes Classifier
* Logistic Regression Classifier
* Model Evaluation

  * Accuracy
  * Precision
  * Recall
  * F1-Score
  * Confusion Matrix
* Spam and Ham WordCloud Visualization
* Custom Message Prediction

---

## 📊 Machine Learning Models

### 1. Multinomial Naive Bayes

A widely used probabilistic classifier for text classification tasks due to its simplicity and efficiency.

### 2. Logistic Regression

A supervised learning algorithm used for binary classification that performs well on TF-IDF features.

---

## 📈 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📸 Project Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Data Cleaning
5. Text Preprocessing
6. TF-IDF Feature Extraction
7. Train-Test Split
8. Train Machine Learning Models
9. Evaluate Performance
10. Generate WordClouds
11. Test Custom Messages

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Open the project folder.

```bash
cd Email-Spam-Detection
```

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open **Email_Spam_Detection.ipynb** and run all cells.

---

## 📁 Project Structure

```text
Email-Spam-Detection/
│
├── Email_Spam_Detection.ipynb
├── spam.csv
├── README.md
└── requirements.txt
```

---

## 📌 Results

The project successfully classifies spam and legitimate messages using machine learning techniques. Both classifiers achieve strong performance, with **Multinomial Naive Bayes** serving as an effective baseline for text classification.

---

## 🚀 Future Improvements

* Lemmatization and stemming
* Hyperparameter tuning
* Deep Learning models (LSTM/Bi-LSTM)
* Transformer-based models (BERT)
* Flask/Streamlit web application deployment
* Real-time email spam detection API

---

## 👨‍💻 Author

**Aarush Tyagi**

BCA (AI & Data Science) Student

---

## 📜 License

This project is created for educational and internship purposes under the **Oasis Infobyte Internship Program (OIBSIP)**.
