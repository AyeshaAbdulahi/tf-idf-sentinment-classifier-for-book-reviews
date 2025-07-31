# TF-IDF-SENTINMENT-CLASSIFIER-FOR-BOOK-REVIEWS
Overview
This project implements a sentiment analysis model using TF-IDF vectorization to classify book reviews as positive or negative. The goal is to gain insights into customer sentiment based on review data. The model uses logistic regression for classification and evaluates performance through metrics such as accuracy, F1-score, precision, recall, and log loss.

Features
Data Cleaning: Eliminated white spaces, converted text to lowercase, and removed special characters.

Feature Extraction: Used TF-IDF vectorizer to convert text into meaningful feature vectors.

Model: Logistic Regression classifier applied to the transformed feature vectors.

Hyperparameter Tuning: Optimized the regularization parameter C to enhance model performance.

Evaluation Metrics: Accuracy, precision, recall, F1-score, and log loss used to assess the model’s performance.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/TF-IDF-Sentiment-Classifier.git
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Preprocess the dataset.

Train the model using logistic regression.

Tune hyperparameters for optimal results.

Visualize performance metrics.

Results
After applying the model, various metrics were calculated to assess its performance, with hyperparameter tuning improving results.
