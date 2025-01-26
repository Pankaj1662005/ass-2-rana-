# ass-2-rana-
Performance Analysis:
The table shows the accuracy results of five machine learning models (M1 to M5) using different sampling techniques (Sampling1 to Sampling5). Below is the interpretation of the best-performing techniques:

M1 (Random Forest Classifier) → Best: Sampling2 (1.00)

Random Over-Sampling performed best for M1.
Over-sampling helps when the model needs more balanced data for learning.
M2 (Logistic Regression) → Best: Sampling5 (1.00)

NearMiss sampling worked best for M2.
This suggests that removing certain majority class instances helped in classification.
M3 (SVC) → Best: Sampling5 (1.00)

NearMiss sampling also worked best for M3.
SVC might have benefited from a more balanced dataset by reducing noise.
M4 (Decision Tree Classifier) → Best: Sampling2 (0.993)

Random Over-Sampling gave the best performance for M4.
Decision trees often perform well with more data, and oversampling helped.
M5 (KNN) → Best: Sampling5 (1.00)

NearMiss was the best for M5.
KNN models often struggle with imbalanced data, so undersampling improved performance.
Conclusion:
Random Over-Sampling (Sampling2) worked best for Random Forest and Decision Tree.
NearMiss (Sampling5) performed best for Logistic Regression, SVC, and KNN.
SMOTE-based methods (Sampling3 & Sampling4) showed decent results but were not the top performers.
