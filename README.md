📧 Spam Email Classifier – NLP Machine Learning Project

The Spam Email Classifier is a machine learning project built using Natural Language Processing (NLP) techniques to automatically detect whether an email or message is Spam or Not Spam (Ham). With the rising volume of digital communication, spam filtering is essential for security, fraud prevention, and inbox management. This project builds a complete end-to-end pipeline, from preprocessing raw text to final message prediction.

📝 Project Overview

This project demonstrates how machine learning can classify textual data by leveraging NLP preprocessing and probabilistic algorithms. The workflow begins with cleaning raw email text, removing unnecessary elements such as punctuation, stopwords, special characters, and converting text into meaningful tokens.

After preprocessing, text is transformed into numerical form using TF-IDF Vectorization, which effectively captures the importance of words across messages. These vectorized features are fed into a Multinomial Naive Bayes classifier — one of the most effective and widely used algorithms for text classification.

The model is evaluated using Accuracy, Precision, Recall, and F1-Score, with its overall performance visualized through a Confusion Matrix Heatmap. Additionally, the project includes a feature that allows users to input their own messages and instantly receive predictions, demonstrating real-world applicability.

This project highlights core concepts of NLP, feature engineering, supervised learning, and model evaluation, making it an ideal addition to any machine learning or data science portfolio.

🎯 Objectives

Clean and preprocess raw message text

Convert text into numerical features using TF-IDF

Train a Multinomial Naive Bayes classifier

Evaluate the model using standard ML metrics

Visualize confusion matrix for better understanding

Predict new/unseen messages entered by the user

📂 Dataset Used

The project uses the SMS/Email Spam Collection Dataset, which contains:

label — spam or ham

message — text content of each email/SMS

🔄 Project Workflow

Load dataset with Pandas

Clean and preprocess the message text

Apply TF-IDF vectorization

Split dataset into training and testing sets

Train Naive Bayes classifier

Make predictions

Evaluate performance

Plot confusion matrix

Predict custom email messages in real time

📊 Model Visualization
🔹 Confusion Matrix Heatmap

This heatmap clearly shows how many emails were correctly and incorrectly classified.

📬 Sample Predictions
Message	Model Output
“Congratulations! You won a $500 prize! Click here to claim.”	Spam
“Hello, the report for tomorrow’s meeting is attached.”	Ham
“Your bank account is at risk. Confirm your identity immediately.”	Spam
“Your order has been shipped and will arrive tomorrow.”	Ham

These examples highlight how effectively the model identifies real-world spam patterns.
