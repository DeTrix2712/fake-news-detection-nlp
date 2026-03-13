# Fake News Detection Using Natural Language Processing

## Overview

This project explores various machine learning and deep learning models for fake news detection. It evaluates the effectiveness of different text preprocessing techniques, such as stemming, lemmatization, and naive preprocessing, to enhance model performance. The primary dataset used for training and testing is the ISOT Fake News Dataset, and the project achieves an accuracy of 98.61% using Long Short-Term Memory (LSTM).

## Dataset

- **ISOT Fake News Dataset**: A dataset containing 44,898 labeled articles (21,417 real and 23,481 fake).
- **Secondary Dataset**: A Kaggle dataset used to test model generalization.

## Preprocessing Techniques

- **Naive Preprocessing**: Removed stopwords, converted text to lowercase, and kept structure intact for deep learning models.
- **Stemming**: Reduced words to their root forms (e.g., “running” to “run”).
- **Lemmatization**: Converted words to their base forms, considering context (e.g., “better” to “good”).

## Models

Several models were implemented and compared:
- **Logistic Regression**
- **Support Vector Classifier (SVC)**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**
- **Long Short-Term Memory (LSTM)**: Best-performing model with 98.61% accuracy.

## Results

The models were evaluated based on accuracy, precision, recall, and F1-score. LSTM outperformed other models, with naive preprocessing leading to the best performance across all models.

| Model          | Accuracy (ISOT) | F1-Score |
|----------------|-----------------|----------|
| LSTM           | 98.61%          | 0.93     |
| Logistic Reg.  | 98.60%          | 0.92     |
| Random Forest  | 98.31%          | 0.91     |
| SVC            | 98.34%          | 0.89     |

## Usage

After installing the required libraries and datasets, you can train and evaluate the models using the Jupyter notebook located in CSCI594_Final_Project.ipynb, where the entire workflow from preprocessing to evaluation is implemented.

## Acknowledgments

- ISOT Fake News Dataset
- Kaggle Datasets
- Special thanks to my collaborators Rakhat Myrzakhan, Merey Bissenbin, Kuanysh Murat, Galymzhan Turysbekov, and Arman Sydikov.
