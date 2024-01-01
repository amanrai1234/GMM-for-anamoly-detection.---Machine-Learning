# Gaussian-Mixture-model-for-anamoly-detection.





# Step1: 

loaded the dataset using pandas and added the output 
feature after concatenation of the new dataset for capturing 
anomalies

# Step2: 

scaled and trained the model using sklearn Gaussian 
mixture models.

# Step3: 

evaluated the models using confusion matix and 
accuracy

# Step4: 

# grid search using BIC method.

## Parameter selections and grid search result:

Here the hyperparamter selection can be done by looking at the above figure where I have done 
grid search using BIC(Bayesian information criterion), and here I am using elbow method to do 
the choose the best model and I think if I go with that I might choose the number of 
clusters(components as 5) as I have done grid search on 5 compenents(you can just increase 
the number bic and np.zeros to select how many components we want). we can choose the 
elbow method and in the above graph it is more likely to be 2, but if we increase the number of 
components it can be greater than that as well, but the main idea of elbow method iss that the 
values don't descend that much after a certain point although in the above figure it might not look 
like an elbow but if we increase the number of compenets then it is likely to be more. I think 5 
would be the best model because it has more accurate readings compared to the other number 
of components. But then if you want to make a tradeoff between computation resources and the 
accuracy we can choose whichever is better accordingly. But yeah the values(increasing 
components) after a certain point don't descend in the plot










# Dataset was too big, I was not able to upload it to git. Please drop me an email at amanrai942@gmail.com, I could manage it to send it to you.


