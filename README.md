# Health-symptom-classifier

Goal of project was to develop a robust model which can differentiate between four respiratory diseases - "Covid", "Flu", "Allergy", "Cold" using 20 different symptoms.

First I preprocessed the data and then did mannual hyperparameter tunning using "Random forest classifier". Then found that 2 diseases have low accuracy then did under sampling on rest 2 diseases to increase the accuracy. Then used "GridSearchCV" and evaluated 6 machine learning models. And observed that Logistic Regression has highest accuracy.

This model had accuracy of 94% and now I have increased it to 96%
