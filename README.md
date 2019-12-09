# machine_learning

Lending Club is a peer to peer lending company based in the United States, 
in which investors provide funds for potential borrowers and investors earn a profit depending 
on the risk they take (the borrowers credit score).


# project objective
Build a pipeline to process the data and predict if a new loan or increase
should be approved for those customers who are  already on profile
# Data preprocessing
Data has 145 features which contains 109 numeric columns and 36 categorical columns.
Manually looked through the data and dropped some  features which obviously have no relationship with the target variable based on our research.
Some features are relating to the target variable but they have too many NAs so we assigned ‘None’ to categorical variables and 0 or -1 to some numerics features and other numeric features were assigned to mode value.


# data file - loan.csv
https://drive.google.com/open?id=1hx6mGt1m_Gf2XQyVDqAFIkYU05gT0MXT

# note
saved models were too big to upload as well, please ignore code that loads saved models and retrain.

# RESULTS
Best Model - LOGISTIC REGRESSION
Neural Network doesn’t seem to generalize well to test data but there’s a lot of room for improvement/tweaks to get there.
Based on the metrics, We can conclude that  loans predicted by the random forest as bad loans are either bad or have a high possibility of becoming so. For more details, please look through the power point file, consulting proposal
