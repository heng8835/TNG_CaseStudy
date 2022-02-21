# TNG_CaseStudy

### Goal / Case Requirement:
- To build the final model with the highest performance scores - to detect fraudulent transactions
- Require to showcase features importance and imbalanced handling

### Data Description: 
Dataset presents transactions that occurred, where 148 frauds out of 50,000 transactions
Features V1, V2, … V28 are the principal components
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction
Feature 'Amount' is the transaction Amount, can be used for dependant cost-sensitive learning
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise


### To Run:
Amend datasource path for blocks:
df=pd.read_csv('sample_data.csv')


## Thank you
