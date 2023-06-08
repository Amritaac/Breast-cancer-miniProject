# Breast-cancer-miniProject
Breast cancer detection
The top 5 rows of our data show that we need to add column names as well as to deal with "?"
if there are null values and drop them
Checking how each of the features is distributed
As there are different scales for the features and  some of the algorithms require a prior normalization of input data, need to normalize using StandardScaler
In order to train and test our data, let's split it into two parts: 75%-25%. Then we'll apply the above mentioned models to see which of them performs better with selected parameters.
 using DecisionTreeClassifier to fit training data
 Print corresponding score and confusion matrix.
 Using GraphViz plot Decision trees
 Plotting ROC curve
 Implementing K-fold cross validation upto k=10
 Applied RandomForestClassifier and check accuracy score
 Then KNN. KNN-using neighbors.KNeighborsClassifier - Starting with a K of 10. K is an example of a hyperparameter - a parameter on the model itself which may need to be tuned for best results on a particular data set.
 As choosing K is a bit tricky, so trying different values of K. Writing a for loop to run KNN with K values ranging from 1 to 50 and see if K makes a substantial difference.
 Then applying naive_bayes.MultinomialNB
 Next applying SVM with different kernels and check ROC.
 After that LogisticRegression
 Last applied ANN with KERAS.
 
 the best accuracy received with Artificial Neural Network where AUC of 0.87 +/- 0.01.
 Next is Logistic Regression with AUC of 0.847 +/- 0.01 and SVM (Linear Kernel) with AUC of 0.842 +/- 0.01
 
 ACKNOWLEDGEMENT:
 https://scikit-learn.org/stable/modules/cross_validation.html
 https://www.sundog-education.com/machine-learning/
 https://github.com/Sobiam1/Breast-Cancer-Classification-Using-Mammography-Masses-Results/blob/master/README.md
 
