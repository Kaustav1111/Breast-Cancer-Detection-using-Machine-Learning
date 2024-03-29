# Project Description :
This project focuses on breast cancer classification, leveraging a common dataset for concept demonstration. The primary goal is to showcase the iterative process of model improvement through hyperparameter tuning, leading to enhanced accuracy and reduced type II errors.

# Actions Taken :
### 1) Dataset Import:

Imported the breast cancer dataset from the sklearn.datasets library.

### 2) Exploratory Data Analysis (EDA):

Generated an Exploratory Data Analysis (EDA) report using the ydata_profiling package to gain insights into the dataset's structure and characteristics.

### 3) Data Splitting:

Split the dataset into training and testing sets to facilitate model training and evaluation.

### 4) Initial Model Training:

Trained an initial Support Vector Machine classification model on the training data.

### 5) Confusion Matrix Analysis:

Reviewed the confusion matrix, identifying a 96% accuracy rate but notable type 2 errors.

### 6) Hyperparameter Tuning:

Conducted hyperparameter tuning using the GridSearchCV attribute from the model_selection class in the sklearn package.
Tuned parameters included C-parameter, gamma-parameter, and kernel.

### 7) Model Refitting:

Refitted the model with the identified optimal hyperparameters. Repredicted the results.

### 8) Post-Tuning Evaluation:

Re-evaluated the confusion matrix for the updated model. Observed an increased overall accuracy to 98% and a notable reduction in type 2 errors to 1.
