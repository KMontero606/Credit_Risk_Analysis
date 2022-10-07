# Credit_Risk_Analysis
![image](https://user-images.githubusercontent.com/106962921/194563249-1b2adc8a-19f8-4be2-ab7f-06c5132eb52d.png)

## Overview of the analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, one will need to employ different techniques to train and evaluate models with unbalanced classes.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. 

Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. 

Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once completed, evaluate the performance of these models and make a written recommendation on whether these models should be used to predict credit risk.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
  - ### ***Oversampling RandomOverSampler Algorithm***

  - ### ***Oversampling SMOTE Algorithm***

  - ### ***Undersampling ClusterCentroids Algorithm***

  - ### ***Combinatorial SMOTEENN Algorithm***

  - ### ***BalancedRandomClassifier Algorithm***
    - Balanced accuracy score:
    
    ![image](https://user-images.githubusercontent.com/106962921/194574452-e68317fa-bc29-41c4-8bef-1ff947044ed2.png)

    - Precision score:
    
    ![image](https://user-images.githubusercontent.com/106962921/194574520-94af2a45-fbae-4ba1-82c4-7f4bca196043.png)
    
    - Recall score:
    
    ![image](https://user-images.githubusercontent.com/106962921/194574575-08a1c13b-a67b-498f-9b75-b602c8ce1e40.png)


  - ### ***EasyEnsembleClassifier Algorithm***

    - Balanced accuracy score:
    
    ![image](https://user-images.githubusercontent.com/106962921/194574071-37cc4e0f-d57a-463e-a392-76d0c51c403c.png)

    - Precision score:

    ![image](https://user-images.githubusercontent.com/106962921/194574272-f9eea882-9076-4716-9ba4-976728e916c8.png)
    
    - Recall score:
    
    ![image](https://user-images.githubusercontent.com/106962921/194574322-2ff6b0a6-eaa4-4be6-8691-00653c2a306d.png)

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
