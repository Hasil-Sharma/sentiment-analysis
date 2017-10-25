# sentiment-analysis

Binary Naive Bayes based sentiment analysis with Laplace Smoothing, stemming and negation

Average Accuracy for K for validation : 92.63 % (Better than [Baseline](https://github.com/Hasil-Sharma/sentiment-analysis/tree/baseline))
[Binary-Naive-Bayes](https://github.com/Hasil-Sharma/sentiment-analysis/tree/a1b4b1b0db335ebfc19fc22755bf398c9e191fa6)

Summary of Cross Validation Running

```
Total Count 189

For Fold 0 as dev
POS: 85, NEG: 85
Correct: 16, Total: 19, Accuracy: 84.210526
         ID Class Pred_Class
8   ID-0869   NEG        POS
11  ID-0885   NEG        POS
14  ID-0805   NEG        POS

For Fold 1 as dev
POS: 87, NEG: 83
Correct: 18, Total: 19, Accuracy: 94.736842
         ID Class Pred_Class
37  ID-0961   NEG        POS

For Fold 2 as dev
POS: 86, NEG: 84
Correct: 18, Total: 19, Accuracy: 94.736842
         ID Class Pred_Class
51  ID-0993   NEG        POS

For Fold 3 as dev
POS: 84, NEG: 86
Correct: 18, Total: 19, Accuracy: 94.736842
         ID Class Pred_Class
71  ID-1196   POS        NEG

For Fold 4 as dev
POS: 84, NEG: 86
Correct: 17, Total: 19, Accuracy: 89.473684
         ID Class Pred_Class
77  ID-0971   NEG        POS
87  ID-1272   POS        NEG

For Fold 5 as dev
POS: 87, NEG: 83
Correct: 18, Total: 19, Accuracy: 94.736842
          ID Class Pred_Class
104  ID-0827   NEG        POS

For Fold 6 as dev
POS: 83, NEG: 87
Correct: 17, Total: 19, Accuracy: 89.473684
          ID Class Pred_Class
123  ID-0963   NEG        POS
128  ID-1184   POS        NEG

For Fold 7 as dev
POS: 85, NEG: 85
Correct: 18, Total: 19, Accuracy: 94.736842
          ID Class Pred_Class
149  ID-0839   NEG        POS

For Fold 8 as dev
POS: 88, NEG: 82
Correct: 19, Total: 19, Accuracy: 100.000000
Empty DataFrame
Columns: [ID, Class, Pred_Class]
Index: []

For Fold 9 as dev
POS: 86, NEG: 85
Correct: 17, Total: 18, Accuracy: 94.444444
          ID Class Pred_Class
178  ID-0973   NEG        POS
93.1286549708
[84.21052631578948, 94.736842105263165, 94.736842105263165, 94.736842105263165, 89.473684210526315, 94.736842105263165, 89.473684210526315, 94.736842105263165, 100.0, 94.444444444444443]
```
