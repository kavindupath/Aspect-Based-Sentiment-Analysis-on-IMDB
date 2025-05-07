# aspect-sentiment-imdb
This repository contains the implementation of an Aspect-Based Sentiment Analysis (ABSA) model based on deep learning techniques. 

## Overview
This project implements an Aspect-Based Sentiment Analysis (ABSA) model using deep learning techniques applied to the IMDB Movie Review Dataset. The aim is to detect sentiments towards specific aspects of a movie (e.g., acting, direction, story) using neural architectures such as LSTM, Attention, and Multi-Head Attention in TensorFlow/Keras.

## 🎯 Project Goal
To extend traditional sentiment classification into a more fine-grained **aspect-based sentiment analysis**, identifying specific aspects in IMDB movie reviews and classifying the sentiment toward each aspect using a neural network approach.

---

## 📚 Methodology

- Conducted baseline sentiment analysis using IMDB reviews (as per Chollet, 2021, Chapter 11).
- Implemented an ABSA system based on neural networks.
- Incorporated word embeddings and custom aspect-extraction logic.
- Trained and evaluated the model with proper metrics and visualization.

---

## Experiments Implemented
Three model architectures were tested:
- LSTM + Attention (Base Model)
- 2-layer LSTM + Attention
- LSTM + Multi-Head Attention
  
Each model is trained for 10 epochs and evaluated on a separate test set to measure accuracy. 

---

## 📦 Dataset

- **Source**: IMDB Movie Reviews Dataset  
- **Reference**: Chollet (2021) – Deep Learning with Python, 2nd Edition  
- 50,000 labeled movie reviews (positive/negative)

---

## 🧪 Technologies Used

- Python 3.10+
- TensorFlow / Keras
- NumPy / Pandas
- Matplotlib / Seaborn
- NLTK / Scikit-learn

---
This project was developed as part of Assignment 2 for the subject **CSCI446/946** at the **School of Computing and Information Technology, University of Wollongong**.

