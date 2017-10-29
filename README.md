# kaggle-higgsboson
My attempt for Higgs Boson ML challenge (https://www.kaggle.com/c/higgs-boson)

Approach:

1. Visualize distribution of input features 
2. Normalize features (after replacing UNDEF values with mean of rest of distribution)
3. Experiment with different Deep Neural Networks

Step 1 - Reduce Bias & Variance by altering hyperparameters such as 
  #Layers, 
  #Nodes in each layer, 
  Learning rate,
  Learning rate decay,
  Regularization,
  Beta 
  
Find out F1 score (precision, recall) at each stage to make correct decision. 
  
