# Confusion-Matrix

Table that represents performance of binary classification models NOT regression models. 
Every observation(row) in the testing set is represented in exactly on box. 

It is used on the test data for the true/actual values are known. 
Most important rule is first argument is true values, 
second is predicted values(print metrics.confusion_matrix(y_test, y_predicted)).

All matrix in sklearn expects Actual to be first, 
actual is shown on left side of the box and predicted is displayed in right side top of the box 
('A' in Actual appears first 'P' in Predicted appears latter) with class '0' in first place followed by class '1'
(in number system '0' appears first  then 1).  'No' class first and 'Yes' class next
('N' appears first in alphabets first then 'Y' appears in abcd..)

Confusion Matrix gives you a more complete picture of how your classifier is performing.
