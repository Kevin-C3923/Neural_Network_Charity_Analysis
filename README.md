# Neural_Network_Charity_Analysis

### Overview of the analysis

Using deep learning network, we are tasked to determine which organization is worth to invest in.

### Results

#### Data Preprocessing

- What variable(s) are considered the target(s) for your model?
	
	"IS_SUCCESSFUL" is our main target 
	
- What variable(s) are considered to be the features for your model?
	
	"APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT" are the features for this model.

- What variable(s) are neither targets nor features, and should be removed from the input data?
	
	"EIN" and "NAME" are variables that are not needed, so they are removed.


#### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
	
	For this model we used a total of three hidden layers, with neurons being 100 and 30 with our activation being "tanh". 

- Were you able to achieve the target model performance?
	
	Even with these add on, our accuracy, 69%, did not meet the target model performance, 75%.
	
- What steps did you take to try and increase model performance?
	
	With this result, we are close to reaching our target. Therefor, it is likey we may change the activation to be another version or have multiple version and/or we may add more layers to the model.

### Summary

In conclusion, the model did not reach the target even with the different changes that were added. Therefor, a new model is need to determine where each point are located and make a self determine cluster to help improve the accuracy of the model.