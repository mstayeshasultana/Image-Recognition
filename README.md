# Image-Recognition

**Purpose of the Task

The purpose of this exercise is to develop and evaluate machine learning models for image classification. The goal is to determine which classifier performs best in distinguishing between different image categories based on extracted features. We achieve this by training multiple models, tuning their hyperparameters, and assessing their generalization performance using cross-validation techniques.

Dataset Description

The dataset consists of 185 images, from which we extracted 10 features. These features capture key properties of the images, enabling classification without directly using pixel values. The dataset contains images of different classes, including grass, sand, and stairs, making it a multi-class classification problem. The images were preprocessed to grayscale and quantized into 8 levels to enhance feature extraction.

Methods Used

To build and evaluate classifiers, the following machine learning methods were applied:

Feature Extraction: In this study, we extract and analyze various texture and color features to classify image data effectively. Texture-based features were extracted using Gray-Level Co-occurrence Matrix (GLCM) technique.
Classification Models: Three classifiers were implemented:
Ridge Classifier
Random Forest
Multi-Layer Perceptron (MLP)
Hyperparameter Tuning: GridSearchCV with 5-fold Stratified Cross-Validation was used to optimize hyperparameters for each classifier.
Performance Estimation: Nested Cross-Validation was applied, using 4-fold Stratified K-Fold in the inner loop for hyperparameter tuning and 5-fold Stratified K-Fold in the outer loop to estimate model performance.
Evaluation Metrics: The models were evaluated using accuracy scores and confusion matrices to assess classification performance. For the Random Forest model, feature importance was analyzed to understand the contribution of different features.
Structure of the Report

The report presents the methodology, experimental results, and a discussion on model performance. We first describe the classification models and cross-validation techniques. Then, we present the results of hyperparameter tuning and nested cross-validation. Finally, we analyze feature importance, discuss model performance, and conclude with key findings.**
