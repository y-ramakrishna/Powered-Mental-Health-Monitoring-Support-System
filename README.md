# Powered-Mental-Health-Monitoring-Support-System
Developed an AI-powered system leveraging NLP and Explainable AI (LIME) to analyze textual data for early identification of mental health indicators, focusing on transparently explaining model predictions.

## Project Overview

This project develops an Artificial Intelligence system designed to provide preliminary insights into potential mental health states (e.g., stress, anxiety, depression, suicidal ideation) by analyzing textual data, such as simulated journal entries or social media posts. A core focus of this project is Explainable AI (XAI), which ensures transparency by showing *why* the model makes a particular prediction, thereby building trust and providing actionable insights.

**Disclaimer:** This tool is developed for academic and demonstrative purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. If you or someone you know is experiencing mental health concerns, please seek help from a qualified healthcare professional.

## Features

Text Classification:Categorizes textual input into relevant mental health-related classes (e.g., 'suicide', 'non-suicide' based on the dataset used).
Natural Language Processing (NLP):Utilizes standard NLP techniques for text cleaning, tokenization, and feature extraction.
Machine Learning Model: Employs a robust classification algorithm to predict mental health states.
Explainable AI (LIME):Provides local, interpretable explanations for each prediction, highlighting the specific words or phrases that most influenced the model's decision.
Interactive Web Application (Streamlit):A user-friendly interface for real-time text analysis and explanation (deployment coming soon / deployed via Streamlit Cloud).

## Why Explainable AI (XAI)?

In sensitive domains like mental health, understanding *why* an AI model arrives at a particular conclusion is paramount. Black-box models, while powerful, lack the transparency needed for critical applications. By incorporating LIME, this project aims to:
1.Build Trust:Users can see which parts of their text led to a specific prediction.

2.Aid Interpretation: Researchers or practitioners can gain insights into patterns the model learns.

3.Facilitate Debugging:Understanding misclassifications becomes easier by analyzing the contributing factors.

## Technical Stack

Language: Python
Core Libraries:
    `pandas`, `numpy`: Data manipulation and numerical operations.
    `nltk`, `re`, `string`: Natural Language Processing (text cleaning, lemmatization, stop words).
    `scikit-learn`: Machine Learning (TF-IDF vectorization, Logistic Regression for classification, model selection, evaluation metrics)
    `lime`: Local Interpretable Model-agnostic Explanations (for XAI).
    `joblib`: Model persistence (saving/loading trained models).
    `streamlit`: For building the interactive web application.
Environment: Kaggle Notebooks for development, local environment for Streamlit app.
Version Control:Git & GitHub

## Dataset

This project utilizes the "Suicide and Depression Detection" dataset sourced from Kaggle. This dataset typically contains Reddit posts labeled as 'suicide' or 'non-suicide'.

Ethical Note:The dataset consists of publicly available Reddit posts. All data used is anonymized and utilized strictly for academic research and demonstration. Strict disclaimers are in place within the application to prevent misuse or misinterpretation of predictions.
