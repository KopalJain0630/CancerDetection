Cancer Detection - XAI

This repository contains 3 different projects involving tumor detection/classification done on publically available datasets. The steps followed in each project is as follows:
1. The first stage involves visualization of the input features/images to asses the importance of each feature for the final predictions.
2. In the second stage, the predictive models are developed and tested in order to achieve the best possible accuracies on predictions.
3. Shapley Additive Explaination (SHAP) Values were evaluated on the test outputs in order to explain the predictions made by the models.

There are 3 different datasets used for different classifications:
1. Breast Cancer: Winconsin dataset, containing tabulated features and outcomes are used to classify the tumours into benign and malignant
2. Lung Cancer: A dataset available on Kaggle, containing tabulated features and outcomes are used to predict the probability of developing lung cancer
3. Skin Cancer: An image dataset of benign and malignant tumours in the skin, obtained from Kaggle, on which these classifications are made

The aim of this project is to deploy an explainable model using meta-heuristic to enhance transparency and accuracy in cancer and detection.
We have applied data preprocessing techniques to analyze the datasets, and employed the models for suitable classifications, enabling actionable AI-driven decisions.
We have also justified the decision explanations using Explainable AI (XAI) tools like Shapley Additive Explanation Values (SHAP), improving clinical trust on AI-healthcare.
