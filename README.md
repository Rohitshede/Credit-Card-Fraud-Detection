# Credit Card Fraud Detection
## Problem statement:

The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.

In this project, we will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group.

The dataset is taken from the Kaggle Website website and it has a total of 2,84,315 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.

# Data Dictionary

You can download this dataset using [this link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. Out of a total of 2,84,315 transactions, 492 were fraudulent. This data set is highly unbalanced, with the positive class (frauds) accounting for 0.172% of the total transactions. The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality. Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time' contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount. The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.

# Sampling Techniques
 Undersampling: Randomly removes samples from the majority class to balance class distributions.
 
 Oversampling SMOTE (Synthetic Minority Over-sampling Technique): Generates synthetic examples in the minority class using nearest neighbors to balance class distributions.

# Algorithms
Logistic Regression: A linear model for binary classification.

Decision Tree: A tree-based model that partitions the feature space into subsets.

Random Forest: An ensemble of decision trees that improves generalization and reduces overfitting.

# Evaluation Metrics
Accuracy Score: Measures the overall correctness of the model's predictions.

Precision Score: Measures the proportion of true positive predictions among all positive predictions.

Recall Score: Measures the proportion of true positive predictions among all actual positive instances.

F1 Score: Harmonic mean of precision and recall, balancing both metrics.

# Conclusion
This project demonstrates the effectiveness of different machine learning algorithms and sampling techniques in detecting credit card fraud. By evaluating multiple models using various metrics, it provides insights into the performance and robustness of each approach.


