# Credit_Risk_Analysis
![image](https://user-images.githubusercontent.com/106962921/194563249-1b2adc8a-19f8-4be2-ab7f-06c5132eb52d.png)

## Overview of the analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, one will need to employ different techniques to train and evaluate models with unbalanced classes.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. 

Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. 

Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once completed, evaluate the performance of these models and make a written recommendation on whether these models should be used to predict credit risk.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
  - ### ***Oversampling RandomOverSampler Algorithm***
    - Balanced accuracy score: 0.66
    
    ![image](https://user-images.githubusercontent.com/106962921/194575751-92a2287c-8973-48af-963f-98f266bc8d32.png)

    - Precision score: low precision for high-risk, high precision for low-risk

    ![image](https://user-images.githubusercontent.com/106962921/194575852-3f9d9259-ef14-4aa2-9574-78cafd52b497.png)

    - Recall score: 0.71 for high-risk, 0.60 for low-risk  

    ![image](https://user-images.githubusercontent.com/106962921/194575915-63387cae-3917-4732-8ce6-2e7ec19df96f.png)

  - ### ***Oversampling SMOTE Algorithm***
    - Balanced accuracy score: 0.66
    
    ![image](https://user-images.githubusercontent.com/106962921/194576053-f1b4427e-1ba1-4ba9-8ef4-4c5805c64c80.png)
    
    - Precision score: low precision for high-risk, high precision for low-risk
    
    ![image](https://user-images.githubusercontent.com/106962921/194576115-46564017-d96e-4c98-807e-992f4493793b.png)
    
    - Recall score: 0.63 for high-risk, 0.69 for low-risk 

    ![image](https://user-images.githubusercontent.com/106962921/194576202-ae88fe63-58a2-4cec-84f8-13b22f97ab2f.png)
    
  - ### ***Undersampling ClusterCentroids Algorithm***
    - Balanced accuracy score: 0.54

    ![image](https://user-images.githubusercontent.com/106962921/194576628-3ace8f48-fe29-4cc2-b344-cf64fec9af58.png)

    - Precision score: low precision for high-risk, high precision for low-risk

    ![image](https://user-images.githubusercontent.com/106962921/194576694-fb43fec6-e18c-4422-965c-e00bd0d169c9.png)

    - Recall score: 0.69 for high-risk, 0.40 for low-risk

    ![image](https://user-images.githubusercontent.com/106962921/194576783-b5b92bba-c1cb-44d4-9e7c-66ac1d9da76e.png)  

  - ### ***Combinatorial SMOTEENN Algorithm***
    - Balanced accuracy score: 0.69
    
    ![image](https://user-images.githubusercontent.com/106962921/194576908-99e25414-40a6-487c-a009-35638f249cb4.png)

    - Precision score: low precision for high-risk, high precision for low-risk
    
    ![image](https://user-images.githubusercontent.com/106962921/194576964-491dd815-b979-400b-853f-8c35e7b0139b.png)

    - Recall score: 0.80 for high-risk, 0.57 for low-risk
  
    ![image](https://user-images.githubusercontent.com/106962921/194577118-73d10c2a-4de0-4f6f-98ec-0b0089d62749.png)

  - ### ***BalancedRandomClassifier Algorithm***
    - Balanced accuracy score: 0.79
    
    ![image](https://user-images.githubusercontent.com/106962921/194574452-e68317fa-bc29-41c4-8bef-1ff947044ed2.png)

    - Precision score: low precision for high-risk, high precision for low-risk
    
    ![image](https://user-images.githubusercontent.com/106962921/194574520-94af2a45-fbae-4ba1-82c4-7f4bca196043.png)
    
    - Recall score: 0.67 for high-risk, 0.91 for low-risk
    
    ![image](https://user-images.githubusercontent.com/106962921/194574575-08a1c13b-a67b-498f-9b75-b602c8ce1e40.png)


  - ### ***EasyEnsembleClassifier Algorithm***

    - Balanced accuracy score: 0.93
    
    ![image](https://user-images.githubusercontent.com/106962921/194574071-37cc4e0f-d57a-463e-a392-76d0c51c403c.png)

    - Precision score: low precision for high-risk, high precision for low-risk

    ![image](https://user-images.githubusercontent.com/106962921/194574272-f9eea882-9076-4716-9ba4-976728e916c8.png)
    
    - Recall score: 0.91 for high-risk, 0.94 for low-risk
    
    ![image](https://user-images.githubusercontent.com/106962921/194574322-2ff6b0a6-eaa4-4be6-8691-00653c2a306d.png)

## Summary:
In summary, EasyEnsembleClassifier model may be the best one for predicting credit risk analysis because of the model's accuracy of 0.93. However, it does provide low precision for high-risk analysis, but has high precision for low-risk. On top of that, the recall score are good enough to state that the model will be good at analysing credit risk.
