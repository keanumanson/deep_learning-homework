###Evaluate the performance of each model
####*note: due to the fact i had a m! mac i had to do the assignment on google collab so there are some code variations at the begining with the imports/install and i manually uploaded the csv file*

##Summary


- Which model has a lower loss?
    The HOMEWORK-1 Fear and Greed (FNG) predictor model had a loss of 0.1861, and the HOMEWORK-2 Closing predictor model had a loss of 0.0479.
    So the closing price predicting model had a much lower loss

- Which model tracks the actual values better over time?
    Overall the closing price predicting model (HOMEWORK-2-predictor closing) tracked the actual values better over time. 

- Which window size works best for the model?
    Lower windows make the prediction mirror the real prices more accurately on a short scale within the plot. But when the larger windows were used it dampened the predicted movements.
    
    Therefore a balanced window of around 7 seems to work well. 
