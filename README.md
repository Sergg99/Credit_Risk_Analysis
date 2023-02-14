# Credit_Risk_Analysis

## Overview:

We used fancy tricks to teach computers how to tell good loans from bad loans, even though there are way more good loans. We tested out lots of different tools, like imbalanced-learn and scikit-learn, to build and check our models. Some of the tools even help fix biases in the data!

Our mission was to:

  - Show how machines learn from data
  - Split data into groups to test and train our models
  - Try out different algorithms like logistic regression, decision trees, random forests, and support vector machines
  - Figure out which algorithm is best for different scenarios
  - Improve our models using resampling and ensemble techniques

Hope that helps!

## Results:

We tested six different machine learning models to see which one could tell good loans from bad loans the best. The results are in:

- The Naive Random Oversampling model did okay, with a balanced accuracy of 0.66.
- The SMOTE Oversampling and Undersampling models were about the same, with a balanced accuracy of 0.63.
- The Combination Under-Over Sampling model didn't work so well, with a balanced accuracy of 0.52.
- The Balanced Random Forest Classifier did better, with a balanced accuracy of 0.79.
- But the clear winner was the Easy Ensemble AdaBoost Classifier, with a balanced accuracy of 0.93!

## Summary: 

If you're aiming for balanced accuracy, it's crucial to choose a machine learning model with the highest accuracy possible between 0 and 1, preferably closest to 1. Based on the credit card dataset, the Easy Ensemble AdaBoost Classifier proved to be the most suitable model, boasting a balanced accuracy of 0.93, whereas the other models had lower scores below 0.80. In terms of precision, all models had comparable performance within an acceptable range. The recall score, on the other hand, should be as close to 1 as possible for optimal results, and the Easy Ensemble AdaBoost Classifier scored the highest, indicating its superior performance. Consequently, the recommended machine learning model for further credit card analysis is the Easy Ensemble AdaBoost Classifier.
