# credit-risk-analysis-report

Machine learning techniques are applied to a dataset of historical lending activity from a peer-to-peer lending platform to develop a model that can assess the creditworthiness of borrowers.

## Overview of the Analysis
The lending_data.csv dataset is a synthetic dataset representing historical lending activity from a peer-to-peer lending platform, used to assess the creditworthiness of borrowers. In this analysis, a Logistic Regression model was employed to predict credit risk and evaluate borrowers' creditworthiness. The model's performance was assessed using a confusion matrix and classification report. Loans were categorized as '0' (healthy, low-risk loans) or '1' (high-risk loans with potential for default). The dataset was split into training and testing sets, and model performance was evaluated based on accuracy, precision, recall, and the confusion matrix.

## Results
Logistic Regression Model

Accuracy Score

The model correctly classified 99% of the loans.

Precision Score

Class 0 (Healthy, low-risk loans): 100% precision, with 97% of the data in the training set being classified as healthy loans.
Class 1 (High-risk loans): 84% precision, with 3% of the data representing high-risk loans.

Recall Score

Class 0 (Healthy, low-risk loans): 99% recall, indicating that most of the positive predictions were correct.
Class 1 (High-risk loans): 94% recall, indicating a high proportion of correct predictions for high-risk loans.

## Summary
The Logistic Regression Model demonstrates high performance with an accuracy of 99%, effectively classifying loan statuses. For precision, the model predicts high-risk loans (class '1') with 84% accuracy. In terms of recall, it correctly identifies high-risk loans (class '1') 94% of the time, minimizing false negatives and maintaining a low false positive rate. Given its strong performance, the Logistic Regression Model is highly effective and should be adopted by the peer-to-peer lending services company.
