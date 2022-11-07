# cross-validation-and-Model-Validation-Method <br />
### all types of cross validation and Model Validation Method with explaination  
#### cross–validation is to test the ability of a machine learning model to predict new data. It is also used to flag problems like overfitting or selection bias and gives insights on how the model will generalize to an independent dataset
1.Evaluate using KFold Cross Validation <br />
2.STRATIFIED K FOLD CROSS VALIDATION <br />
3.Evaluate using Leave One Out Cross Validation <br />
4.Leave-p-out cross-validation <br />
5.GapLeavePOut <br /> 
6.(1)1Hold-out cross validation <br />
2.Evaluate using a train and a test set <br />
7.Shuffle split <br />
8.Rolling cross validation <br />
9.Time Series Split Cross-Validation <br />
10.Blocked Cross-Validation <br />
#### for visualization of all cross validation https://scikit-learn.org/stable/auto_examples/model_selection/plot_cv_indices.html#sphx-glr-auto-examples-model-selection-plot-cv-indices-py <br />
NOTE   <br />
cross validation will always give acurracy estimates of the models but not actual but to know how far accuraccy is from estimates and actual we will use accuracy measures to know(for regression type model)   <br />
![image](https://user-images.githubusercontent.com/79073189/200225870-62464510-45af-422e-b010-69ca0a26ae7b.png)
(for classification type model) <br />
accuracy=number of correct prediction/total number of prediction made  <br />
or we can use confusion matrix(only for binary classification we can use but not for multiple classes we can not) <br />
#### the F-score or F-measure  <br />
is a measure of a test's accuracy. <br />
can be calculated by the following formula: 2 x [(Precision x Recall) / (Precision + Recall)] <br />
Precision <br />
It helps us to measure the ability to classify positive samples in the model we can do it for both Y and N that will test how  precisies it is when we call Y and N <br />
Recall <br />
It helps us to measure how many positive samples were correctly classified by the ML model and similarly we can test the recall by  when we call Y and N (sensitivity and specificity)<br />
