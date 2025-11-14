# NLP Sentiment Analysis on Movie Reviews

## Overview
This project performs Natural Language Processing (NLP) on a corpus of movie reviews to classify sentiment as positive or negative. The workflow includes text cleaning, tokenization, vectorization, and model training using multiple classifiers.

## Objectives
- Preprocess raw text by removing noise (stopwords, punctuation, etc.)  
- Tokenize and vectorize text (Bag-of-Words, TF-IDF)  
- Train ML models for sentiment classification  
- Evaluate performance using accuracy and confusion matrices  

## Dataset
A movie review dataset containing:
- Review text  
- Binary sentiment label (positive/negative)

## Workflow Summary
1. **Text Cleaning**
   - Lowercasing  
   - Removing punctuation  
   - Stopword filtering  
   - Stemming/Lemmatization  

2. **Vectorization**
   - CountVectorizer  
   - TF-IDF transformations  

3. **Model Training**
   - Naive Bayes  
   - Logistic Regression  
   - Support Vector Machines  

4. **Evaluation**
   - Confusion Matrix  
   - Classification Report  

## Results
- Naive Bayes performed best on sparse text data.
- TF-IDF produced strong improvements over raw Bag-of-Words.
- Effective sentiment separation observed.

## Technologies Used
- Python  
- Pandas  
- NumPy  
- NLTK  
- Scikit-Learn  

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```

---

*This project was completed as part of the Python for Data Science and Machine Learning Bootcamp course on Udemy.*
