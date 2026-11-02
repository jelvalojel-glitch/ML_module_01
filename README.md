# ML_module_01

In this project, i had to make three models to classify, which people we can give platinum credit card (Class 1) and which we don't want to (Class 0), predicting their income by using other values.

The most important metric here is Precision because worst thing we can get is False positive meaning giving platinum card to Class 0

RandomForestClassifier:

Accuracy: 0.8582794629537543

Classification Report:
               precision    recall  f1-score   support

           0       0.87      0.95      0.91      4531
           1       0.79      0.59      0.67      1502

    accuracy                           0.86      6033
    macro avg       0.83      0.77      0.79      6033
    weighted avg       0.85      0.86      0.85      6033

Logistic regression:

Accuracy: 0.817503729487817

Classification Report:
               precision    recall  f1-score   support

           0       0.84      0.94      0.89      4531
           1       0.71      0.45      0.55      1502

    accuracy                           0.82      6033
    macro avg       0.78      0.69      0.72      6033
    weighted avg       0.81      0.82      0.80      6033

Gradient Boosting:

Accuracy: 0.863583623404608

Classification Report:
               precision    recall  f1-score   support

           0       0.89      0.94      0.91      4531
           1       0.77      0.64      0.70      1502

    accuracy                           0.86      6033
    macro avg       0.83      0.79      0.81      6033
    weighted avg       0.86      0.86      0.86      6033
  
Random Forest
- Achieved 86% accuracy.
- Class 1 precision is 0.79, the highest among all three models.
- Class 1 recall is 0.59, meaning it identifies 59% of actual positive cases.
- F1-score of 0.67 shows a reasonable balance between precision and recall.

Logistic Regression
- Achieved the lowest accuracy of approximately 81.75%.
- Class 1 recall is only 0.45.
- Its F1-score of 0.55 is also the lowest.
- This indicates that Logistic Regression performs worse at identifying positive cases compared with the other models.

Gradient Boosting
- Achieved the highest accuracy of approximately 86.36%.
- Has the highest Class 1 recall (0.64).
- Has the highest Class 1 F1-score (0.70).
- Provides the best balance between precision and recall among the three models.

Gradient Boosting demonstrated the best overall classification performance, achieving 86.36% accuracy and an F1-score of 0.70 for Class 1. It also achieved the highest recall for Class 1 (0.64), meaning it successfully identifies more positive cases than Random Forest and Logistic Regression.

Random Forest also performed well, particularly in precision, where it achieved the highest score of 0.79. However, its recall was slightly lower than Gradient Boosting.

Logistic Regression showed the weakest performance, with the lowest accuracy, recall, and F1-score.

Therefore, Gradient Boosting is the most suitable model based on these results, while Random Forest could be considered an alternative when precision is more important.
