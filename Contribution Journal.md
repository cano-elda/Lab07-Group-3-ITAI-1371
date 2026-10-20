Elda's Entry

For Module 7 Lab, I prepared the Titanic dataset, trained the model, and created the confusion matrix.  
I split the date into training and testing sets and trained a logistic regression model to predict whether  
a passenger survived. I then calculated the confusion matrix and displayed it as heatmap so we could compare  
the model’s predictions with the actual results. The results showed 90 true negatives, 15 false positive,  
20 false negatives, and 54 true positives. I completed the first question of the knowledge-check.


Xinyu's Entry:

For this Exercise, I created sections for Task 2: Generate a Classification Report and Knowledge Check Question 2. I used the classification_report function from scikit-learn to generate a classification report for the Titanic survival prediction model that I had created. The report contains information about the precision, recall, F1-score, and support for each of the classes. I checked the results for the report, and they looked correct. The accuracy for the model was 80%. For the Knowledge Check Question 2, I described why recall is more important than precision in a medical screening situation for a serious disease. After I completed the sections for Task 2 and Knowledge Check Question 2, I ran the required code to confirm that the classification report was correctly generated.


Michelle's Entry

My part of the Module 7 Lab was the cross-validation section, which was Task 3 and Question 3 of the knowledge check. The job was to check whether the 80% accuracy from our single split was actually reliable so I ran 5-fold cross-validation on the full Titanic data using cross_val_score. The scores came out around 77% to 80%, and the average was 78.68%. That’s a bit lower than 80% so our first result was slightly lucky, but the standard deviation was only 0.0094, so the model stays pretty consistent. 
