# Spam Detection using NLP and Machine Learning

## Overview
This project focuses on detecting spam messages using NLP and machine learning. Text data is preprocessed, vectorized, and then fed into multiple classification algorithms. The performance of each model is evaluated and compared.

## Features
- Data preprocessing: cleaning, tokenization, stopwords removal, and vectorization.
- Multiple classification algorithms:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes
- Performance comparison using accuracy and classification report.
- Visualization of:
  - Spam vs. Ham distribution
  - Model performance comparison

## Dataset
The dataset contains labeled messages as either "spam" or "ham" (non-spam). Each message is a text string that the model uses for training and testing.

## Preprocessing Steps
1. Text cleaning: remove special characters, numbers, and punctuation.
2. Tokenization and lowercase conversion.
3. Stopwords removal using NLTK.
4. Vectorization using CountVectorizer or TF-IDF.

## Machine Learning Models
| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression | 0.95     |
| Random Forest       | 0.98     |
| SVM                 | 0.98     |
| Naive Bayes         | 0.97     |

Random Forest and SVM provided the best performance in detecting spam messages.

## How to Run
1. Clone the repository:
```bash
git clone <your-repo-url>
