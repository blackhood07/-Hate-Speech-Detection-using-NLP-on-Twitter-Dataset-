# Model Descriptions: Hate Speech Detection Project

This document outlines all the machine learning and deep learning models developed for the project "Hate Speech Detection using NLP on Twitter Dataset" by Musharaf Maqbool.

## I. Classical Machine Learning Models with Basic Embeddings

### 1. Count Vectorizer / TF-IDF + Multinomial Naive Bayes
- Embedding: Bag of Words / TF-IDF
- Classifier: Multinomial Naive Bayes
- Precision: 0.75
- Recall: 0.79
- F1 Score: 0.77

### 2. Count Vectorizer / TF-IDF + Logistic Regression
- Embedding: Bag of Words / TF-IDF
- Classifier: Logistic Regression
- Precision: 0.68
- Recall: 0.84
- F1 Score: 0.73

## II. Deep Learning Models with BERT Embeddings

### 3. BERT + MLP (Undersampling)
- Embedding: BERT
- Classifier: Multilayer Perceptron
- Technique: Undersampling
- Precision: 0.84
- Recall: 0.84
- F1 Score: 0.84

### 4. BERT + MLP (No Sampling)
- Embedding: BERT
- Classifier: Multilayer Perceptron
- Precision: 0.88
- Recall: 0.70
- F1 Score: 0.76

### 5. BERT + MLP + SMOTE
- Embedding: BERT
- Classifier: Multilayer Perceptron
- Technique: SMOTE (Oversampling)
- Precision: 0.93
- Recall: 0.93
- F1 Score: 0.93

### 6. BERT + LSTM + SMOTE
- Embedding: BERT
- Classifier: LSTM
- Technique: SMOTE
- Precision: 0.95
- Recall: 0.95
- F1 Score: 0.95

## III. MPNet Sentence Embeddings with Recurrent Models

### 7. MPNet + BiLSTM + SMOTE
- Embedding: MPNet
- Classifier: BiLSTM
- Precision: 0.89
- Recall: 0.89
- F1 Score: 0.89

### 8. MPNet + LSTM + SMOTE
- Embedding: MPNet
- Classifier: LSTM
- Precision: 0.89
- Recall: 0.88
- F1 Score: 0.89

## IV. Google Sentence T5 Embeddings with Recurrent Models

### 9. T5 + LSTM + SMOTE
- Embedding: Google Sentence T5
- Classifier: LSTM
- Precision: 0.87
- Recall: 0.87
- F1 Score: 0.87

### 10. T5 + BiLSTM + SMOTE
- Embedding: Google Sentence T5
- Classifier: BiLSTM
- Precision: 0.88
- Recall: 0.88
- F1 Score: 0.88

## V. RoBERTa Sentence Embeddings with Recurrent Models

### 11. RoBERTa + LSTM + SMOTE
- Embedding: RoBERTa
- Classifier: LSTM
- Precision: 0.88
- Recall: 0.87
- F1 Score: 0.87

### 12. RoBERTa + BiLSTM + SMOTE
- Embedding: RoBERTa
- Classifier: BiLSTM
- Precision: 0.87
- Recall: 0.86
- F1 Score: 0.86

## VI. ELECTRA Sentence Embeddings with Recurrent Models

### 13. ELECTRA + LSTM + SMOTE
- Embedding: ELECTRA
- Classifier: LSTM
- Precision: 0.76
- Recall: 0.76
- F1 Score: 0.76

### 14. ELECTRA + BiLSTM + SMOTE
- Embedding: ELECTRA
- Classifier: BiLSTM
- Precision: 0.77
- Recall: 0.74
- F1 Score: 0.73
