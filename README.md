# Neural_Network_Charity_Analysis

## Overview
Through the knowledge of Neural Networks and Machine Learning, our client wants help with their foundation on how to predict where to make investments. A large dataset was provided to create a binary classifier that is capable of predicting weather applicants will be successful if funded by Alphabet Soup, the clients’ foundation. 

Included in the dataset is over 34,000 organizations that have received funding from Alphabet Soup over the years. There are seven columns in the dataset including application types, company names, and if the money was used successfully. 

Since the dataset is large, analysis was split up into three sections for clarification. This included preprocessing the data for a Neural Network Model; compiling, training, and evaluating the model; and finally optimizing the model. 

## Results

*Data Processing*

	
  •	The variable considered the target for the model was, if the funding was successful.
  
	
  •	The variables that are considered to be the features of our model included initially the application type and the classification (I.e. government organization). See figures to help illustrate value counts for application types and classification to determine data processing:


![](https://github.com/holleyvoegtle/Neural_Network_Charity_Analysis/blob/main/images/application_type.png)


![](https://github.com/holleyvoegtle/Neural_Network_Charity_Analysis/blob/main/images/classification.png)



	
  •	The variables that were originally removed from the data was the EIN column (a number ID) and company names. But for the optimization model, the names were kept. 	


*Compiling, Training, and Evaluating the Model*

	
  •	For the optimization part, the amount of hidden layers were threes with the neurons as: 120, 50, 10. The activation functions stayed the same with all three layers as RELU and the output layer as sigmoid. The reason these parameters were selected was because this data helped fit the data with a 75% accuracy. It models the changes in the input variables and how its affected. 
  
	
  •	We were able to achieve the target model performance with 75.5%
  
	
  •	The steps we took to increase the performance was by increasing the node and the hidden layers. Also we include the names of the companies in the model. 



## Summary 

The initial model that was run only produced a 53.9% accuracy. But when we optimized the data with increased nodes, hidden layers, neurons, and company names, our accuracy increased to 75.5%. If we were to further this analysis, it would be beneficial to have more variables to increase the dataset. But we could also use logistic regression and random forest models to solve for this classification problem. 
