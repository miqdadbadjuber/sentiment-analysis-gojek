# Sentiment Analysis on Gojek Reviews

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.20-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-88.69%25-28A745?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-00C853?style=for-the-badge)

A Deep Learning project for sentiment classification of Gojek user reviews using TensorFlow and Bidirectional LSTM.

![Training History](assets/training-history.png)

---

## Overview

This project performs sentiment analysis on Gojek application reviews collected from Google Play Store.

The workflow includes:

- Data scraping
- Text preprocessing
- Label encoding
- Deep Learning model training
- Model evaluation
- Confusion Matrix visualization

---

## Dataset

Source:

Google Play Store Reviews (Gojek)

Sentiment Classes

- Positive
- Neutral
- Negative

---

## Features

- Google Play review scraping
- Indonesian text preprocessing
- LSTM & BiLSTM comparison
- EarlyStopping
- Confusion Matrix
- Classification Report
- Accuracy evaluation

---

## Project Structure

```text
sentiment-analysis-gojek/
├── assets/
│   ├── training-history.png
│   └── confusion-matrix.png
├── dataset_gojek.csv
├── scraping.ipynb
├── sentiment_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## Model Performance

| Metric | Value |
|--------|-------:|
| Test Accuracy | **88.69%** |

### Training History

![Training History](assets/training-history.png)

---

## Confusion Matrix

![Confusion Matrix](assets/confusion-matrix.png)

---

## Model Architecture

- Embedding Layer
- Bidirectional LSTM
- Dropout
- Dense Layer
- Softmax Output

---

## Technologies

- Python
- TensorFlow
- Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Future Improvements

- Increase dataset size
- Better class balancing
- Transformer-based models (IndoBERT)
- Hyperparameter tuning
- Deploy using Streamlit

---

## Author

**Miqdad Badjuber**

GitHub: https://github.com/miqdadbadjuber
