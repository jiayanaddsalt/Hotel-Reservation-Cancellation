# Hotel-Reservation-Cancellation

Author: Jiayan Li

**Data Source**: https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset

This project is about training a classifier to identify which hotel reservations are likely to be canceled. This is a supervised learning - binary classification task. 

Rather than scratch the surface of multiple models, I choose to dive deep into one of the most basic models—Decision Tree.
My goals for modeling are:
1. Compare over- vs. under-sampling
2. Explore both manual parameter tuning and GridSearch
3. Explore a simplified tree that is computationally and data cheap, because in business settings, it’s not all about precision and recall, it’s more about cost/quality ratio

data: stores the raw dataset and preprocessed dataset
classification.ipynb: stores the codes of the complete pipeline from data preprocessing to fine tuning model parameters.