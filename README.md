# Bank_Churner_Classifier
The goal of this project is to predict credit card customers who are gonna get churned, So that the bank can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction. A GradientBoostingClassifier model was chosen which after data cleaning produced an accuracy score of 96%.

## Workflow

### Data Collection:
The dataset was taken from kaggle [kaggle](https://www.kaggle.com/sakshigoyal7/credit-card-customers)

### Data Preprocessing:
1. Outliers in the data were handled using IQR and Boxplot.
2. Data imbalance was taken care of by performing stratified train_test_split.
3. One-Hot encoding was used to transform catogorical features.

### Model Selection:
A gradient booting classifier was selected, hyper-parameter tuning was not performed as the base model preformed really well on the dataset.

