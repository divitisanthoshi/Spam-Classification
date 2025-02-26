# Spam Classification

This project builds a spam classifier for SMS messages using natural language processing (NLP).

## 📌 Features
- **Dataset:** SMS messages labeled as *Spam* or *Ham*.
- **Preprocessing:** Includes tokenization, stopword removal, lemmatization, and feature extraction using TF-IDF.
- **Machine Learning Model:** Uses Multinomial Naive Bayes for classification.
- **Evaluation:** Analyzes accuracy, confusion matrix, and classification reports.

## 🚀 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Spam-Classification.git
   cd Spam-Classification
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## 🏠 Usage
1. Run the classifier:
   ```sh
   python spam_classification.py
   ```
2. Predict if a message is spam:
   ```python
   message = "Congratulations! You have won a free prize."
   prediction = model.predict([message])
   print(prediction)
   ```

## 📊 Results
- Achieved **98% accuracy** using a Naive Bayes classifier.
- Displays a confusion matrix for model evaluation.
- 

