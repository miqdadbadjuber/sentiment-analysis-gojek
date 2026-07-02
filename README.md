# Sentiment Analysis on Gojek Reviews

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.20-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-88.69%25-28A745?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-00C853?style=for-the-badge)

A Deep Learning project for sentiment classification of Gojek user reviews using TensorFlow and Bidirectional LSTM.

---

## Overview

This project analyzes user reviews of the Gojek application collected from the Google Play Store.

The workflow covers the complete machine learning pipeline, including:

- Data scraping
- Text preprocessing
- Sentiment labeling
- Model training
- Model evaluation
- Performance visualization

---

## Dataset

Source:

**Google Play Store Reviews (Gojek)**

Sentiment Classes:

- Positive
- Neutral
- Negative

---

## Features

- Google Play review scraping
- Indonesian text preprocessing
- LSTM & Bidirectional LSTM models
- EarlyStopping callback
- Classification Report
- Confusion Matrix
- Training History visualization
- Model performance evaluation

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

The best-performing model uses:

- Embedding Layer
- Bidirectional LSTM
- Dropout
- Dense Layer (ReLU)
- Softmax Output Layer

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
- Improve class balance
- Hyperparameter tuning
- Transformer-based models (IndoBERT)
- Deploy using Streamlit or TensorFlow Serving

---

## Author

**Miqdad Badjuber**

GitHub: https://github.com/miqdadbadjuber
