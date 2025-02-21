🚨 Hate Speech Detection using Machine Learning

📌 Overview
This project detects hate speech in text using machine learning techniques. It classifies text as either hate speech or non-hate speech based on labeled data.

🛠️ Technologies Used
Python
Pandas (Data Handling)
Scikit-learn (ML Models)
Label Encoding

📂 Dataset
The dataset is loaded from hatespeech.csv.
Includes text samples labeled as hate speech or non-hate speech.

🏗️ Model Workflow
Data Preprocessing – Converting text data into numerical format
Label Encoding – Transforming categorical labels into numeric form
Feature Extraction – Applying TF-IDF / Count Vectorizer
Model Training – Using Multinomial Naïve Bayes
Evaluation – Accuracy, Precision, Recall

📉 Results
The model effectively identifies hateful text from normal text.

🔥 Future Enhancements
Improve accuracy using Deep Learning models like LSTMs & BERT
Deploy as a web API for real-time hate speech detection
