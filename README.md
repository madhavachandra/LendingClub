# Lending Club Data Analysis and Modeling
Predicting bad loans from Lending Club data
The purpose of this study was to determine what constitutes a risky lending. 
Each line item in the data corresponded to a loan, and had various features relating to loan amount, employment information of the borrower, payments made, and the classification of the loan as charged off or active with any delays in payments noted.

An exploratory data analysis was performed on the data, to look for outliers and individual distributions of the variables. 
Following which, the interactions between these variables were studied to weed out highly correlated variables. 
Owing to low representation of defaults in the sample, this was treated as an imbalanced class problem, wherein traditional random sampling would not yield optimal results. 
To overcome this problem, stratified sampling, random under and over sampling, SMOTE and ADASYN methodologies were explored.

All the above sampling methodologies were trained and tested on logistic regression to pick which sampling procedure to follow for this exercise. 
Following which, it was found that SMOTE gave the best results. 
To best classify which loans would likely default from the given dataset, various statistical learning techniques, such as Regression, Tree-based methods- standalone, boosting and bagging ensemble methods, Support Vector Machines and Neural Networks were employed.  
Amongst these classifiers, Gradient boosting was observed to have the best performance, although with further fine tuning, Deep Neural Networks could possibly classify better. 
