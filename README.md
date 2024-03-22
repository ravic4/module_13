# module_13: Venture Funding with Deep Learning 
This assignment was completed with some support from Shah in the Office Hours. 
## What this code does: 
This code takes in data from a CSV of applicants to figure out to what extent the firm can be successful. 
1. Using the OneHotEncoder an StandardScaler to scale our data
2. We create deep neural network over three models each with different neurons: Model 1 = 54, Model 2 = 100, and model 3 has 200. Through this we came up with three different models that had alternating loss and accuracies. 
3. Model 1 loss: 0.55 Accuracy: 0.73, Model 2 loss:0.71 Accuracy:0.48 , Model 3 loss :0.56 Accuracy: 0.73
From this, Model 3 and 1 perform the best from the three. However, overall, these models are only somewhat effective due to their low accuracy scores (of 0.73) and higher loss scores. This shows that our neural-network model is only helpful to some extent in determining startup success
