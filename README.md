# sentiment-analysis

Baseline Naive Bayes based sentiment analysis with Laplace Smoothing.

Average Accuracy for K for validation : 89.44 %

Summary of Cross Validation Running

```
Total Count 189

For Fold 0 as dev
POS: 85, NEG: 85
Correct: 18, Total: 19, Accuracy: 94.736842
        ID Class Pred_Class
3  ID-0993   NEG        POS

For Fold 1 as dev
POS: 88, NEG: 82
Correct: 18, Total: 19, Accuracy: 94.736842
         ID Class Pred_Class
29  ID-0905   NEG        POS

For Fold 2 as dev
POS: 90, NEG: 80
Correct: 15, Total: 19, Accuracy: 78.947368
         ID Class Pred_Class
48  ID-0805   NEG        POS
49  ID-1013   NEG        POS
52  ID-1196   POS        NEG
55  ID-0869   NEG        POS

For Fold 3 as dev
POS: 88, NEG: 82
Correct: 16, Total: 19, Accuracy: 84.210526
         ID Class Pred_Class
61  ID-1184   POS        NEG
66  ID-0973   NEG        POS
71  ID-0885   NEG        POS

For Fold 4 as dev
POS: 82, NEG: 88
Correct: 19, Total: 19, Accuracy: 100.000000
Empty DataFrame
Columns: [ID, Class, Pred_Class]
Index: []

For Fold 5 as dev
POS: 85, NEG: 85
Correct: 14, Total: 19, Accuracy: 73.684211
          ID Class Pred_Class
98   ID-1272   POS        NEG
99   ID-0827   NEG        POS
106  ID-0971   NEG        POS
109  ID-1144   POS        NEG
112  ID-1210   POS        NEG

For Fold 6 as dev
POS: 85, NEG: 85
Correct: 15, Total: 19, Accuracy: 78.947368
          ID Class Pred_Class
120  ID-0963   NEG        POS
122  ID-0991   NEG        POS
128  ID-1021   NEG        POS
131  ID-0989   NEG        POS

For Fold 7 as dev
POS: 81, NEG: 89
Correct: 19, Total: 19, Accuracy: 100.000000
Empty DataFrame
Columns: [ID, Class, Pred_Class]
Index: []

For Fold 8 as dev
POS: 86, NEG: 84
Correct: 18, Total: 19, Accuracy: 94.736842
          ID Class Pred_Class
154  ID-0839   NEG        POS

For Fold 9 as dev
POS: 85, NEG: 86
Correct: 17, Total: 18, Accuracy: 94.444444
          ID Class Pred_Class
187  ID-1216   POS        NEG
89.4444444444
[94.736842105263165, 94.736842105263165, 78.94736842105263, 84.21052631578948, 100.0, 73.684210526315795, 78.94736842105263, 100.0, 94.736842105263165, 94.444444444444443]
```
