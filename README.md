# Credit_Risk_Analysis 💳 

## Overview
Apply machine learning to solve a real-world challenge: credit card risk.

Using
* Naive Random Oversampling
* SMOTE_Oversampling
* Undersampling
* Combination (Over and Under) Sampling
* Balanced Random Forest Classifier
* Easy Ensemble AdaBoost Classifier

## Results

1 Naive Random Oversampling results<br>
<br>
The first is a way from our target of 1 which would bring us with an accurate score.<br>
<img src="https://github.com/Acromic/Credit_Risk_Analysis/blob/5f0c45dc4823e468013dc3b6f7c2a173cabe52b1/resources/Naive%20Random%20Oversampling.png" width="50%" height="50%">
<br>
2 SMOTE Oversampling results<br>
<br>
The second started in the correct direction of 1
<img
src="https://github.com/Acromic/Credit_Risk_Analysis/blob/5f0c45dc4823e468013dc3b6f7c2a173cabe52b1/resources/SMOTE_Oversampling.png" width="50%" height="50%">
<br>

3 Undersampling results<br>
<br>
The third was the worse test.
<img
src="https://github.com/Acromic/Credit_Risk_Analysis/blob/1c57e3e34f6d69c46d56524dc0eaff04d2758d1d/resources/Undersampling.png" width="50%" height="50%">
<br>

4 Combination (Over and Under) Sampling results<br>
<br>
The fourth started the right direction again.
<img
src="https://github.com/Acromic/Credit_Risk_Analysis/blob/1c57e3e34f6d69c46d56524dc0eaff04d2758d1d/resources/Combination%20(Over%20and%20Under)%20Sampling.png" width="50%" height="50%">
<br>

5 Balanced Random Forest Classifier results<br>
<br>
The fifth brought us back closer to 1 which is what we want.
<img
src="https://github.com/Acromic/Credit_Risk_Analysis/blob/983e989954cd52070a244db381b4c0094b15e48d/resources/Combination%20(Over%20and%20Under)%20Sampling.png" width="50%" height="50%">
<br>

6th Easy Ensemble AdaBoost Classifier results<br>
<br>
The sixth brought our model where we want to be with a score close to 1.
<img
src="https://github.com/Acromic/Credit_Risk_Analysis/blob/a745af95549647a8530c50ecc0902cf6a68acc18/resources/Easy%20Ensemble%20AdaBoost%20Classifier.png" width="50%" height="50%">
<br>

## Summary
Closest to the results we want to use are Easy Ensemble AdaBoost Classifier results with an f1 score of .93. I especially wouldn't recommend Undersampling results with an F1 score of .56, the results were too far from our goal of 1.  With rigorous training it shows how the results can improve with the correct testing and training. 
