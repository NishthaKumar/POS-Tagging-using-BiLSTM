# 🧠 POS-Tagging-using-BiLSTM

A mini NLP deep learning project that implements **Part-of-Speech (POS) Tagging** using a **Bidirectional LSTM (BiLSTM)** model trained on the **NLTK Treebank** dataset.  

This project demonstrates how recurrent neural networks can learn the contextual dependencies between words in a sentence to accurately predict their grammatical roles (noun, verb, adjective, etc.).

---

## 📌 Project Overview

Part-of-Speech Tagging is a fundamental task in **Natural Language Processing (NLP)** where each word in a sentence is labeled with its grammatical tag (like NN for noun, VB for verb, etc.).  
This project uses a **BiLSTM** architecture that captures both **past and future context** to predict each tag effectively.

---

## 🧩 Features
- Uses **NLTK Treebank corpus** for training and testing  
- Implements **Bidirectional LSTM** for sequential learning  
- Handles **variable-length sequences** using padding  
- Includes **word and tag encoding** for model input/output  
- Evaluates model accuracy and predicts POS tags for custom sentences  

---

## 🛠️ Technologies Used
- **Python 3**
- **TensorFlow / Keras**
- **NLTK**
- **NumPy**
- **scikit-learn**

---

## 📁 Dataset

The project uses the **Treebank dataset** available in NLTK:
```python
from nltk.corpus import treebank
