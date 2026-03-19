# 🧠 RNN-Based Sentiment Analysis

## 📌 Project Overview

This project implements a **Recurrent Neural Network (RNN)** using PyTorch to perform **sentiment analysis** on text data.
The model classifies text reviews as **positive or negative** based on learned patterns.

---

## 🚀 Features

* Text preprocessing (cleaning, tokenization)
* TF-IDF / vectorized input representation
* RNN model built using PyTorch
* Binary sentiment classification
* Training and evaluation pipeline
* Accuracy calculation on test data

---

## 🧠 Model Architecture

* Input Layer (vectorized text)
* RNN Layer (captures sequential patterns)
* Fully Connected Layer
* Sigmoid Activation (for binary output)

---

## ⚙️ Tech Stack

* Python
* PyTorch
* NumPy
* scikit-learn
* Pandas
* Regex 


---

## 📂 Dataset

* Text review dataset (binary sentiment)
* Labels:

  * `1` → Positive
  * `0` → Negative

---

## 🔄 Workflow

```text
Text Data
   ↓
Preprocessing (remove HTML tags, urls, puntuations, stop words, cleaning, normalization)
   ↓
Vectorization (TF-IDF)
   ↓
Train-Test Split
   ↓
RNN Model Training
   ↓
Evaluation (Accuracy)
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/RNN-Sentiment-Analysis.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook RNNSentimentAnalysis.ipynb
```

---

## 📊 Results

* Model trained over multiple epochs
* Achieved reasonable accuracy on test dataset
* Outputs probability scores for sentiment classification

---
## 🚀 Future Improvements

* Replace TF-IDF with Tokenizer + Embeddings
* Use LSTM or GRU for better performance
* Add dropout for regularization
* Deploy using Streamlit or Flask
* Improve dataset size and diversity


## ⭐ Acknowledgment

If you found this project helpful, please give it a ⭐ on GitHub!
