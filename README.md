# Predicting Customer Churn at Beta Bank Using Machine Learning
![](https://pbs.twimg.com/profile_banners/1450876299858358278/1651250341/1500x500)


## Project Overview:

Beta Bank is facing a gradual loss of customers each month. Since retaining existing clients is more cost-effective than acquiring new ones, the goal is to build a predictive model that can identify customers at risk of leaving the bank.

The task involves:

- Using historical customer behavior and contract termination data.

- Developing a model that maximizes the F1-score, with a minimum threshold of 0.59 for approval.

- Evaluating model performance on the test set using both F1-score and AUC-ROC, and comparing the two metrics to ensure robust predictions.


## Data Dictionary:

| Variable        | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| RowNumber       | Data string index                                                           |
| CustomerId      | Unique customer identifier                                                  |
| Surname         | Customer surname                                                            |
| CreditScore     | Credit score                                                                |
| Geography       | Country of residence                                                        |
| Gender          | Gender                                                                      |
| Age             | Age                                                                         |
| Tenure          | Period during which a customer's fixed-term deposit has matured (years)     |
| Balance         | Account balance                                                             |
| NumOfProducts   | Number of banking products used by the customer                             |
| HasCrCard       | Customer has a credit card (1 - yes; 0 - no)                                |
| IsActiveMember  | Customer activity (1 - yes; 0 - no)                                         |
| EstimatedSalary | Estimated salary                                                            |


## Impact

This project developed a predictive model to identify Beta Bank clients at risk of leaving, helping the bank prioritize retention efforts. Among the models tested, the Random Forest classifier with minority class replication performed best, achieving an F1-score of 0.58 and an AUC-ROC of 0.81. The model successfully identified 66% of clients who left, providing a reliable tool to support customer retention and reduce revenue loss.

"TripleTen" Project #8
