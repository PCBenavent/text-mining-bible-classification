# Biblical Text Genre Classification

This project applies Natural Language Processing (NLP) techniques to classify biblical text fragments into literary genres.

## Objective

The goal is to determine whether linguistic patterns can be used to distinguish between different genres:
- Narrative
- Poetry
- Prophetic
- Epistle
- Legal

## Methodology

- Text preprocessing
- TF-IDF vectorization (unigrams and bigrams)
- Supervised classification using:
  - Naive Bayes
  - Logistic Regression
  - Linear SVM

## Results

The models achieve an accuracy close to 0.88–0.89.  
SVM provides the best performance.

The results show that genre classification is feasible using simple and interpretable models.

## Dataset

The dataset is based on publicly available biblical texts:
https://www.kaggle.com/datasets/phyred23/bibleverses

## Author

Pablo Cebrián Benavent
