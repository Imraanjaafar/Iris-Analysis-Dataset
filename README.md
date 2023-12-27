## Iris Flower Classification Model
### Overview
- This repository contains Python code for a machine learning model designed to classify Iris flowers into different species based on their features. The Iris dataset is utilized, and the model is built using various classifiers such as K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM). The performance of these models is evaluated, and the best-performing model is saved for future use.

### Contents
1- Data Loading:

- The Iris dataset is loaded using scikit-learn's built-in load_iris function.
- Basic information about the dataset, including its description and keys, is displayed.

2 - Data Visualization:

- Scatterplots and histograms are used to visualize the relationships between different features.
- A pair plot is created to explore the interactions between all pairs of features.

3 - Data Cleaning:

- Duplicates are checked and removed.
- Boxplots are used to identify potential outliers.

4 - Data Preprocessing:

- The dataset is split into features (X) and the target variable (y).
- The data is further split into training and testing sets using the train_test_split function from scikit-learn.

5 - Model Training:

- The K-Nearest Neighbors (KNN) classifier is trained on the Iris dataset.
- The model's accuracy is evaluated using the test set.

6 - Model Evaluation:

- Classification reports, confusion matrices, and model complexity curves are used to evaluate the performance of the KNN classifier.
- Other classifiers such as Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM) are also trained and evaluated.

7 - Model Selection:

- The accuracy and F1 scores of each model are compared, and the best-performing model is identified.

8 - Confusion Matrix and Classification Report:

- Confusion matrices and classification reports are generated for the best-performing model.

9 - Model Saving:

- The best model (StandardScaler + Support Vector Machine) is saved using the Pickle library for future use.

10 - Model Prediction:

- The saved model is loaded and used to make predictions on new input data.
