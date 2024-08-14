# Emotion-Classifier-NLP-Project
This project is focused on building an emotion classification model using natural language processing (NLP) techniques and machine learning algorithms. The main objective is to classify text data into different emotional categories, such as happiness, sadness, anger, etc.
The project involves several key steps:

1. Data Cleaning and Preprocessing: The text data is cleaned by removing user handles, special characters, and stopwords to prepare it for analysis.
2. Feature Extraction: Text data is converted into numerical features using the CountVectorizer method, enabling the machine learning models to process the input.
3. Model Building: Two models are built for emotion classification: Logistic Regression and Naive Bayes. These models are trained on a labeled dataset and evaluated based on accuracy and other metrics.
4. Evaluation: The models are evaluated using accuracy scores, classification reports, and confusion matrices. Additionally, prediction probabilities are calculated and visualized to understand the confidence of the models in their predictions.
5. Model Saving: The trained Logistic Regression model is saved using the Joblib library for future use.
This project demonstrates the use of NLP and machine learning to analyze text data and classify it into predefined emotional categories, making it useful for applications such as sentiment analysis, customer feedback analysis, and more.
