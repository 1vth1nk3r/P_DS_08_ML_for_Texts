# Classifying movie reviews
The project from the Machine Learning for Texts sprint of the Practicum DS course.

## Description
Here we have a dataset of IMBD movie reviews with polarity labelling. Our goal is to build a model for classifying positive and negative reviews.

First, we should do some data preprocessing and EDA. Next, we need to normalize, lemmatize and vectorize the texts. Afterward, we could proceed to model development.

## Conclusion
After preprocessing and EDA, we tried two lemmatization methods (using nltk and spacy), vectorized our texts with TF-IDF and built a Logistic Regression model and an LGBM Classifier.  
Our best model uses  NLTK, TF-IDF and LogisticRegression. It shows an F1 score of 0.88 on the test set. Also, it is significantly faster than the other two methods.