**Titanic Survival Prediction**

This project builds a classification model to predict passenger survival using a Random Forest classifier with hyperparameter tuning via GridSearchCV.

**Objective**
To develop and optimize a machine learning model capable of predicting whether a passenger survived the Titanic disaster based on structured passenger features.

**Model Used**
Random Forest Classifier

**Model Performance**

Test Set Results:
Accuracy: 82%
Precision (Survival = 1): 0.78
Recall (Survival = 1): 0.72
F1-Score (Survival = 1): 0.75

Class-wise Metrics:

Class	              Precision Recall	F1-Score	Support
0 (Did Not Survive) 0.83	    0.87	  0.85	     110
1 (Survived)	      0.78	    0.72	  0.75	     69

The model performs slightly stronger in identifying non-survivors, reflecting class distribution imbalance.

**Techniques Applied**

Data preprocessing
Handling missing values
Categorical feature encoding
Hyperparameter tuning
Confusion matrix evaluation
Precision, Recall, F1-score analysis

**Tools & Libraries**
Python
Pandas
NumPy
Scikit-learn

Seaborn

Matplotlib
