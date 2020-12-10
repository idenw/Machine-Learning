# Machine-Learning
In this project
we started with EDA
we filled Age column with the Means of Pcabin Means
droppped the Cabin column as there were too many missing values
also dropped the empty rows because there were only few
we used get_dummies for the categorical columns sex,embarked,Pclass and chosed to drop the first columns as True
we concat theese with our df
and of cource we dropped the columns which we have dummied
we also dropped PassengerId column as it is only like an index
we also dropped the name and ticket columns as they are strings.but some str functons may apply as you wish for further EDA
Our DataFrame became all numeric and resdy for the Machine Learning Process
we used logistic regression
we splitted the DataFrame as X_train, X_test, y_train, y_test
we used X_train, y_train to train our model
we then made predictions to predict y_pred by using X_test
and lastly we draw our confusion matrix and classification report
we got 0,83 accuracy and 0.76 for F1 score.

