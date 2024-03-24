# googleadvanced_da
Google Advanced Data Analytics capstone project

This project looked at HR data for  a fictionalized company Salifort Motors. Due to high turnover rate, build a classification model to predict if an employee will leave the company.

Two models were built - a Logistic Regression model and a Random Forest model. The model with the highest F1 score was chosen.

### Overview
The goal of the project was to compare the performance of a logistic regression and random forest model to predict employee turnover.
The project utilized the HR data from a fictionalized company Salifort Motors.
The final model chosen was random forest with an F1 score of 95.6%, 98.5% precision, and 93% recall.
Important features in determining the employees leaving the company are satisfaction levels, number of projects, last evaluation, tenure, and average monthly hours.

### Business Understanding
Salifort wants to create a corporate culture that supports employee success and professional development. However, currently there is a high turnover rate of employees. This high turnover rate is financially costly as the company makes a big investment in recruiting, training, and upskilling its employees. It is important to understande what causes employees to leave the company.

### Data Understanding
The data consists of 14,999 rows and 10 features. The features satisfaction level, last evaluation, and average monthly hours. The bar chart shows the percentage of employees retained vs. those who left.
![Employee left and retained percentage](https://github.com/lhdatalab/googleadvanced_da/blob/main/Employee_percentage.png?raw=true)

### Modeling and Evaluation
A random forest model was used to determine feature importance in which employees would leave the company.
The below feature importance plot showed the top 5 important ones are satisfaction level, number project, last evaluation, tenure, and average monthly hours.
The model had  a performacne of 95.6% F1 score.
![Random forest feature importance](https://github.com/lhdatalab/googleadvanced_da/blob/main/
Feature_importance.png?raw=true)

