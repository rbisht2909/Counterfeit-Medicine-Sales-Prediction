# Counterfeit-Medicine-Sales-Prediction

Counterfeit medicine are fake medicines which are either contaminated or contain the wrong or no active ingredient. They could have the right active ingredient but at the wrong dose. Counterfeit drugs are illegal and are harmful to the health. 10% of the world's medicine is counterfeit, problem is even worse in developing countries .Up to 30% of medicines in developing countries are counterfeit.
Millions of pills, bottles and sachets of counterfeit and illegal medicines are being traded across the world The World Health Organization (WHO) is working with International Criminal Police Organization (Interpol) to dislodge the criminal networks raking in billions of dollars from this cynical trade.

*Data Files*

Train Dataset = counterfeit_train.csv

Test Dataset = counterfeit_test.csv

*Formal Problem Statement*

Variable names are self explanatory.
Task here is to build predictive model for predicting sales figures given other information related to counterfeit medicine selling operations. We need to build our model on Train data . Test data doesnt have response column.

*Evaluation Criterion*

Score will be calculated as:
Score = 1-(MAE/1660)
Where MAE is mean absolute error on test file. Just focus on minimising MAE.
