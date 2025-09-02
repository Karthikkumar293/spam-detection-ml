
---

# 🚀 Spam Detection System

An intelligent email spam detection system powered by **Logistic Regression**.  
Built as part of a machine learning journey to explore text classification.

##  ✨ Features
- Preprocessing of raw email text
- Feature extraction using TF-IDF
- Logistic Regression classifier
- Model evaluation with accuracy, precision, recall, and F1-score

## 🛠 Tech Stack
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## 📊 Workflow
1. Dataset loaded (`mail_data_1.csv`)
2. Text data cleaned and processed
3. Labels encoded into numerical format
4. TF-IDF used for text representation
5. Logistic Regression applied for classification
6. Performance evaluated with standard metrics

## ⚡ Quickstart

git clone <repo-url>
cd spam-detection
pip install -r requirements.txt
jupyter notebook spam_dectection.ipynb

# 📈 Results 

Accuracy: >90%

Balanced precision and recall


# 📂 Dataset: mail_data_1.csv

This dataset contains email/text messages labeled as **spam** or **ham (not spam)**.  
It is used for training and evaluating machine learning models for spam detection.

## 📊 Dataset Overview
- **File Name:** `mail_data_1.csv`
- **Format:** CSV (comma-separated values)
- **Rows:** N (number of samples in dataset)
- **Columns:**
  - `label` → The class of the message (`spam` or `ham`)
  - `message` → The raw email/text message

## 🔍 Example Records
| label | message |
|-------|---------|
| ham   | "Hello, how are you doing today?" |
| spam  | "Congratulations! You've won a free lottery. Claim now." |
| ham   | "Let's catch up tomorrow after work." |

## ✅ Usage
This dataset is designed for **binary text classification** tasks:
- Train ML models (Logistic Regression, Naive Bayes, SVM, etc.)
- Perform feature extraction using TF-IDF or CountVectorizer
- Evaluate with metrics (accuracy, precision, recall, F1-score)

## ⚠️ Notes
- The dataset may contain duplicates or noisy data → cleaning recommended.
- Ensure proper preprocessing


