# BanglaBlend: Sadhu-Cholito Text Classification

## Overview

BanglaBlend is a Bangla text classification project focused on distinguishing between two major Bangla writing styles:

- Cholito (চলিত)
- Sadhu (সাধু)

The project evaluates Machine Learning, Deep Learning, and Transformer-based approaches.

## Dataset

The final processed dataset contains:

- 7,053 text samples
- 3,600 Cholito samples
- 3,453 Sadhu samples
- No duplicate or conflicting texts

## Models

### Machine Learning
- Logistic Regression
- Naive Bayes
- Support Vector Machine
- Random Forest

### Deep Learning
- CNN
- BiLSTM
- GRU
- MLP

### Transformers
- Bangla-BERT
- Bangla Sentence Transformer
- Bangla-BERT Base
- DistilBERT Multilingual
- XLM-R
- MuRIL

## Evaluation

All models are evaluated using 3-fold cross-validation.

Metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Cohen's Kappa
- Matthews Correlation Coefficient (MCC)

## Explainability

Layer Integrated Gradients (LIG) with Captum is used for model explainability.

## Best Model

Based on the 3-fold comparison, MuRIL achieved the highest mean F1-score among the successfully evaluated models.

## Project Structure

- data/
- src/
- results/
- notebooks/
- docs/

## Technologies

Python, PyTorch, Hugging Face Transformers, Scikit-learn, Captum, Google Colab, and GitHub.
