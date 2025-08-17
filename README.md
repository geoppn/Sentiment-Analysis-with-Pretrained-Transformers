# Sentiment Analysis with Pretrained Transformers  
*AI II – Deep Learning for Natural Language Processing, Spring 2024-2025*

This project implements sentiment classifiers for English-language Twitter data by fine-tuning two **pretrained transformer models** using **PyTorch**:  

- **BERT** (Bidirectional Encoder Representations from Transformers)  
- **DistilBERT** (a smaller, faster distilled version of BERT)  

It is a follow-up to Homework 2, moving from Word2Vec-based deep neural networks to transformer-based models.

## Features & Workflow
- **Data Processing:** Cleaning and preparing Twitter text for transformer models  
- **Modeling:** Fine-tuning BERT and DistilBERT with hyperparameter tuning, regularization, and reproducibility via random seeds  
- **Evaluation:**  
  - Kaggle: **accuracy**  
  - Report: **accuracy, precision, recall, F1-score**  
- **Visualization:** High-quality plots to illustrate model performance, check for underfitting/overfitting  
