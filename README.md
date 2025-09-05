# Introduction
This is a Complete Project I made using a very large sized dataset of about 100000 Records and 26 columns.

# Dataset Description:
- The dataset is a bank data set that is very large and contains a lot of columns that have missing values and outliers in most columns, Also the dataset had a lot of uncommon patterns that made the columns
that are supposed to be numerical columns, but are object columns instead.

# Dataset Cleaning:

I've cleaned and handled all the missing values in the dataset appropriately and check for duplicates.
- The dataset before cleaning and fixing the broken columns:
![Dataset Before Cleaning](https://github.com/RattleBrattle/Credit-Score-Decision-Tree-Machine-Learning/blob/main/Visualizations%20&%20Code%20Images/Dataset%20before%20Cleaning..png?raw=true)

- The dataset after cleaning and fixing the broken columns:
![Dataset After Cleaning](https://github.com/RattleBrattle/Credit-Score-Decision-Tree-Machine-Learning/blob/main/Visualizations%20&%20Code%20Images/Dataset%20after%20Cleaning..png?raw=true)

- I've also checked each and every column in the EDA file, Analyzing each column correctly and removing outliers, Also removed unnecessary columns from the dataset.

Also these are the patterns that made the columns broken, and this is a method I used to clean all of them and first convert them to int.
![Pattern Removal](https://github.com/RattleBrattle/Credit-Score-Decision-Tree-Machine-Learning/blob/main/Visualizations%20&%20Code%20Images/Code%20for%20removing%20common%20patterns..png?raw=true)

## Visualizations:

- The Visualizations of the dataset are in the Visualizations folder but here are some pictures I took.
![Occupation with credit score hue](https://github.com/RattleBrattle/Credit-Score-Decision-Tree-Machine-Learning/blob/main/Visualizations%20&%20Code%20Images/Occupation%20with%20credit%20score%20hue..png?raw=true)

![Before & After outliers](https://github.com/RattleBrattle/Credit-Score-Decision-Tree-Machine-Learning/blob/main/Visualizations%20&%20Code%20Images/Monthly%20Inhand%20Salary%20Boxplot%20before%20and%20after%20Winsorize..png?raw=true)

# Machine Learning:
I've used a Decision Tree Machine Learning Algorithm to predict the credit score of a customer, and also tried making a Random Forest Tree Model and the results did improve but not by alot.

- For both, I used a test-validate-train split of 60-20-20 and then used GridSearchCV to search for the best parameters to use with the models.

## 1. Decision Tree Model:
- I Used GridSearchCV to search for the best parameters to use with the model and managed to obtain a 79% accuracy on the test set and a confusion matrix that looks like this:
![Confusion Matrix of Decision Tree]()
