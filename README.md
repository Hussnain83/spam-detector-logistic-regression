# 📧 Spam Message Detector using Logistic Regression

This project is a machine learning solution designed to classify SMS messages as either **Spam** or **Ham (Not Spam)** using Logistic Regression. It demonstrates the power of natural language processing combined with basic machine learning algorithms to solve real-world classification problems.

---

We have used the dataset of spam2.csv for training our model.

## 📌 Project Overview

The aim of this project is to detect unwanted spam messages by training a model on a dataset of labeled SMS messages. This is achieved through a carefully constructed ML pipeline that includes text preprocessing, feature extraction using TF-IDF, and Logistic Regression for classification. Additionally, SMOTE is applied to address class imbalance and improve recall for the minority class (spam messages).

---

## 🧠 Key Features

- Logistic Regression classifier with strong performance
- Text preprocessing including lowercasing, punctuation removal, stopword removal, and lemmatization
- TF-IDF vectorization for transforming text data into numeric features
- Class imbalance handled using SMOTE (Synthetic Minority Oversampling Technique)
- Evaluation with metrics such as Accuracy, Precision, Recall, and F1 Score
- Confusion matrix visualization
- Real-time message prediction using a saved pipeline
- Clean and reusable pipeline with modular steps

---

## 📊 Model Performance

The final model achieved excellent results, particularly in terms of precision and recall. This makes it effective at catching spam messages while minimizing false positives. The confusion matrix shows a strong balance between detecting ham and spam, confirming the model’s readiness for real-world testing.

---

## ⚙️ Workflow Summary

1. Collected and loaded SMS data
2. Preprocessed text (cleaning + lemmatization)
3. Converted text to numeric vectors using TF-IDF
4. Balanced the dataset using SMOTE
5. Trained a logistic regression model
6. Evaluated using standard classification metrics
7. Built a prediction pipeline for real-time use
8. Saved the model for future predictions

---

## 💾 Model Deployment

The final trained pipeline is saved using joblib, enabling seamless integration for real-time predictions. With this setup, a new message can be passed to the pipeline and the system will automatically process and classify it as spam or not.

---

## 🚀 Future Improvements

- Explore alternative models like KNN, Random Forest, or SVM
- Enhance dataset with more recent or diverse messages
- Experiment with deep learning (e.g., LSTM or BERT)

---

## 📜 License

This project is intended for educational and non-commercial use. Contributions and suggestions are welcome.

---

## 👤 Author

**[Muhammad Hussnain Dogar]**  
Machine Learning Enthusiast  
GitHub: [Hussnain83]

---

