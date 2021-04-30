# Machine Learning Projects Using Python by Soorya Parthiban.

## Project 1: Adult Income Classification

### Links
[Adult Income Classification Jupyter Notebook Link](https://github.com/drdataSpp/Spp-Machine-Learning-using-Python/blob/main/SPP_ML_1%20Adult%20income%20predictions.ipynb)<br>
[Adult Income Dataset Link](https://archive.ics.uci.edu/ml/datasets/adult)

### Project Description
Prediction task is to determine whether a person makes over 50K a year.

### How did I solve this problem?
1. I started with exploring the dataset by performing statistical analysis.
2. After performing statistical analysis, I found the null values and filled the null values using the respective column's mode values.
3. After filling the null values, I performed data visualization to understand the relation between the dependent variable and outcome variable.
4. After performing data visualization, I pre-processed the dataset where I converted all the categorical values to numerical values.
5. Once the dataset was pre-processed, I split the 70% of data into the training set and 30% of data into testing set.
6. A Logistic Regression model was trainied using the training data and evaluated using the testing data.
7. To reduce the curse of dimenstionality, using Principle Component Analysis method I created another train and test set with lesser columns or features.
8. With the above PCA train and test set, a Logistic Regression and Decision Tree model was trained and evaluated. 

### Conclusion
Both, Logistic Regression and Decision Tree model performed well on the test set and got an accuracy of **82%**.
