# Evaluating-Student-Writing
Created a model to classify argumentative elements in student writing as "effective," "adequate," or "ineffective."

Data is cleaned and preprocessed using NLTK library functions:
- tokenizer
- filter
- stemmer
- chunking

Machine Learning models are fit on the processed data to evaluate which model works best for or data.
- Logistic Regression
- K Nearest Neighbour Classifieer
- Random Forest Classifier
- XG Boost
- SVM

Matrics used to evaluate the performance are:
- F1 Score
- Accuracy
- Log Loss

Conclusion:
Considering all three matrices on the validation set, it is found that logistic regression gives better results with the shortest training period.
