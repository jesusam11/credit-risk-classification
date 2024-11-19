# credit-risk-classification

## Overview of the Analysis

The purpose of this analysis was to evaluate a Logistic Regression Model can identify the creditworthiness of borrowers.  By training the model, it should provide results that proprerly identify healthy and high risk loans.

## Results

Performance on Class 0 (Healthy Loan):
 - Precision: 1.00 — Nearly every prediction of 0 was accurate, meaning the model rarely mislabels high-risk loans as healthy.
 - Recall: 0.99 — Almost all actual healthy loans were correctly classified, so very few healthy loans were mistakenly classified as high-risk.
 - F1-score: 1.00 — The F1-score reflects that the model performs extremely well on this majority class, with an ideal balance between precision and recall.

Performance on Class 1 (High-Risk Loan):
 - Precision: 0.84 — Some healthy loans were incorrectly classified as high-risk, leading to a moderate precision.
 - Recall: 0.94 — The model accurately identifies 94% of high-risk loans, showing its strong recall, though some high-risk loans were missed.
 - F1-score: 0.89 — This score reflects that the model is reasonably accurate for this class but shows room for improvement.

## Summary

- Accuracy: 0.99 — The model achieves an impressive 99% accuracy, largely due to the high number of correctly predicted healthy loans.

- Class Imbalance Impact: The large difference in class sizes (18,765 healthy loans vs. 619 high-risk loans) favors predicting the 0 class. This imbalance results in a slightly lower performance on class 1.

In conclusion, the model is excellent at predicting healthy loans, though it could be optimized further for identifying high-risk loans. Handling class imbalance, such as by adjusting decision thresholds or using oversampling/undersampling techniques, may improve predictions for high-risk loans (1).
