# Credit_Risk_Analysis

The purpose of this analysis is to assess the best way to sample data for a machine learning model that predicts the risk of credit loans to certain borrowers. Among the many metrics used to assess risk, a few notable ones were home ownership status (rent, mortgage, owner), deliquency on previous loans, annual income, and loan amount.

## Results

### Naive Random Oversampling
![](images/naive_oversampling.png)

The above output tells us this:
- The precision for high risk loans is extremely low while the precision for low risk loans is extremely high. In other words, this model is highly effective at predicting true positive low risk loans but is likely to have many false positives for high risk loans. 
- The recall indicates that this model is just above average at correctly predicting high risk and low risk loans. In other words, these recall numbers indicate that this model only predicts correctly 72% of the time for high risk loans and 61% of the time for low risk loans.
- The balanced accuracy score for is the average recall of each class (low risk and high risk), which is 66.79%. This model is 66.79% accurate at making predictions.

### SMOTE Oversampling
![](images/SMOTE.png)
