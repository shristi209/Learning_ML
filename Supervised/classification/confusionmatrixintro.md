<h2>Description Of Confusion Matrix</h2>

Confusion matrix is measuring the performace of the model we made. We can measure the model performace by 4 different ways:

    *   Accuracy
    *   Precision
    *   Recall
    *   F1-score

Confusion Matrix has four prediction:

    TP: True Positive
        Truth value (true) + Prediction also matches (positive)
    TN: True Negative
        Truth value (true) + Prediction doesnot matches (Negative)
    FP: False Positive
        Truth value (false) + Prediction (positive)
    FN: False Negative
        Truth value (false) + Prediction (negative)

Let's do with one example:

    NUm:           1     2        3       4       5      6        7       8       9      10      11
    Truth:       rose   lily    rose    rose    lily    rose    rose    rose    lily    rose    rose
    Prediction:  lily   lily    rose    rose    rose    rose    lily    rose    lily    lily    rose  

Above example presents:
Here: 

    Positive = rose,  True = rose
    Negative = lily,  False = lily

    TP = 3 4 6 8 & 11 are true positive as the truth value "rose" is giving prediction that its rose. So, It's true positive

    TN = 1 7 10 are true negative values as they have truth value "rose" but predicting lily which is negative so.

    FN = 2 9 are false negative as the lily itself is false in contect of rose, and  they are predicting lily as output which is positive so, Its False negative.

    FP = 5 is false negative as it has false value 'lily' and predicting 'rose' which is positive. 


We are finding rose prediction performance.
**Accuracy** is calculated by 

    right prediction / total number of prediction = (TN + TP)/ (FN + TN + TP + FP)

Like from the example, It's 7/11 accurate    

**Precision** is calculated by

    True Positive / total target prediction = TP / (TP + FP)

Like from the example, It's 5/6 precision

**Recall** is calculated by

    True Positive / total truth values = TP / (TP + TN)

Like from the example, It's 5 / 8 recall

**F1-Score** is calculated by

    F1-Score = 2*precision*recall / (precision + recall)