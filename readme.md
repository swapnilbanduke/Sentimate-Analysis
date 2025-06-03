
# 📊 Sentiment Analysis on IMDB Movie Reviews

**Author**: *Swapnil Banduke*  
**Project Type**: NLP | Deep Learning | Comparative Modeling

---

## 🚀 Project Overview

This project performs sentiment analysis on IMDB movie reviews using deep learning models. The objective is to classify reviews as **positive** or **negative** and compare the performance of three popular neural network architectures:  
- Simple Neural Network (SNN)  
- Convolutional Neural Network (CNN)  
- Long Short-Term Memory Network (LSTM)

---

## 🎯 Objective

To build, train, and evaluate multiple deep learning models on the IMDB dataset and determine the most effective architecture for sentiment classification.

---

## 📂 Dataset

- **Source**: [IMDB Sentiment Dataset – Kaggle](https://www.kaggle.com/columbine/imdb-dataset-sentiment-analysis-in-csv-format)  
- **Description**: Contains 50,000 labeled movie reviews from IMDB, evenly split between positive and negative sentiments.

---

## 🔧 Project Workflow

1. **Data Collection**: Downloaded the dataset from Kaggle.
2. **Data Preprocessing**:
   - Cleaned text using regular expressions.
   - Removed stopwords using NLTK.
   - Converted text to sequences using tokenization and word embedding.
3. **Model Building**:
   - Built and trained three models: SNN, CNN, and LSTM.
4. **Evaluation**:
   - Compared models based on Accuracy, Loss, and Confusion Matrix.

---

## 🤖 Models Implemented

| Model | Summary |
|-------|---------|
| **Simple Neural Network (SNN)** | A basic model using embedding and dense layers. |
| **Convolutional Neural Network (CNN)** | Captures local patterns and n-gram features using 1D convolutions. |
| **Long Short-Term Memory (LSTM)** | Captures temporal dependencies using recurrent units, ideal for sequential text data. |

---

## 📦 Required Libraries

Install these libraries to run the project:

```bash
pip install nltk
pip install numpy==1.24.3
pip install pandas==1.5.0
pip install matplotlib==3.6.0
pip install tensorflow==2.6.0
