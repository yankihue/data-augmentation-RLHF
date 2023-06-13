### sentiment task

```
base

              precision    recall  f1-score   support

     Pozitif       0.86      0.78      0.82      1309
     Negatif       0.84      0.90      0.87      1690

    accuracy                           0.85      2999
   macro avg       0.85      0.84      0.84      2999
weighted avg       0.85      0.85      0.85      2999
```
------------------------------------------
```
data augmented with baseline gpt2
              precision    recall  f1-score   support

     Pozitif       0.97      0.53      0.69      1309
     Negatif       0.73      0.99      0.84      1690

    accuracy                           0.79      2999
   macro avg       0.85      0.76      0.77      2999
weighted avg       0.84      0.79      0.77      2999
```
------------------------------------------
```
data augmented with pre-trained sentiment analysis model-based reinforcement learning
              precision    recall  f1-score   support

     Pozitif       0.98      0.55      0.70      1309
     Negatif       0.74      0.99      0.85      1690

    accuracy                           0.80      2999
   macro avg       0.86      0.77      0.78      2999
weighted avg       0.84      0.80      0.79      2999
```
------------------------------------------
```
data augmented with our human-feedback trained model
              precision    recall  f1-score   support

     Pozitif       0.96      0.59      0.73      1309
     Negatif       0.76      0.98      0.85      1690

    accuracy                           0.81      2999
   macro avg       0.86      0.79      0.79      2999
weighted avg       0.85      0.81      0.80      2999
```
--------------------------------
### classification task
```
base

              precision    recall  f1-score   support

       dunya       0.67      0.76      0.71      1489
     ekonomi       0.84      0.37      0.52       903
        spor       1.00      0.03      0.06       298
     siyaset       0.97      0.18      0.31       373
   teknoloji       0.93      0.19      0.32       498
      kultur       0.63      0.97      0.76      2729
      saglik       1.00      0.01      0.03       216

    accuracy                           0.66      6506
   macro avg       0.86      0.36      0.39      6506
weighted avg       0.74      0.66      0.60      6506
```
------------------------------------------
```
data augmented with baseline gpt2

              precision    recall  f1-score   support

       dunya       0.76      0.67      0.71      1489
     ekonomi       0.52      0.79      0.63       903
        spor       1.00      0.02      0.03       298
     siyaset       1.00      0.10      0.18       373
   teknoloji       0.94      0.15      0.26       498
      kultur       0.70      0.95      0.81      2729
      saglik       1.00      0.00      0.01       216

    accuracy                           0.68      6506
   macro avg       0.85      0.38      0.38      6506
weighted avg       0.75      0.68      0.62      6506
```
------------------------------------------
```
data augmented with our model

              precision    recall  f1-score   support

       dunya       0.74      0.71      0.72      1489
     ekonomi       0.59      0.78      0.67       903
        spor       1.00      0.02      0.04       298
     siyaset       0.98      0.13      0.23       373
   teknoloji       0.93      0.17      0.29       498
      kultur       0.70      0.96      0.81      2729
      saglik       1.00      0.01      0.02       216

    accuracy                           0.69      6506
   macro avg       0.85      0.40      0.40      6506
weighted avg       0.75      0.69      0.63      6506
```
-----------------------------------------------
### detoxification task
```
base

              precision    recall  f1-score   support

         yes       0.86      0.89      0.88       995
          no       0.89      0.86      0.87      1005

    accuracy                           0.88      2000
   macro avg       0.88      0.88      0.87      2000
weighted avg       0.88      0.88      0.87      2000
```
------------------------------------------
```
data augmented with baseline gpt2

              precision    recall  f1-score   support

         yes       0.72      0.99      0.84       995
          no       0.99      0.62      0.76      1005

    accuracy                           0.81      2000
   macro avg       0.86      0.81      0.80      2000
weighted avg       0.86      0.81      0.80      2000
```
------------------------------------------
```
data augmented with our model

              precision    recall  f1-score   support

         yes       0.74      0.99      0.85       995
          no       0.99      0.66      0.79      1005

    accuracy                           0.82      2000
   macro avg       0.87      0.83      0.82      2000
weighted avg       0.87      0.82      0.82      2000
```
