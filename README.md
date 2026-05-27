
# Fake News Detection using NLP and BERT
## Overview

This project focuses on detecting fake news articles using Natural Language Processing (NLP) techniques and the BERT (Bidirectional Encoder Representations from Transformers) deep learning model. The system classifies news articles as either Real or Fake based on textual content analysis.

The project demonstrates the use of transformer-based language models for text classification and misinformation detection.

## Features
* Fake vs Real news classification
* Text preprocessing using NLP techniques
* Transformer-based feature extraction using BERT
* Fine-tuning of pretrained BERT model
* Deep learning-based text classification
* Performance evaluation using classification metrics
## Technologies Used
* Python
* TensorFlow / PyTorch
* Hugging Face Transformers
* BERT
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
## Dataset

The dataset contains news articles labeled as:

Fake News
Real News

Dataset features include:

Title
News Text
Label

Dataset Sources:

Kaggle Fake News Dataset
[Link](/kaggle/input/datasets/msaideepak/fake-new-detection-dataset)

## Project Workflow

### 1. Data Collection

Collected labeled fake and real news articles from publicly available datasets.

### 2. Data Preprocessing

Performed NLP preprocessing techniques:

* Lowercasing
* Removing special characters
* Removing stop words
* Tokenization
* Text cleaning
### 3. BERT Tokenization

Used pretrained BERT tokenizer to:

* Convert text into tokens
* Generate attention masks
* Create input embeddings
### 4. Model Building

Built a Fake News Detection model using pretrained BERT:

* BERT Encoder Layer
* Dropout Layer
* Dense Classification Layer
### 5. Model Training

Fine-tuned the BERT model on the fake news dataset using:

* Adam Optimizer
* Cross Entropy Loss
* Batch Training
### 6. Prediction & Evaluation

Classified news articles as fake or real and evaluated performance using multiple metrics.

## Evaluation Metrics

The model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Results
Successfully classified fake and real news articles using BERT
Achieved good classification performance on textual datasets
Improved contextual understanding compared to traditional NLP models

## Author 
Saideepak

## GitHub Repository
(https://github.com/Saideepak2004/fake-news-detection-using-the-NLP-and-BERT.git)
