<center><h1>Iris Classification Project</h1></center>

- **Project Overview**
This project demonstrates an end-to-end supervised machine learning workflow using the classic Iris dataset. The goal is to classify iris flowers into three species (Setosa, Versicolor, Virginica) based on four features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
    
- **The project includes**:
  - Exploratory Data Analysis (EDA)
  - Feature Visualization
  - Data Preprocessing
  - Model Building and Evaluation
  - Hyperparameter Tuning
  - Final Model Selection

- **Key Features and Insights**
  - Petal features (length and width) are highly discriminative for species separation.
  - Setosa is easily separable; Versicolor and Virginica show some overlap in sepal dimensions.
  - Correlation analysis revealed strong relationships between petal features.
  - Boxplots, histograms, pairplots, and feature-wise mean comparison help visualize class separability.

- **Models Used**
  - Logistic Regression – Linear baseline classifier
  - K-Nearest Neighbors (KNN) – Distance-based classifier
  - Decision Tree – Rule-based, interpretable classifier
  - Support Vector Machine (SVM) – Margin-based classifier
  - Hyperparameter Tuning – Applied to KNN and SVM

- **Model Evaluation**
Models were evaluated using:
  - Accuracy – Overall performance metric
  - Confusion Matrix – Class-wise prediction analysis
  - Precision, Recall, F1-Score – Class-wise evaluation

- **Results Summary**:
Model	Test Accuracy
  - Logistic Regression:	0.931
  - KNN:	0.931
  - Decision Tree:	0.931
  - SVM:	1.000
  - KNN (Tuned):	0.931
  - SVM (Tuned):	0.966


- **Final Model**:
Support Vector Machine (SVM) selected due to highest and most stable performance, consistent class-wise results, and superior generalization.

- **Learnings**
  - Proper EDA and feature analysis for classification tasks
  - Model comparison using accuracy, precision, recall, and F1-score
  - Effect of hyperparameter tuning
  - Selecting a robust final model based on evaluation metrics
