# Digikala Sentiment Analysis

This project performs **sentiment analysis** on Digikala product comments using **machine learning**. It also demonstrates **text preprocessing**, **TF-IDF vectorization**, **SVM classification**, and **clustering** of comments.

## Features

- **Text Preprocessing:** Tokenization, stopword removal, and stemming using Hazm (Persian NLP library).  
- **Sentiment Classification:** Classify comments into `recommended`, `not_recommended`, and `no_idea`.  
- **Clustering:** Group comments with similar content using KMeans.  

## Dataset

The original dataset is **not included** in this repository due to its large size.  
You can download it from Kaggle:  
[Digikala Comments and Products Dataset](https://www.kaggle.com/datasets/radeai/digikala-comments-and-products/suggestions)


## Requirements

- Python 3.8+  
- pandas  
- scikit-learn  
- imbalanced-learn  
- hazm  
- matplotlib  
- wordcloud  

Install dependencies using:  
```bash
pip install -r requirements.txt
