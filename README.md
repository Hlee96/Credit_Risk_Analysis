# Credit_Risk_Analysis
## Overview
Evaluate credit risk using machine learning models. Oversample the data via Randomeoversampler, undersample the data via clustercentroids, combination via smoteen, and comparison via balancedrandomforestclassifer.

## Results
RandomOverSampler
<img width="733" alt="Screenshot 2022-10-28 230432" src="https://user-images.githubusercontent.com/108282027/198794417-7bb7802d-19b2-47a0-b53b-9c70e9145e85.png">
The accuarcy is 65%, with 1% high risk percision. 

SMOTE 
<img width="762" alt="Screenshot 2022-10-28 230607" src="https://user-images.githubusercontent.com/108282027/198795000-07506881-b7ce-41f0-8cf5-6419fb804756.png">
Accuracy is 62%

ClusterCentorids
<img width="755" alt="Screenshot 2022-10-28 230734" src="https://user-images.githubusercontent.com/108282027/198795679-69cfda2b-101c-49fc-96d7-ee2adf34350a.png">
Accuracy is 52%

## Summary
There is lack of percision to determine if credit risk is high. Low risk credits can still be faslely detected as high risk. The recommendation would be to avoid using any of the models above. 
