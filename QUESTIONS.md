# Questions
Please try to answer the following questions.
Reference your own code/Notebooks where relevant.

Data exploration and LSTM: data_exploration.ipynb

Prophet: training_prophet.ipynb

## Your solution
1. What machine learning techniques did you use for your solution? Why?

* The model has been trainned and predicted using LSTM and the prophet library from Facebook. 

2. What is the error of your prediction?

   a. How did you estimate the error?
   
   * The error is measured with Normalized Root Mean Squared Error (NRMSE) 
   
   b. How do the train and test errors compare?
   
   * Since, test doesn't have prediction value. Cross validaton has been performed to assess the model.
   
   c. How will this error change for predicting a further week/month/year into the future?
   
   * It will increase for predicting a further.
   
3. What improvements to your approach would you pursue next? Why?
   
   * I will try to optimise hyperperameters phrophet and LSTM. Also, explore other algorithms.
    
4. Will your approach work for a new household with little/no half-hourly data?
  * It won't work because we dont have any information for a new household. 
  
   How would you approach forecasting for a new household?
   * Meta data information and cluster analysis might helpful for initial forcasting for a new household. 
