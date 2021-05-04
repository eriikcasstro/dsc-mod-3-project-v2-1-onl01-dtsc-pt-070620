# Project 

## Bank Personal Loan Modelling
This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.

## Components
### Jupyter Notebook
The Jupyter Notebook is our key deliverable and contains details of our approach and methodology, data cleaning, exploratory data analysis, model training and tuning and recommendations.

### Presentation
The presentation gives a high-level overview of our approach, findings and recommendations for non-technical stakeholders. It is aimed to be between 5 and 10 minutes long.

### Data
The dataset can be found in this repository. 

### Data Analysis 

![image](https://user-images.githubusercontent.com/36000513/116994916-4888cf80-acd1-11eb-9138-9509c3d7aad4.png)

29.4% of customers have a credit card

![image](https://user-images.githubusercontent.com/36000513/116994949-550d2800-acd1-11eb-93f8-dc3f433b5168.png)

59.6% users use online banking


## Conclusion

In this problem Bank XYL wanted to explore different ways to create marketing strategies with better target marketing increasing success ratio with minimal budget.
Bank XYL provided with the task to predict the likelyhood of a liability customer buying personal Loans. 
This will help the bank better aim the marketing strategies. 
Summary of key steps that lead to the results: 
    1. Data was gathered from the previous campaign, which included: age, Income, Family, CCA, Family, Education and more.
       There were 5000 entries available to train the algorithm
    2. Data was cleaned, fortunately there were not any null values in the data. 
    3. Categorical data was dealt with using one got encode 
    4. Data was normalized using StandardScaler
    5. F1 score was determined to be used as the measure of quality of prediction 
    6. KNN algorithm was the baseline model with a F1 score of 73% 
    7. Other classifiers were trained including;  Logistic Regression, KNN, Decisiton Tree, Random Forest, Adaboost, 
       Gradient Boosting and XGB
    8. This classifiers were further tuned using GridSearchCV, which pointed out that the best Classifier was XGB 
    9. XGB was used to find which were the most important variables when acquiring a Loan. 
    10. XGB has a probaility of 93% ot find the right customers that most likely will acquired a loan
   
![image](https://user-images.githubusercontent.com/36000513/116995386-eb414e00-acd1-11eb-8f0f-e87e41ad831b.png)


This variables were: 
 - Education 3 (Advanced/ Proffesional)
 - Education 2 (Graduate) 
 - Family Size (especially of 3 and 4)
 - Income 
 - CD Account
#### Recomendations
 - Emphasize Professional and Graduates customers
 - Focus on customers with families larger than 2
 - Focus on customers with an anual income larger than 105k
 
 If the recommendations are taken, then there's a probability of 92% that the customers will acquire a loan. 
