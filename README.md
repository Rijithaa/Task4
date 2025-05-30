# Task4

 1. Choose a Binary Classification Dataset
We use the Breast Cancer dataset where the goal is to predict if a tumor is malignant (0) or benign (1).

2. Train/Test Split and Standardize Features
We split the data into training and test sets, and standardize the features so all values are on the same scale for better model performance.

3. Fit a Logistic Regression Model
We train a logistic regression model which uses the sigmoid function to predict probabilities between 0 and 1, and classify outcomes.

4. Evaluate the Model
We check model performance using:
Confusion matrix
Precision
Recall
ROC-AUC score
These help us understand accuracy and error rates.

5. Tune Threshold & Explain Sigmoid
We can change the threshold (default is 0.5) to improve results.
The sigmoid function converts model output into probabilities used for classification.
