# Problem-Dataset-02
Approach

This problem is treated as a binary classification task, where:

1 → will subscribe
0 → will not subscribe

We use Logistic Regression to model the probability of a customer subscribing based on input features such as demographics, financial status, and campaign details.

Methodology
1. Data Collection
Dataset: Bank Marketing Dataset
Contains 17 features including:
Age, Job, Marital Status
Balance, Loan, Contact Type
Campaign-related attributes

2. Data Preprocessing
Converted target variable (yes/no) → (1/0)
Handled categorical variables using one-hot encoding
Checked for missing values and cleaned data

3. Feature Engineering
Transformed categorical features into numerical format
Selected relevant features for model training

4. Train-Test Split
Training Set: 80%
Testing Set: 20%


5. Model Building
Algorithm: Logistic Regression
Used sigmoid function to estimate probability
6. Model Training
Trained the model on training data
Learned coefficients for each feature

7. Prediction
Predicted probabilities for test data
Applied threshold (0.5) to classify outputs

8. Evaluation
Accuracy Score
Confusion Matrix
Precision, Recall, F1-score



