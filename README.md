# -Hate-Speech-Detection-using-NLP-on-Twitter-Dataset-
# Hate Speech Detection on Twitter Using NLP

This project explores the detection of hate speech from tweets using various machine learning and deep learning models, including transformers. It was completed as part of an internship at IIT Indore under the mentorship of Dr. Nagendra Kumar.

## 📝 Project Summary

- **Dataset**: Kaggle Twitter Hate Speech Dataset (binary classification: hate vs. non-hate)
- **Techniques**: Classical ML (Naïve Bayes, Logistic Regression), Deep Learning (MLP, LSTM, BiLSTM), Transformers (BERT, RoBERTa, MPNet, T5, Electra)
- **Embeddings**: CountVectorizer, TF-IDF, BERT, MPNet, etc.
- **Sampling**: SMOTE, Undersampling
- **Frameworks**: TensorFlow, Keras, NLTK, scikit-learn

## 📁 Repository Structure

- `data/`: Details about the dataset and preprocessing.
- `models/`: Model architecture explanations.
- `notebooks/`: Jupyter notebooks for preprocessing and training models.
- `results/`: Performance metrics and evaluation tables.
- `report/`: Contains the original PDF report.
- `requirements.txt`: Dependencies needed to run the project.

## 📊 Results

| Model | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Count Vectorizer + Naïve Bayes | 0.75 | 0.79 | 0.77 |
| TF-IDF + Logistic Regression | 0.68 | 0.84 | 0.73 |
| BERT + MLP + SMOTE | 0.93 | 0.93 | 0.93 |
| BERT + LSTM + SMOTE | 0.95 | 0.95 | 0.95 |
| MPNet + BiLSTM + SMOTE | 0.89 | 0.89 | 0.89 |

(See full results in `results/performance_metrics.md`)


