#AI-Powered-Sentiment-Analysis

# Project Overview
A machine learning project designed to analyze and classify text-based data into distinct emotional states. The model leverages Natural Language Processing (NLP) to detect sentiment (Positive, Negative, or Neutral) with high precision, bridging the gap between raw text and actionable insights.

# Model Performance & Analytics
The sentiment analysis engine was developed using a robust classification pipeline, yielding the following performance indicators:

Accuracy: 85.44% on unseen validation data.

Model Architecture: Logistic Regression chosen for its efficiency in high-dimensional text classification.

Vectorization Strategy: TF-IDF Vectorization to prioritize meaningful terms over common stop words.

Contextual Analysis: Implementation of Bi-gram (1,2) modeling to preserve phrase-level context and linguistic nuances.

Data Source: Trained on the Amazon Fine Food Reviews dataset, leveraging over 560,000 annotated samples.

# System Architecture
The application integrates a dual-layered technical stack:

Machine Learning Core: A Python-based pipeline utilizing NLTK for advanced text normalization and Scikit-learn for statistical modeling.

Deployment Layer: A Flask web framework providing a lightweight API to serve model predictions in real-time.

Connectivity: Integrated Ngrok tunneling to facilitate external access and public URL testing for the local development server.

# Key System Features
Automated Preprocessing: A custom pipeline for case folding, lemmatization, and noise reduction (URL/special character removal).

Real-time Inference Engine: A backend process that transforms raw user input into feature vectors for immediate classification.

Dynamic Web Dashboard: A responsive frontend interface that visualizes sentiment scores and classification results instantly.

File Inventory
Sentiment_Analysis_Pipeline.ipynb: The central development notebook containing data preprocessing, model training, and the Flask server deployment.

Technical_Analysis_Report.pdf: Detailed documentation of the experimental setup, methodology, and evaluation metrics.

templates/: Directory housing the Semantic HTML5 files that define the web application's user interface.

