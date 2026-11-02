# ML_module_01

In this project, i had to make RandomForestClassifier model to classify, which people we can give platinum credit card, predicting their income by using other values.

Accuracy: 0.8582794629537543

Classification Report:
               precision    recall  f1-score   support

           0       0.87      0.95      0.91      4531
           1       0.79      0.59      0.67      1502

    accuracy                           0.86      6033
   macro avg       0.83      0.77      0.79      6033
weighted avg       0.85      0.86      0.85      6033

As you can see from the report the model got decent accuracy of 85.8% but it has difficulty identifying 'platinum card people' (1) correctly.
This may be caused by the imbalance in the dataset, where 0 represents approximately 75% of observations and 1 represents only 25%. Therefore, despite the relatively high accuracy, the model could be improved by adjusting the classification threshold, applying class weighting, or using resampling techniques. Overall, the model performs well for class 0 but requires improvement in detecting class 1.
