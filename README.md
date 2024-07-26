# Decision Tree Classifier on Marketing Bank Data #

### Introduction: ###
This analysis aims to build and evaluate a decision tree classifier to predict whether a customer will subscribe to a term deposit based on the marketing bank dataset. The dataset includes features such as job, marital status, education, and previous marketing outcomes.

### Methodology: ###
**1. Data Loading:**
- Pandas, matplotlib, and seaborn libraries are imported.
- The dataset is loaded from the specified file path.

**2. Preprocessing the Data:**
- Categorical variables are encoded using one-hot encoding for compatibility with the decision tree algorithm.

**3. Defining Features and Target Variable:**
- Features (X) are defined by dropping the 'deposit' column.
- The target variable (y) is defined as the 'deposit' column.

**4. Splitting the Data:**
- The data is split into training and testing sets with a test size of 20%.

**5. Building and Training the Model:**
- A decision tree classifier is instantiated and trained using the training data.

**6. Evaluating the Model:**
- Predictions on the test set are made using the trained classifier.
- Accuracy is calculated to assess the model's performance.
- A confusion matrix is generated to understand the classification results.
- A classification report is produced to provide precision, recall, and F1-score for each class.

### Results: ###
- The decision tree classifier provides an accuracy score indicating its performance on the test set.
- The confusion matrix shows the distribution of true positives, true negatives, false positives, and false negatives.
- The classification report offers detailed metrics, helping to understand the model's strengths and areas for improvement in predicting customer subscription to term deposits.
