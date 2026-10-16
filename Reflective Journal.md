Elda's Entry

In this Lab, I got a better understanding of how confusion matrix compares the model's predictions to the actual results.  
It helped me see when the model was right or wrong by showing the true positives, true negatives, false positives, and false  
negatives in a heatmap. I also learned that accuracy does not tell the whole story because it does not show the types of  
mistakes the model makes. Another thing I learned is that precision can matter more than recall when false positives can  
cause bigger problems, like a spam filter deleting an important email or a system mistakenly banning a real user for being a bot.


Xinyu's Entry:

For this lab, I generated a classification report for the Titanic survival prediction model using the classification_report function from scikit-learn. The results were that the model was correct in its classification of about 80% of the passengers in the test data set. 

Looking at the numbers for Class 0 (Non-Survivors), we have a Precision of 0.82, a Recall of 0.86, and an F1-score of 0.84. Moving on to Class 1 (Survivors), we see that the Precision is 0.78, the Recall is 0.73, and the F1-score is 0.76. Precision measures the proportion of true positives among predicted positives. This metric can be important depending on the classification problem. For example, in a medical screening for a serious disease, missing a positive case is worse than a false positive (since a false positive can usually be checked for more). Hence, for this type of problem, recall would be a more appropriate metric to choose. 

The F1-score provides a useful average between precision and recall for a classification model. The support of the classification report shows the number of actual samples in each class. The samples for Class 0 in the test data used for this lab consisted of 105 passengers, while for Class 1, 74. There were therefore not equal numbers of the two classes in the test data.

One limitation of the model in this case is that the overall accuracy does not reveal the specific misclassifications of individual passengers. I will look to the confusion matrix for further information on the incorrectly classified passengers, and investigate the performance of other classification models in order to try to improve their recall and F1-scores. I would also like to further investigate the effect that the chosen features have on the model’s predictions.
